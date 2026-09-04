---
url: /api/cli-plugin-prisma/types/commands/class-prisma-cmd.md
description: api documentation of PrismaCmd from @tsed/cli-plugin-prisma
---

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
