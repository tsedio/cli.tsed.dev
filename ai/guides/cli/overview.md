---
title: CLI Overview
description: Understand how @tsed/cli-core, prompts, tasks, and MCP servers compose to build interactive developer tooling.
---
# CLI Overview

The Ts.ED CLI is no longer only a project scaffolder. The current runtime layers `@tsed/cli-core` with three specialized packages:

-   `@tsed/cli-prompts` to orchestrate conversational flows with the Ts.ED DI container.
-   `@tsed/cli-tasks` to stream progress, logs, and nested steps inside the terminal.
-   `@tsed/cli-mcp` to expose any CLI capability through the Model Context Protocol (MCP) so AI assistants can call it.

This page shows how the pieces fit together, which versions you need, and how to bootstrap an interactive workflow.

## Architecture at a glance

1.  **`@tsed/cli-core`** bootstraps the DI container, loads installed plugins, and resolves commands/tasks/prompts via decorators.
2.  **`@tsed/cli-prompts`** declares reusable prompt providers. Each prompt receives the DI context, so you can reuse services or share state across steps.
3.  **`@tsed/cli-tasks`** runs ordered task arrays and injects a `TaskLogger` into each step so you can stream progress, logs, and status updates to the terminal.
4.  **`@tsed/cli-mcp`** wraps the same DI container in an MCP server. External clients (Claude Desktop, VS Code Agents, etc.) can call CLI tools through the MCP spec without shell access.

The runtime ensures tasks and prompts always run inside a `DIContext`, so your generators, plugins, and MCP tools share the exact same services.

## Compatibility matrix

| Package             | Minimum version | Node.js recommendation | Notes                                                                                                  |
| ------------------- | --------------- | ---------------------- | ------------------------------------------------------------------------------------------------------ |
| `@tsed/cli-core`    | `7.0.0`         | 3+                     | Base runtime for custom CLIs and plugins.                                                              |
| `@tsed/cli-prompts` | `7.0.0`         | 3+                     | Depends on `@tsed/di` and `@clack/prompts`.                                                            |
| `@tsed/cli-tasks`   | `7.0.0`         | 3+                     | Uses WHATWG streams for log forwarding.                                                                |
| `@tsed/cli-mcp`     | `7.0.0`         | 20+ recommended        | MCP transports lean on `@modelcontextprotocol/sdk` features that benefit from the Node 20 fetch stack. |

::: tip
The CLI binaries still support Node 16, but interactive prompts/tasks rely on `Intl` APIs that work best on Node 18+. Running on Node 20 ensures the bundled MCP server can reuse `fetch` without polyfills.
:::

`@tsed/cli-core` provides a bunch of reusable Ts.ED injectable services to handle differents usecases:

<ApiList query="symbolType.includes('class') && module === '@tsed/cli-core'" />

## Quickstart

1.  Install the runtime packages inside any Node.js project. Include `@tsed/cli-mcp` only if you plan to expose commands over MCP:

::: code-group

```bash [npm]
npm install @tsed/cli-core @tsed/cli-prompts @tsed/cli-tasks
npm install @tsed/cli-mcp --save-dev # optional MCP server
```

```bash [yarn]
yarn add @tsed/cli-core @tsed/cli-prompts @tsed/cli-tasks
yarn add -D @tsed/cli-mcp # optional
```

```bash [pnpm]
pnpm add @tsed/cli-core @tsed/cli-prompts @tsed/cli-tasks
pnpm add -D @tsed/cli-mcp # optional
```

```bash [bun]
bun add @tsed/cli-core @tsed/cli-prompts @tsed/cli-tasks
bun add -d @tsed/cli-mcp # optional
```

:::

2.  Adopt the same project layout the official CLI uses so your commands, tools, resources, and templates stay discoverable:

```txt
my-cli/
├─ package.json
├─ tsconfig.json
└─ src/
   ├─ bin/
   │  └─ index.ts
   ├─ commands/
   │  └─ InteractiveWelcome.ts
   ├─ resources/
   ├─ tools/
   ├─ prompts/
   └─ templates/
```

Peeking at `packages/cli/src/bin/tsed.ts` in this repo shows the exact layout Ts.ED uses in production.

3.  Register prompts, tasks, and commands. Pick whichever API fits your style—decorators [Command](/ai/api/cli-core/types/decorators/decorator-command.md) or the [command](/ai/api/cli-core/types/fn/function-command.md) helper:

::: code-group

```ts [Decorators]
import {mkdir, writeFile} from "node:fs/promises";
import {join} from "node:path";

import {CliExeca, Command, type CommandProvider} from "@tsed/cli-core";
import type {PromptQuestion} from "@tsed/cli-prompts";
import type {Task} from "@tsed/cli-tasks";
import {inject} from "@tsed/di";

type Runtime = "node" | "bun";

export interface WelcomeContext {
  projectName: string;
  runtime: Runtime;
  installDeps: boolean;
}

@Command({
  name: "interactive:welcome",
  description: "Guide developers through project bootstrap with prompts and tasks"
})
export class InteractiveWelcome implements CommandProvider<WelcomeContext> {
  protected cliExeca = inject(CliExeca);

  async $prompt(initial: Partial<WelcomeContext>): Promise<PromptQuestion[]> {
    return [
      {
        type: "input",
        name: "projectName",
        message: "Project name",
        default: initial.projectName || "awesome-cli",
        validate(value) {
          return value?.trim() ? undefined : "Project name is required (letters, numbers, and dashes are allowed)";
        }
      },
      {
        type: "list",
        name: "runtime",
        message: "Choose a runtime",
        choices: [
          {name: "Node.js", value: "node"},
          {name: "Bun", value: "bun"}
        ],
        default: initial.runtime || "node"
      },
      {
        type: "confirm",
        name: "installDeps",
        message: "Install dependencies after generating files?",
        default: true
      }
    ];
  }

  $mapContext(ctx: Partial<WelcomeContext>): WelcomeContext {
    return {
      projectName: ctx.projectName?.trim() || "awesome-cli",
      runtime: (ctx.runtime as Runtime) || "node",
      installDeps: ctx.installDeps ?? true
    };
  }

  async $exec(): Promise<Task<WelcomeContext>[]> {
    return [
      {
        title: "Create workspace",
        task: async (context, logger) => {
          const destination = join(process.cwd(), context.projectName);
          await mkdir(destination, {recursive: true});
          await writeFile(join(destination, "README.md"), `# ${context.projectName}\n\nGenerated with the Ts.ED CLI runtime.\n`);
          logger.message(`Workspace ready at ${destination}`);
        }
      },
      {
        title: "Install dependencies",
        skip: (context) => (!context.installDeps ? "Skipped by --no-install flag" : false),
        task: async (context, logger) => {
          logger.message("Installing packages (this may take a minute)...");

          const packageManager = context.runtime === "bun" ? "bun" : "npm";

          return this.cliExeca.run(packageManager, ["install"], {
            cwd: join(process.cwd(), context.projectName)
          });
        }
      }
    ];
  }
}
```

```ts [Functional API + inputSchema]
import {mkdir, writeFile} from "node:fs/promises";
import {join} from "node:path";

import {CliExeca, command} from "@tsed/cli-core";
import type {Task} from "@tsed/cli-tasks";
import {inject} from "@tsed/di";
import {s} from "@tsed/schema";

type Runtime = "node" | "bun";

export interface WelcomeContext {
  projectName: string;
  runtime: Runtime;
  installDeps: boolean;
}

const WelcomeSchema = s.object({
  projectName: s.string().prompt("Project name").default("awesome-cli"),
  runtime: s
    .enums<Runtime>(["node", "bun"])
    .prompt("Choose a runtime")
    .choices([
      {label: "Node.js", value: "node"},
      {label: "Bun", value: "bun"}
    ])
    .default("node"),
  installDeps: s.boolean().prompt("Install dependencies after generating files?").default(true)
});

export const InteractiveWelcome = command<WelcomeContext>({
  name: "interactive:welcome",
  description: "Guide developers through project bootstrap with prompts and tasks",
  inputSchema: WelcomeSchema,
  async handler(): Promise<Task<WelcomeContext>[]> {
    const cliExeca = inject(CliExeca);

    return [
      {
        title: "Create workspace",
        task: async (ctx, logger) => {
          const destination = join(process.cwd(), ctx.projectName);
          await mkdir(destination, {recursive: true});
          await writeFile(join(destination, "README.md"), `# ${ctx.projectName}\n\nGenerated with the Ts.ED CLI runtime.\n`);
          logger.message(`Workspace ready at ${destination}`);
        }
      },
      {
        title: "Install dependencies",
        skip: (ctx) => (!ctx.installDeps ? "Skipped by --no-install flag" : false),
        task: async (ctx, logger) => {
          logger.message("Installing packages (this may take a minute)...");
          const packageManager = ctx.runtime === "bun" ? "bun" : "npm";
          return cliExeca.run(packageManager, ["install"], {
            cwd: join(process.cwd(), ctx.projectName)
          });
        }
      }
    ];
  }
}).token();
```

:::

::: tip
The functional example shows how `inputSchema` replaces ad-hoc args/options. See the [Commands guide](/guide/cli/commands#input-schema) for every helper (`.prompt()`, `.choices()`, `.when()`, etc.).
:::

4.  Bootstrap the runtime in `src/bin/index.ts` (or any entrypoint under `src/bin`). This mirrors the official `packages/cli/src/bin/tsed.ts` entrypoint without the module-alias hook:

```ts
#!/usr/bin/env node
import {CliCore, type PackageJson} from "@tsed/cli-core";

import pkg from "../../package.json" assert {type: "json"};
import {InteractiveWelcome} from "../commands/InteractiveWelcome.ts";

CliCore.bootstrap({
  name: "awesome",
  pkg: pkg as PackageJson,
  commands: [InteractiveWelcome],
  tools: [],
  resources: [],
  prompts: [],
  updateNotifier: false,
  checkPrecondition: false,
  logger: {
    level: process.env.DEBUG ? "debug" : "info"
  }
}).catch((error) => {
  console.error(error);
  process.exit(1);
});
```

5.  Execute commands through Node + SWC so both the functional API and decorators work without a build step:

```bash
 node --import @swc-node/register/esm-register src/bin/index.ts interactive:welcome
```

-   guides the user through a `PromptRunner`-powered conversation to collect inputs,
-   hands the data to `@tsed/cli-tasks` so each `Task<Context>` streams logs through the shared renderer,
-   and persists the result via any Ts.ED service available in DI.

## Where to go next

-   Learn how to configure `@Command`/`command()` in [Commands](/guide/cli/commands).
-   Build custom generators with [Templates](/guide/cli/templates).
-   Compose rich multi-step conversations in [Prompts](/guide/cli/prompts).
-   Stream progress, handle retries, and chain subtasks in [Tasks](/guide/cli/tasks).
-   Learn how to expose the CLI over MCP in [MCP servers](/guide/cli/mcp).
