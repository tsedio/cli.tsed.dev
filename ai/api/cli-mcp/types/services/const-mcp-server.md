---
title: MCP_SERVER from @tsed/cli-mcp
description: api documentation of MCP_SERVER from @tsed/cli-mcp
meta:
 - name: keywords
   description: api typescript node.js documentation MCP_SERVER const
---
# MCP_SERVER - @tsed/cli-mcp

## Usage

```typescript
import { MCP_SERVER } from "@tsed/cli-mcp";
```

> See [/packages/cli-mcp/src/services/McpServerFactory.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-mcp/src/services/McpServerFactory.ts#L0-L0).

## Overview

```ts
const MCP_SERVER: import("@tsed/di").FactoryTokenProvider<{
    server: McpServer;
    connect(mode?: "streamable-http" | "stdio" | undefined): Promise<void>;
}>;
export type MCP_SERVER = typeof MCP_SERVER;
```

<!-- Members -->

## server

```ts
server: McpServer;
```

## connect

```ts
connect(mode?: "streamable-http" | "stdio" | undefined): Promise<void>;
```
