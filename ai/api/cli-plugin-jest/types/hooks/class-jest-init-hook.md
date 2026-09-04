---
title: JestInitHook from @tsed/cli-plugin-jest
description: api documentation of JestInitHook from @tsed/cli-plugin-jest
meta:
 - name: keywords
   description: api typescript node.js documentation JestInitHook class
---
# JestInitHook - @tsed/cli-plugin-jest

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

<!-- Members -->

## $alterInitSubTasks

```ts
$alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task<any>[];
```
