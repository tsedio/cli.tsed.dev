---
title: TypeORMInitHook from @tsed/cli-plugin-typeorm
description: api documentation of TypeORMInitHook from @tsed/cli-plugin-typeorm
meta:
 - name: keywords
   description: api typescript node.js documentation TypeORMInitHook class
---
# TypeORMInitHook - @tsed/cli-plugin-typeorm

## Usage

```typescript
import { TypeORMInitHook } from "@tsed/cli-plugin-typeorm";
```

> See [/packages/cli-plugin-typeorm/src/hooks/TypeORMInitHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-typeorm/src/hooks/TypeORMInitHook.ts#L0-L0).

## Overview

```ts
class TypeORMInitHook implements CliCommandHooks {
    protected cliService: CliService;
    $alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson;
    $alterInitSubTasks(tasks: Task[], data: RenderDataContext): Promise<Task<any>[]>;
}
```

<!-- Members -->

## protected cliService

```ts
protected cliService: CliService;
```

## $alterPackageJson

```ts
$alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson;
```

## $alterInitSubTasks

```ts
$alterInitSubTasks(tasks: Task[], data: RenderDataContext): Promise<Task<any>[]>;
```
