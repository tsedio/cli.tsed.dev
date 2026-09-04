---
title: NormalizedChoice from @tsed/cli-prompts
description: api documentation of NormalizedChoice from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation NormalizedChoice type
---
# NormalizedChoice - @tsed/cli-prompts

## Usage

```typescript
import { NormalizedChoice } from "@tsed/cli-prompts/src/utils/normalizeChoices";
```

> See [/packages/cli-prompts/src/utils/normalizeChoices.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/utils/normalizeChoices.ts#L0-L0).

## Overview

```ts
type NormalizedChoice<Value = any> = Option<Value> & {
    checked?: boolean;
};
```

<!-- Members -->

## checked

```ts
checked?: boolean;
```
