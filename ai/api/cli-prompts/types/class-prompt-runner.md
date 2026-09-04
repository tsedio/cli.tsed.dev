---
title: PromptRunner from @tsed/cli-prompts
description: api documentation of PromptRunner from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation PromptRunner class
---
# PromptRunner - @tsed/cli-prompts

## Usage

```typescript
import { PromptRunner } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/PromptRunner.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/PromptRunner.ts#L0-L0).

## Overview

```ts
class PromptRunner {
    run(questions: PromptQuestion[] | undefined, initialAnswers?: Record<string, any>): Promise<Record<string, any>>;
    protected prompt(question: NormalizedPromptQuestion, answers: Record<string, unknown>): Promise<any>;
}
```

<!-- Members -->

## run

```ts
run(questions: PromptQuestion[] | undefined, initialAnswers?: Record<string, any>): Promise<Record<string, any>>;
```

## protected prompt

```ts
protected prompt(question: NormalizedPromptQuestion, answers: Record<string, unknown>): Promise<any>;
```
