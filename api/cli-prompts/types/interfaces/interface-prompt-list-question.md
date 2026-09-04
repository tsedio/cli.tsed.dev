---
url: /api/cli-prompts/types/interfaces/interface-prompt-list-question.md
description: api documentation of PromptListQuestion from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptListQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptListQuestion<Value = any> extends PromptBaseQuestion<Value>, Omit<SelectOptions<Value>, "message" | "options"> {
    type: "list";
    choices: string[] | PromptChoice<Value>[];
}
```

## Description

Single-select prompt with predefined choices.

## type

```ts
type: "list";
```

## choices

```ts
choices: string[] | PromptChoice<Value>[];
```

Available choices displayed to the user.
