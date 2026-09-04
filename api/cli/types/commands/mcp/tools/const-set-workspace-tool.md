---
url: /api/cli/types/commands/mcp/tools/const-set-workspace-tool.md
description: api documentation of setWorkspaceTool from @tsed/cli
---

## Usage

```typescript
import { setWorkspaceTool } from "@tsed/cli/src/commands/mcp/tools/setWorkspaceTool";
```

> See [/packages/cli/src/commands/mcp/tools/setWorkspaceTool.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/mcp/tools/setWorkspaceTool.ts#L0-L0).

## Overview

```ts
const setWorkspaceTool: any;
```

## Description

Simplified behavior per MVP:

* If the provided cwd exists: set it, resolve the nearest package.json root via ProjectPackageJson, return that resolved cwd.
* If the provided cwd does not exist: do not create anything; return an error suggesting to confirm creation and run init-project.
