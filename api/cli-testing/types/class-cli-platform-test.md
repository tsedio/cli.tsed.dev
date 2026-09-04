---
url: /api/cli-testing/types/class-cli-platform-test.md
description: api documentation of CliPlatformTest from @tsed/cli-testing
---

## Usage

```typescript
import { CliPlatformTest } from "@tsed/cli-testing";
```

> See [/packages/cli-testing/src/CliPlatformTest.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-testing/src/CliPlatformTest.ts#L0-L0).

## Overview

```ts
class CliPlatformTest extends DITest {
    static reset(): Promise<void>;
    static bootstrap(options?: Partial<TsED.Configuration>): Promise<void>;
    static initProject(options?: any): Promise<void>;
    static create(options?: Partial<TsED.Configuration>): Promise<void>;
    static createInjector(options?: Partial<TsED.Configuration>): InjectorService;
    static setPackageJson(pkg: any): void;
    static exec(cmdName: string, initialData: any): Promise<void>;
}
```

## static reset

```ts
static reset(): Promise<void>;
```

## static bootstrap

```ts
static bootstrap(options?: Partial<TsED.Configuration>): Promise<void>;
```

## static initProject

```ts
static initProject(options?: any): Promise<void>;
```

## static create

```ts
static create(options?: Partial<TsED.Configuration>): Promise<void>;
```

## static createInjector

```ts
static createInjector(options?: Partial<TsED.Configuration>): InjectorService;
```

Create a new injector with the right default services

## static setPackageJson

```ts
static setPackageJson(pkg: any): void;
```

## static exec

```ts
static exec(cmdName: string, initialData: any): Promise<void>;
```

Invoke command with a new context without running prompts
