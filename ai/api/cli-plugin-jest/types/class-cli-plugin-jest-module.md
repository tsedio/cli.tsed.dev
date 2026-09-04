---
title: CliPluginJestModule from @tsed/cli-plugin-jest
description: api documentation of CliPluginJestModule from @tsed/cli-plugin-jest
meta:
 - name: keywords
   description: api typescript node.js documentation CliPluginJestModule class
---
# CliPluginJestModule - @tsed/cli-plugin-jest

## Usage

```typescript
import { CliPluginJestModule } from "@tsed/cli-plugin-jest/src/CliPluginJestModule";
```

> See [/packages/cli-plugin-jest/src/CliPluginJestModule.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-jest/src/CliPluginJestModule.ts#L0-L0).

## Overview

```ts
class CliPluginJestModule {
    protected runtimes: RuntimesModule;
    protected packageJson: ProjectPackageJson;
    $onAddPlugin(plugin: string): void;
    addScripts(): void;
    addDevDependencies(): void;
}
```

<!-- Members -->

## protected runtimes

```ts
protected runtimes: RuntimesModule;
```

## protected packageJson

```ts
protected packageJson: ProjectPackageJson;
```

## $onAddPlugin

```ts
$onAddPlugin(plugin: string): void;
```

## addScripts

```ts
addScripts(): void;
```

## addDevDependencies

```ts
addDevDependencies(): void;
```
