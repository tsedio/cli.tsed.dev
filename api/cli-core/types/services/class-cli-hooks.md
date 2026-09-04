---
url: /api/cli-core/types/services/class-cli-hooks.md
description: api documentation of CliHooks from @tsed/cli-core
---

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

## emit

```ts
emit(hookName: string, cmd: string, ...args: any[]): Promise<any>;
```
