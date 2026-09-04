---
title: AlterInitSubTasks from @tsed/cli
description: api documentation of AlterInitSubTasks from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation AlterInitSubTasks interface
---
# AlterInitSubTasks - @tsed/cli

## Usage

```typescript
import { AlterInitSubTasks } from "@tsed/cli";
```

> See [/packages/cli/src/interfaces/AlterInitSubTasks.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/interfaces/AlterInitSubTasks.ts#L0-L0).

## Overview

```ts
interface AlterInitSubTasks {
    $alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
}
```

<!-- Members -->

## $alterInitSubTasks

```ts
$alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
```
