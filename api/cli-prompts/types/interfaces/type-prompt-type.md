---
url: /api/cli-prompts/types/interfaces/type-prompt-type.md
description: api documentation of PromptType from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptType } from "@tsed/cli-prompts/src/interfaces/PromptQuestion";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
type PromptType = "input" | "password" | "confirm" | "list" | "checkbox" | "autocomplete";
```

## Description

Enumerates the built-in prompt types supported by the Ts.ED CLI.
