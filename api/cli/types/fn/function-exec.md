---
url: /api/cli/types/fn/function-exec.md
description: api documentation of exec from @tsed/cli
---

## Usage

```typescript
import { exec } from "@tsed/cli";
```

> See [/packages/cli/src/fn/exec.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/fn/exec.ts#L0-L0).

## Overview

```ts
function exec(command: string, data: any): Promise<import("@tsed/cli-core").Task<any>[]>;
```
