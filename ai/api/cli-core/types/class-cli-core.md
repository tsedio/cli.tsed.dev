---
title: CliCore from @tsed/cli-core
description: api documentation of CliCore from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CliCore class
---
# CliCore - @tsed/cli-core

## Usage

```typescript
import { CliCore } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/CliCore.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/CliCore.ts#L0-L0).

## Overview

```ts
class CliCore {
    protected constructor(settings: Partial<TsED.Configuration>);
    static checkPrecondition(settings: any): void;
    static checkPackage(pkg: any): void;
    static checkNodeVersion(wanted: string, id: string): typeof CliCore;
    static bootstrap(settings: Partial<TsED.Configuration>): Promise<CliCore>;
    static updateNotifier(pkg: any): Promise<typeof CliCore>;
    protected static getProjectRoot(argv: string[]): string;
    bootstrap(): Promise<this>;
}
```

<!-- Members -->

## static checkPrecondition

```ts
static checkPrecondition(settings: any): void;
```

## static checkPackage

```ts
static checkPackage(pkg: any): void;
```

## static checkNodeVersion

```ts
static checkNodeVersion(wanted: string, id: string): typeof CliCore;
```

## static bootstrap

```ts
static bootstrap(settings: Partial<TsED.Configuration>): Promise<CliCore>;
```

## static updateNotifier

```ts
static updateNotifier(pkg: any): Promise<typeof CliCore>;
```

## protected static getProjectRoot

```ts
protected static getProjectRoot(argv: string[]): string;
```

## bootstrap

```ts
bootstrap(): Promise<this>;
```
