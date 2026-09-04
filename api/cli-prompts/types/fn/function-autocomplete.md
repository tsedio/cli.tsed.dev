---
url: /api/cli-prompts/types/fn/function-autocomplete.md
description: api documentation of autocomplete from @tsed/cli-prompts
---

## Usage

```typescript
import { autocomplete } from "@tsed/cli-prompts/src/fn/autocomplete";
```

> See [/packages/cli-prompts/src/fn/autocomplete.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/fn/autocomplete.ts#L0-L0).

## Overview

```ts
function autocomplete(question: NormalizedPromptQuestion, answers: Record<string, unknown>): Promise<unknown>;
```
