---
url: /api/cli/types/interfaces/interface-cli-command-hooks.md
description: api documentation of CliCommandHooks from @tsed/cli
---

## Usage

```typescript
import { CliCommandHooks } from "@tsed/cli";
```

> See [/packages/cli/src/interfaces/CliCommandHooks.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/interfaces/CliCommandHooks.ts#L0-L0).

## Overview

```ts
interface CliCommandHooks extends Partial<AlterInitSubTasks & AlterPackageJson & AlterRenderFiles & AlterProjectFiles & AlterGenerateTasks> {
    $alterInitPostInstallTasks?(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
    $alterGeneratePostInstallTasks?(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
}
```

## $alterInitPostInstallTasks

```ts
$alterInitPostInstallTasks?(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
```

## $alterGeneratePostInstallTasks

```ts
$alterGeneratePostInstallTasks?(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
```
