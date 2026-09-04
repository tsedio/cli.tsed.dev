---
url: /api/cli-prompts/types/interfaces/type-normalized-prompt-question.md
description: api documentation of NormalizedPromptQuestion from @tsed/cli-prompts
---

## Usage

```typescript
import { NormalizedPromptQuestion } from "@tsed/cli-prompts/src/interfaces/NormalizedPromptQuestion";
```

> See [/packages/cli-prompts/src/interfaces/NormalizedPromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/NormalizedPromptQuestion.ts#L0-L0).

## Overview

```ts
type NormalizedPromptQuestion = PromptQuestion & {
    message: string;
    choices?: NormalizedChoice[];
    source?: PromptAutocompleteQuestion["source"];
    mask?: PromptPasswordQuestion["mask"];
};
```

## message

```ts
message: string;
```

## choices

```ts
choices?: NormalizedChoice[];
```

## source

```ts
source?: PromptAutocompleteQuestion["source"];
```

## mask

```ts
mask?: PromptPasswordQuestion["mask"];
```
