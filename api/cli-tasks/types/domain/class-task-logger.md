---
url: /api/cli-tasks/types/domain/class-task-logger.md
description: api documentation of TaskLogger from @tsed/cli-tasks
---

## Usage

```typescript
import { TaskLogger } from "@tsed/cli-tasks";
```

> See [/packages/cli-tasks/src/domain/TaskLogger.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-tasks/src/domain/TaskLogger.ts#L0-L0).

## Overview

```ts
class TaskLogger {
    readonly type: TaskLoggerOptions["type"];
    max?: number;
    constructor(opts: TaskLoggerOptions);
    get parent(): TaskLogger | undefined;
    get isReady(): boolean;
    get title(): string;
    set title(title: string);
    set output(message: string);
    static from(opts: TaskLoggerOptions): TaskLogger;
    log(message: string): void;
    message(message: string): void;
    advance(): this;
    start(): this;
    done(): this;
    error(message: string | Error): this;
    info(message: string): this;
    warn(message: string): this;
    skip(): this;
    report(message: string): void;
    protected isChildProgress(): boolean;
    protected create(opts: TaskLoggerOptions): any;
    
}
```

## readonly type

```ts
readonly type: TaskLoggerOptions["type"];
```

## max

```ts
max?: number;
```

## get parent

```ts
get parent(): TaskLogger | undefined;
```

## get isReady

```ts
get isReady(): boolean;
```

## get title

```ts
get title(): string;
```

## set title

```ts
set title(title: string);
```

## set output

```ts
set output(message: string);
```

## static from

```ts
static from(opts: TaskLoggerOptions): TaskLogger;
```

## log

```ts
log(message: string): void;
```

## message

```ts
message(message: string): void;
```

## advance

```ts
advance(): this;
```

## start

```ts
start(): this;
```

## done

```ts
done(): this;
```

## error

```ts
error(message: string | Error): this;
```

## info

```ts
info(message: string): this;
```

## warn

```ts
warn(message: string): this;
```

## skip

```ts
skip(): this;
```

## report

```ts
report(message: string): void;
```

## protected isChildProgress

```ts
protected isChildProgress(): boolean;
```

## protected create

```ts
protected create(opts: TaskLoggerOptions): any;
```
