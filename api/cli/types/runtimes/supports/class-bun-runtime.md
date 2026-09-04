---
url: /api/cli/types/runtimes/supports/class-bun-runtime.md
description: api documentation of BunRuntime from @tsed/cli
---

## Usage

```typescript
import { BunRuntime } from "@tsed/cli";
```

> See [/packages/cli/src/runtimes/supports/BunRuntime.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/runtimes/supports/BunRuntime.ts#L0-L0).

## Overview

```ts
class BunRuntime extends BaseRuntime {
    readonly name = "bun";
    readonly cmd = "bun";
    readonly order: number;
    compile(src: string, out: string): string;
    startDev(main: string): string;
    startProd(args: string): string;
    dependencies(): Record<string, any>;
}
```

## readonly name

```ts
readonly name = "bun";
```

## readonly cmd

```ts
readonly cmd = "bun";
```

## readonly order

```ts
readonly order: number;
```

## compile

```ts
compile(src: string, out: string): string;
```

## startDev

```ts
startDev(main: string): string;
```

## startProd

```ts
startProd(args: string): string;
```

## dependencies

```ts
dependencies(): Record<string, any>;
```
