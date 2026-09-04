---
url: /api/cli-tasks/types/function-concat.md
description: api documentation of concat from @tsed/cli-tasks
---

## Usage

```typescript
import { concat } from "@tsed/cli-tasks";
```

> See [/packages/cli-tasks/src/tasks.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-tasks/src/tasks.ts#L0-L0).

## Overview

```ts
function concat(...args: (Task[] | void | undefined)[]): Promise<Task<any>[]>;
```
