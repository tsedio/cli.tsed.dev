---
url: /api/cli-tasks/types/interfaces/interface-task.md
description: api documentation of Task from @tsed/cli-tasks
---

## Usage

```typescript
import { Task } from "@tsed/cli-tasks";
```

> See [/packages/cli-tasks/src/interfaces/Task.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-tasks/src/interfaces/Task.ts#L0-L0).

## Overview

```ts
interface Task<Ctx = any> {
    title: string;
    task: (ctx: Ctx, operation: TaskLogger) => MaybePromise<Task[] | unknown> | Observable<unknown>;
    skip?: boolean | string | ((ctx: Ctx) => TaskPredicate);
    enabled?: boolean | ((ctx: Ctx) => MaybePromise<boolean>);
    type?: TaskLoggerOptions["type"];
}
```

## title

```ts
title: string;
```

## task:

```ts
task: (ctx: Ctx, operation: TaskLogger) => MaybePromise<Task[] | unknown> | Observable<unknown>;
```

## skip: boolean | string |

```ts
skip?: boolean | string | ((ctx: Ctx) => TaskPredicate);
```

## enabled: boolean |

```ts
enabled?: boolean | ((ctx: Ctx) => MaybePromise<boolean>);
```

## type

```ts
type?: TaskLoggerOptions["type"];
```
