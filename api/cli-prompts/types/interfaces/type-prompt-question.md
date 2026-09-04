---
url: /api/cli-prompts/types/interfaces/type-prompt-question.md
description: api documentation of PromptQuestion from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptQuestion } from "@tsed/cli-prompts/src/interfaces/PromptQuestion";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
type PromptQuestion = PromptInputQuestion | PromptPasswordQuestion | PromptConfirmQuestion | PromptListQuestion | PromptCheckboxQuestion | PromptAutocompleteQuestion;
```

## Description

Union describing every supported Ts.ED CLI question type.
