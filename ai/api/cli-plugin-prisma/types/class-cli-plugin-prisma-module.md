---
title: CliPluginPrismaModule from @tsed/cli-plugin-prisma
description: api documentation of CliPluginPrismaModule from @tsed/cli-plugin-prisma
meta:
 - name: keywords
   description: api typescript node.js documentation CliPluginPrismaModule class
---
# CliPluginPrismaModule - @tsed/cli-plugin-prisma

## Usage

```typescript
import { CliPluginPrismaModule } from "@tsed/cli-plugin-prisma/src/CliPluginPrismaModule";
```

> See [/packages/cli-plugin-prisma/src/CliPluginPrismaModule.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-prisma/src/CliPluginPrismaModule.ts#L0-L0).

## Overview

```ts
class CliPluginPrismaModule {
    protected packageJson: ProjectPackageJson;
    $onAddPlugin(plugin: string, ctx: InitCmdContext): void;
    addScripts(): void;
    addDependencies(ctx: InitCmdContext): void;
    addDevDependencies(ctx: InitCmdContext): void;
}
```

<!-- Members -->

## protected packageJson

```ts
protected packageJson: ProjectPackageJson;
```

## $onAddPlugin

```ts
$onAddPlugin(plugin: string, ctx: InitCmdContext): void;
```

## addScripts

```ts
addScripts(): void;
```

## addDependencies

```ts
addDependencies(ctx: InitCmdContext): void;
```

## addDevDependencies

```ts
addDevDependencies(ctx: InitCmdContext): void;
```
