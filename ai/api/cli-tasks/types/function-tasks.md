---
title: tasks from @tsed/cli-tasks
description: api documentation of tasks from @tsed/cli-tasks
meta:
 - name: keywords
   description: api typescript node.js documentation tasks function
---
# tasks - @tsed/cli-tasks

## Usage

```typescript
import { tasks } from "@tsed/cli-tasks";
```

> See [/packages/cli-tasks/src/tasks.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-tasks/src/tasks.ts#L0-L0).

## Overview

```ts
function tasks<T = any>(list: Task[], ctx: T & TasksOptions, parent?: TaskLogger): Promise<void>;
```
