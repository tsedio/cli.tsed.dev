---
url: /api/cli/types/runtimes/supports/class-bun-vite-runtime.md
description: api documentation of BunViteRuntime from @tsed/cli
---

## Usage

```typescript
import { BunViteRuntime } from "@tsed/cli";
```

> See [/packages/cli/src/runtimes/supports/BunViteRuntime.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/runtimes/supports/BunViteRuntime.ts#L0-L0).

## Overview

```ts
class BunViteRuntime extends BaseRuntime {
    readonly name = "bun-vite";
    readonly cmd = "bun";
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
readonly name = "bun-vite";
```

## readonly cmd

```ts
readonly cmd = "bun";
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
