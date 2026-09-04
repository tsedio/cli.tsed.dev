---
url: /api/cli-prompts/types/interfaces/type-prompt-transformer.md
description: api documentation of PromptTransformer from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptTransformer } from "@tsed/cli-prompts/src/interfaces/PromptQuestion";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
type PromptTransformer = (input: any, answers: Record<string, any>, flags?: {
    isFinal?: boolean;
}) => any;
```

## Description

Transforms user input before it becomes part of the command context.

## isFinal

```ts
isFinal?: boolean;
```
