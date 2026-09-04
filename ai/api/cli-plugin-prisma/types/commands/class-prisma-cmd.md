---
title: PrismaCmd from @tsed/cli-plugin-prisma
description: api documentation of PrismaCmd from @tsed/cli-plugin-prisma
meta:
 - name: keywords
   description: api typescript node.js documentation PrismaCmd class
---
# PrismaCmd - @tsed/cli-plugin-prisma

## Usage

```typescript
import { PrismaCmd } from "@tsed/cli-plugin-prisma";
```

> See [/packages/cli-plugin-prisma/src/commands/PrismaCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-prisma/src/commands/PrismaCmd.ts#L0-L0).

## Overview

```ts
class PrismaCmd implements CommandProvider {
    protected cli: CliPrisma;
    $exec(ctx: PrismaContext): {
        title: string;
        task: () => import("execa").ExecaReturnBase<string>;
    }[];
}
```

<!-- Members -->

## protected cli

```ts
protected cli: CliPrisma;
```

## $exec

```ts
$exec(ctx: PrismaContext): {
     title: string;
     task: () => import("execa").ExecaReturnBase<string>;
 }[];
```
