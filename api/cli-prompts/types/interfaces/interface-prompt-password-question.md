---
url: /api/cli-prompts/types/interfaces/interface-prompt-password-question.md
description: api documentation of PromptPasswordQuestion from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptPasswordQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptPasswordQuestion extends PromptBaseQuestion<string>, Omit<PasswordOptions, "message"> {
    type: "password";
}
```

## Description

Hidden text prompt (e.g., passwords or tokens).

## type

```ts
type: "password";
```
