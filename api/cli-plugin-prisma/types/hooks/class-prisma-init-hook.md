---
url: /api/cli-plugin-prisma/types/hooks/class-prisma-init-hook.md
description: api documentation of PrismaInitHook from @tsed/cli-plugin-prisma
---

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
