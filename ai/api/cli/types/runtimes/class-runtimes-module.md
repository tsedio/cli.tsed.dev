---
title: RuntimesModule from @tsed/cli
description: api documentation of RuntimesModule from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation RuntimesModule class
---
# RuntimesModule - @tsed/cli

## Usage

```typescript
import { RuntimesModule } from "@tsed/cli";
```

> See [/packages/cli/src/runtimes/RuntimesModule.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/runtimes/RuntimesModule.ts#L0-L0).

## Overview

```ts
class RuntimesModule {
    protected projectPackageJson: ProjectPackageJson;
    constructor();
    init(ctx: RuntimeInitOptions): void;
    list(): string[];
    get(name?: string): BaseRuntime;
    scripts(ctx: RuntimeInitOptions): {
        build: string;
        barrels: string;
        start: string;
        "start:prod": string;
    };
}
```

<!-- Members -->

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## init

```ts
init(ctx: RuntimeInitOptions): void;
```

## list

```ts
list(): string[];
```

## get

```ts
get(name?: string): BaseRuntime;
```

## scripts

```ts
scripts(ctx: RuntimeInitOptions): {
     build: string;
     barrels: string;
     start: string;
     "start:prod": string;
 };
```
