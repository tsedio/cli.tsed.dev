---
url: /api/cli/types/commands/mcp/utils/function-wait-for-shutdown.md
description: api documentation of waitForShutdown from @tsed/cli
---

## Usage

```typescript
import { waitForShutdown } from "@tsed/cli/src/commands/mcp/utils/waitForShutdown";
```

> See [/packages/cli/src/commands/mcp/utils/waitForShutdown.ts](https://github.com/tsedio/tsed-cli/blob/v7.8.1/packages/cli/src/commands/mcp/utils/waitForShutdown.ts#L0-L0).

## Overview

```ts
function waitForShutdown(mode: "stdio" | "streamable-http", stdin?: NodeJS.ReadableStream): Promise<void>;
```

## Description

Keep the `mcp` command pending while the MCP server is running.

The CLI destroys the injector as soon as a command handler resolves. An MCP server keeps answering requests after
the connection is established, so the handler must stay pending or every later tool call runs on an empty injector.

* `stdio`: resolves when the client closes stdin.
* `streamable-http`: never resolves, the HTTP server lives until the process is stopped.
