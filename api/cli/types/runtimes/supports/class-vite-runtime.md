---
url: /api/cli/types/runtimes/supports/class-vite-runtime.md
description: api documentation of ViteRuntime from @tsed/cli
---

## Usage

```typescript
import { ViteRuntime } from "@tsed/cli";
```

> See [/packages/cli/src/runtimes/supports/ViteRuntime.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/runtimes/supports/ViteRuntime.ts#L0-L0).

## Overview

```ts
class ViteRuntime extends BaseRuntime {
    readonly name = "vite";
    readonly cmd = "node";
    readonly order: number;
    files(): string[];
    compile(): string;
    startDev(): string;
    startProd(args: string): string;
    devDependencies(): Record<string, any>;
}
```

## readonly name

```ts
readonly name = "vite";
```

## readonly cmd

```ts
readonly cmd = "node";
```

## readonly order

```ts
readonly order: number;
```

## files

```ts
files(): string[];
```

## compile

```ts
compile(): string;
```

## startDev

```ts
startDev(): string;
```

## startProd

```ts
startProd(args: string): string;
```

## devDependencies

```ts
devDependencies(): Record<string, any>;
```
