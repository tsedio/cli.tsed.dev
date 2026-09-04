---
url: /api/cli-plugin-oxc/types/hooks/class-oxc-init-hook.md
description: api documentation of OxcInitHook from @tsed/cli-plugin-oxc
---

## Usage

```typescript
import { OxcInitHook } from "@tsed/cli-plugin-oxc/src/hooks/OxcInitHook";
```

> See [/packages/cli-plugin-oxc/src/hooks/OxcInitHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-oxc/src/hooks/OxcInitHook.ts#L0-L0).

## Overview

```ts
class OxcInitHook implements CliCommandHooks {
    $alterRenderFiles(files: string[], data: RenderDataContext): (string | {
        id: string;
        from: string;
    })[];
    $alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson;
    $alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task<any>[];
    $alterInitPostInstallTasks(tasks: Task[], data: InitCmdContext): Task[];
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
$alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson;
```

## $alterInitSubTasks

```ts
$alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task<any>[];
```

## $alterInitPostInstallTasks

```ts
$alterInitPostInstallTasks(tasks: Task[], data: InitCmdContext): Task[];
```
