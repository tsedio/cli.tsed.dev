---
title: RunCmdContext from @tsed/cli
description: api documentation of RunCmdContext from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation RunCmdContext interface
---
# RunCmdContext - @tsed/cli

## Usage

```typescript
import { RunCmdContext } from "@tsed/cli";
```

> See [/packages/cli/src/commands/run/RunCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/run/RunCmd.ts#L0-L0).

## Overview

```ts
interface RunCmdContext {
    production: boolean;
    command: string;
    rawArgs: string[];
}
```

<!-- Members -->

## production

```ts
production: boolean;
```

## command

```ts
command: string;
```

## rawArgs

```ts
rawArgs: string[];
```
