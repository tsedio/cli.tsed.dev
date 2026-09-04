---
url: /api/cli-prompts/types/interfaces/type-prompt-filter.md
description: api documentation of PromptFilter from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptFilter } from "@tsed/cli-prompts/src/interfaces/PromptQuestion";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
type PromptFilter = (input: any, answers: Record<string, any>) => MaybePromise<any>;
```

## Description

Filters the answer into a different representation before persistence.
