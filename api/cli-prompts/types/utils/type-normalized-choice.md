---
url: /api/cli-prompts/types/utils/type-normalized-choice.md
description: api documentation of NormalizedChoice from @tsed/cli-prompts
---

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

## checked

```ts
checked?: boolean;
```
