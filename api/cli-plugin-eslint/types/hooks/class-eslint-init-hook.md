---
url: /api/cli-plugin-eslint/types/hooks/class-eslint-init-hook.md
description: api documentation of EslintInitHook from @tsed/cli-plugin-eslint
---

## Usage

```typescript
import { EslintInitHook } from "@tsed/cli-plugin-eslint/src/hooks/EslintInitHook";
```

> See [/packages/cli-plugin-eslint/src/hooks/EslintInitHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-eslint/src/hooks/EslintInitHook.ts#L0-L0).

## Overview

```ts
class EslintInitHook implements CliCommandHooks {
    $alterRenderFiles(files: string[], data: RenderDataContext): (string | {
        id: string;
        from: string;
    })[];
    $alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson | Promise<ProjectPackageJson>;
    $alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task<any>[];
    $alterInitPostInstallTasks(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
}
```

## $alterRenderFiles

```ts
$alterRenderFiles(files: string[], data: RenderDataContext): (string | {
     id: string;
     from: string;
 })[];
```

## $alterPackageJson

```ts
$alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson | Promise<ProjectPackageJson>;
```

## $alterInitSubTasks

```ts
$alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task<any>[];
```

## $alterInitPostInstallTasks

```ts
$alterInitPostInstallTasks(tasks: Task[], data: InitCmdContext): Task[] | Promise<Task[]>;
```
