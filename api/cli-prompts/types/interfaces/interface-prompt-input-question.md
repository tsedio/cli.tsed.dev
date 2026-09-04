---
url: /api/cli-prompts/types/interfaces/interface-prompt-input-question.md
description: api documentation of PromptInputQuestion from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptInputQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptInputQuestion extends PromptBaseQuestion<string>, Omit<TextOptions, "message"> {
    type: "input";
}
```

## Description

Plain text prompt.

## type

```ts
type: "input";
```
