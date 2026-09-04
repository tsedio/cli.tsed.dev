---
title: CliPlugins from @tsed/cli-core
description: api documentation of CliPlugins from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CliPlugins class
---
# CliPlugins - @tsed/cli-core

## Usage

```typescript
import { CliPlugins } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliPlugins.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliPlugins.ts#L0-L0).

## Overview

```ts
class CliPlugins {
    name: string;
    readonly loadPlugins: typeof loadPlugins;
    
    searchPlugins(keyword?: string, options?: any): Promise<any>;
    addPluginsDependencies(ctx: any): Task[];
    protected getKeyword(keyword: string): string;
    protected cleanKeyword(keyword: string): string;
}
```

<!-- Members -->

## name

```ts
name: string;
```

## readonly loadPlugins

```ts
readonly loadPlugins: typeof loadPlugins;
```

## searchPlugins

```ts
searchPlugins(keyword?: string, options?: any): Promise<any>;
```

## addPluginsDependencies

```ts
addPluginsDependencies(ctx: any): Task[];
```

## protected getKeyword

```ts
protected getKeyword(keyword: string): string;
```

## protected cleanKeyword

```ts
protected cleanKeyword(keyword: string): string;
```
