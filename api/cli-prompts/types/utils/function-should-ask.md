---
url: /api/cli-prompts/types/utils/function-should-ask.md
description: api documentation of shouldAsk from @tsed/cli-prompts
---

## Usage

```typescript
import { shouldAsk } from "@tsed/cli-prompts/src/utils/shouldAsk";
```

> See [/packages/cli-prompts/src/utils/shouldAsk.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/utils/shouldAsk.ts#L0-L0).

## Overview

```ts
function shouldAsk(question: PromptQuestion, answers: Record<string, any>): Promise<boolean>;
```
