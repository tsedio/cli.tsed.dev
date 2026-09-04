---
title: TaskLoggerOptions from @tsed/cli-tasks
description: api documentation of TaskLoggerOptions from @tsed/cli-tasks
meta:
 - name: keywords
   description: api typescript node.js documentation TaskLoggerOptions interface
---
# TaskLoggerOptions - @tsed/cli-tasks

## Usage

```typescript
import { TaskLoggerOptions } from "@tsed/cli-tasks";
```

> See [/packages/cli-tasks/src/domain/TaskLogger.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-tasks/src/domain/TaskLogger.ts#L0-L0).

## Overview

```ts
interface TaskLoggerOptions {
    title: string;
    index: number;
    type?: "group" | "taskLog" | "log" | "spinner" | "progress";
    parent?: TaskLogger;
    renderMode?: "default" | "raw";
}
```

<!-- Members -->

## title

```ts
title: string;
```

## index

```ts
index: number;
```

## type

```ts
type?: "group" | "taskLog" | "log" | "spinner" | "progress";
```

## parent

```ts
parent?: TaskLogger;
```

## renderMode

```ts
renderMode?: "default" | "raw";
```
