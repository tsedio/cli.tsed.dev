---
title: CliPrisma from @tsed/cli-plugin-prisma
description: api documentation of CliPrisma from @tsed/cli-plugin-prisma
meta:
 - name: keywords
   description: api typescript node.js documentation CliPrisma class
---
# CliPrisma - @tsed/cli-plugin-prisma

## Usage

```typescript
import { CliPrisma } from "@tsed/cli-plugin-prisma";
```

> See [/packages/cli-plugin-prisma/src/services/CliPrisma.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-prisma/src/services/CliPrisma.ts#L0-L0).

## Overview

```ts
class CliPrisma {
    protected cliExeca: CliExeca;
    protected cliFs: CliFs;
    protected projectPackageJson: ProjectPackageJson;
    run(command: string, args?: string[], options?: any): import("execa").ExecaReturnBase<string>;
    init(): import("execa").ExecaReturnBase<string>;
    patchPrismaSchema(): Promise<void>;
}
```

<!-- Members -->

## protected cliExeca

```ts
protected cliExeca: CliExeca;
```

## protected cliFs

```ts
protected cliFs: CliFs;
```

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## run

```ts
run(command: string, args?: string[], options?: any): import("execa").ExecaReturnBase<string>;
```

## init

```ts
init(): import("execa").ExecaReturnBase<string>;
```

## patchPrismaSchema

```ts
patchPrismaSchema(): Promise<void>;
```
