---
url: /api/cli-prompts/types/interfaces/type-prompt-choice-input.md
description: api documentation of PromptChoiceInput from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptChoiceInput } from "@tsed/cli-prompts/src/interfaces/PromptQuestion";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
type PromptChoiceInput<Value = any> = PromptChoice<Value> | Value;
```

## Description

Choice definition accepted by prompts. A plain value will be coerced to a `PromptChoice`.
