---
title: CliHooks from @tsed/cli-core
description: api documentation of CliHooks from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CliHooks class
---
# CliHooks - @tsed/cli-core

## Usage

```typescript
import { CliHooks } from "@tsed/cli-core/src/services/CliHooks";
```

> See [/packages/cli-core/src/services/CliHooks.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliHooks.ts#L0-L0).

## Overview

```ts
class CliHooks {
    emit(hookName: string, cmd: string, ...args: any[]): Promise<any>;
}
```

<!-- Members -->

## emit

```ts
emit(hookName: string, cmd: string, ...args: any[]): Promise<any>;
```
