---
title: BaseRuntime from @tsed/cli
description: api documentation of BaseRuntime from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation BaseRuntime class
---
# BaseRuntime - @tsed/cli

## Usage

```typescript
import { BaseRuntime } from "@tsed/cli";
```

> See [/packages/cli/src/runtimes/supports/BaseRuntime.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/runtimes/supports/BaseRuntime.ts#L0-L0).

## Overview

```ts
abstract class BaseRuntime {
    abstract readonly name: string;
    abstract readonly cmd: string;
    readonly order: number;
    protected packageManagers: PackageManagersModule;
    protected cliExeca: CliExeca;
    get packageManager(): import("@tsed/cli-core").BaseManager;
    isCompiled(): boolean;
    files(): string[];
    has(): boolean;
    run(args: string): string;
    abstract compile(src: string, out: string): string;
    abstract startDev(main: string): string;
    abstract startProd(args: string): string;
    dependencies(): Record<string, any>;
    devDependencies(): Record<string, any>;
}
```

<!-- Members -->

## abstract readonly name

```ts
abstract readonly name: string;
```

## abstract readonly cmd

```ts
abstract readonly cmd: string;
```

## readonly order

```ts
readonly order: number;
```

## protected packageManagers

```ts
protected packageManagers: PackageManagersModule;
```

## protected cliExeca

```ts
protected cliExeca: CliExeca;
```

## get packageManager

```ts
get packageManager(): import("@tsed/cli-core").BaseManager;
```

## isCompiled

```ts
isCompiled(): boolean;
```

## files

```ts
files(): string[];
```

## has

```ts
has(): boolean;
```

## run

```ts
run(args: string): string;
```

## abstract compile

```ts
abstract compile(src: string, out: string): string;
```

Returns the compile command

## abstract startDev

```ts
abstract startDev(main: string): string;
```

Returns the start dev command

## abstract startProd

```ts
abstract startProd(args: string): string;
```

Returns the start production command

## dependencies

```ts
dependencies(): Record<string, any>;
```

## devDependencies

```ts
devDependencies(): Record<string, any>;
```
