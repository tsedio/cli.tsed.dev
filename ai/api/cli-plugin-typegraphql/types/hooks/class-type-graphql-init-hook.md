---
title: TypeGraphqlInitHook from @tsed/cli-plugin-typegraphql
description: api documentation of TypeGraphqlInitHook from @tsed/cli-plugin-typegraphql
meta:
 - name: keywords
   description: api typescript node.js documentation TypeGraphqlInitHook class
---
# TypeGraphqlInitHook - @tsed/cli-plugin-typegraphql

## Usage

```typescript
import { TypeGraphqlInitHook } from "@tsed/cli-plugin-typegraphql/src/hooks/TypeGraphqlInitHook";
```

> See [/packages/cli-plugin-typegraphql/src/hooks/TypeGraphqlInitHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-typegraphql/src/hooks/TypeGraphqlInitHook.ts#L0-L0).

## Overview

```ts
class TypeGraphqlInitHook implements CliCommandHooks {
    $alterInitSubTasks(tasks: Task[], data: InitCmdContext): Promise<Task<any>[]>;
    $alterProjectFiles(project: ProjectClient, data: RenderDataContext): ProjectClient;
}
```

<!-- Members -->

## $alterInitSubTasks

```ts
$alterInitSubTasks(tasks: Task[], data: InitCmdContext): Promise<Task<any>[]>;
```

## $alterProjectFiles

```ts
$alterProjectFiles(project: ProjectClient, data: RenderDataContext): ProjectClient;
```
