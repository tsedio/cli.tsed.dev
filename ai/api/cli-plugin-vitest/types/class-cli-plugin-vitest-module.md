---
title: CliPluginVitestModule from @tsed/cli-plugin-vitest
description: api documentation of CliPluginVitestModule from @tsed/cli-plugin-vitest
meta:
 - name: keywords
   description: api typescript node.js documentation CliPluginVitestModule class
---
# CliPluginVitestModule - @tsed/cli-plugin-vitest

## Usage

```typescript
import { CliPluginVitestModule } from "@tsed/cli-plugin-vitest/src/CliPluginVitestModule";
```

> See [/packages/cli-plugin-vitest/src/CliPluginVitestModule.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-vitest/src/CliPluginVitestModule.ts#L0-L0).

## Overview

```ts
class CliPluginVitestModule implements AlterInitSubTasks, AlterPackageJson, AlterGenerateTasks {
    $alterPackageJson(packageJson: ProjectPackageJson, data: InitCmdContext): ProjectPackageJson;
    $alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task<any>[];
    $alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[];
}
```

<!-- Members -->

## $alterPackageJson

```ts
$alterPackageJson(packageJson: ProjectPackageJson, data: InitCmdContext): ProjectPackageJson;
```

## $alterInitSubTasks

```ts
$alterInitSubTasks(tasks: Task[], data: InitCmdContext): Task<any>[];
```

## $alterGenerateTasks

```ts
$alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[];
```
