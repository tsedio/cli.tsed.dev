---
url: /api/cli-prompts/types/interfaces/type-prompt-choice.md
description: api documentation of PromptChoice from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptChoice } from "@tsed/cli-prompts/src/interfaces/PromptQuestion";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
type PromptChoice<Value = any> = Option<Value> & {
    name?: string;
    short?: string;
    disabled?: boolean | string;
    checked?: boolean;
};
```

## Description

Represents a single choice entry usable by select, checkbox, and autocomplete prompts.

## name

```ts
name?: string;
```

Human friendly label displayed in the prompt list.

## short

```ts
short?: string;
```

Optional short label shown beside the main choice name.

## disabled

```ts
disabled?: boolean | string;
```

Marks the choice as disabled (boolean or reason string).

## checked

```ts
checked?: boolean;
```

For checkbox prompts, marks the choice as checked by default.
