---
url: /api/cli-prompts/types/interfaces/interface-prompt-confirm-question.md
description: api documentation of PromptConfirmQuestion from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptConfirmQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptConfirmQuestion extends PromptBaseQuestion<boolean>, Omit<ConfirmOptions, "message"> {
    type: "confirm";
}
```

## Description

Boolean confirmation prompt (yes/no).

## type

```ts
type: "confirm";
```
