---
title: NodeRuntime from @tsed/cli
description: api documentation of NodeRuntime from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation NodeRuntime class
---
# NodeRuntime - @tsed/cli

## Usage

```typescript
import { NodeRuntime } from "@tsed/cli";
```

> See [/packages/cli/src/runtimes/supports/NodeRuntime.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/runtimes/supports/NodeRuntime.ts#L0-L0).

## Overview

```ts
class NodeRuntime extends BaseRuntime {
    readonly name: string;
    readonly cmd: string;
    readonly order: number;
    files(): string[];
    startDev(main: string): string;
    startProd(main: string): string;
    compile(src: string, out: string): string;
    dependencies(): Record<string, any>;
    devDependencies(): Record<string, any>;
}
```

<!-- Members -->

## readonly name

```ts
readonly name: string;
```

## readonly cmd

```ts
readonly cmd: string;
```

## readonly order

```ts
readonly order: number;
```

## files

```ts
files(): string[];
```

## startDev

```ts
startDev(main: string): string;
```

## startProd

```ts
startProd(main: string): string;
```

## compile

```ts
compile(src: string, out: string): string;
```

## dependencies

```ts
dependencies(): Record<string, any>;
```

## devDependencies

```ts
devDependencies(): Record<string, any>;
```
