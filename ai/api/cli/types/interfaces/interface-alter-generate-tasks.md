---
title: AlterGenerateTasks from @tsed/cli
description: api documentation of AlterGenerateTasks from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation AlterGenerateTasks interface
---
# AlterGenerateTasks - @tsed/cli

## Usage

```typescript
import { AlterGenerateTasks } from "@tsed/cli";
```

> See [/packages/cli/src/interfaces/AlterGenerateTasks.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/interfaces/AlterGenerateTasks.ts#L0-L0).

## Overview

```ts
interface AlterGenerateTasks {
    $alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[] | Promise<Task[]>;
}
```

<!-- Members -->

## $alterGenerateTasks

```ts
$alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[] | Promise<Task[]>;
```
