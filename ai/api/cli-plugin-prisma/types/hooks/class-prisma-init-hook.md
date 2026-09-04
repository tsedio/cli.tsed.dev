---
title: PrismaInitHook from @tsed/cli-plugin-prisma
description: api documentation of PrismaInitHook from @tsed/cli-plugin-prisma
meta:
 - name: keywords
   description: api typescript node.js documentation PrismaInitHook class
---
# PrismaInitHook - @tsed/cli-plugin-prisma

## Usage

```typescript
import { PrismaInitHook } from "@tsed/cli-plugin-prisma";
```

> See [/packages/cli-plugin-prisma/src/hooks/PrismaInitHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-prisma/src/hooks/PrismaInitHook.ts#L0-L0).

## Overview

```ts
class PrismaInitHook implements AlterInitSubTasks {
    protected cliPrisma: CliPrisma;
    protected packageJson: ProjectPackageJson;
    protected packageManagers: PackageManagersModule;
    $alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
    $onFinish(): Promise<unknown>;
}
```

<!-- Members -->

## protected cliPrisma

```ts
protected cliPrisma: CliPrisma;
```

## protected packageJson

```ts
protected packageJson: ProjectPackageJson;
```

## protected packageManagers

```ts
protected packageManagers: PackageManagersModule;
```

## $alterInitSubTasks

```ts
$alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
```

## $onFinish

```ts
$onFinish(): Promise<unknown>;
```
