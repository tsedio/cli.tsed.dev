---
url: /api/cli-plugin-jest/types/hooks/class-jest-init-hook.md
description: api documentation of JestInitHook from @tsed/cli-plugin-jest
---

## Usage

```typescript
import { JestInitHook } from "@tsed/cli-plugin-jest/src/hooks/JestInitHook";
```

> See [/packages/cli-plugin-jest/src/hooks/JestInitHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-jest/src/hooks/JestInitHook.ts#L0-L0).

## Overview

```ts
class JestInitHook implements AlterInitSubTasks {
    $alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task<any>[];
}
```

## $alterInitSubTasks

```ts
$alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task<any>[];
```
