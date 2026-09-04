---
title: resolveMaybe from @tsed/cli-prompts
description: api documentation of resolveMaybe from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation resolveMaybe function
---
# resolveMaybe - @tsed/cli-prompts

## Usage

```typescript
import { resolveMaybe } from "@tsed/cli-prompts/src/utils/resolveMaybe";
```

> See [/packages/cli-prompts/src/utils/resolveMaybe.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/utils/resolveMaybe.ts#L0-L0).

## Overview

```ts
function resolveMaybe<T>(value: T | ((answers: Record<string, any>) => T | Promise<T>) | undefined, answers: Record<string, any>): Promise<T> | T;
```
