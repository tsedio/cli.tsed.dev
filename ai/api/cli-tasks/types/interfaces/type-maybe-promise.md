---
title: MaybePromise from @tsed/cli-tasks
description: api documentation of MaybePromise from @tsed/cli-tasks
meta:
 - name: keywords
   description: api typescript node.js documentation MaybePromise type
---
# MaybePromise - @tsed/cli-tasks

## Usage

```typescript
import { MaybePromise } from "@tsed/cli-tasks/src/interfaces/Task";
```

> See [/packages/cli-tasks/src/interfaces/Task.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-tasks/src/interfaces/Task.ts#L0-L0).

## Overview

```ts
type MaybePromise<T> = Promise<T> | T;
```
