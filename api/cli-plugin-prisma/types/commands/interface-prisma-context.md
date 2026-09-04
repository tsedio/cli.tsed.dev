---
url: /api/cli-plugin-prisma/types/commands/interface-prisma-context.md
description: api documentation of PrismaContext from @tsed/cli-plugin-prisma
---

## Usage

```typescript
import { PrismaContext } from "@tsed/cli-plugin-prisma";
```

> See [/packages/cli-plugin-prisma/src/commands/PrismaCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-prisma/src/commands/PrismaCmd.ts#L0-L0).

## Overview

```ts
interface PrismaContext extends CommandData {
    command: string;
}
```

## command

```ts
command: string;
```
