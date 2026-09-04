---
title: PromptAutocompleteQuestion from @tsed/cli-prompts
description: api documentation of PromptAutocompleteQuestion from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation PromptAutocompleteQuestion interface
---
# PromptAutocompleteQuestion - @tsed/cli-prompts

## Usage

```typescript
import { PromptAutocompleteQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptAutocompleteQuestion<Value = any> extends PromptBaseQuestion<Value>, Omit<AutocompleteOptions<Value>, "message" | "options" | "filter"> {
    type: "autocomplete";
    source?: (answers: Record<string, any>) => MaybePromise<PromptChoice<Value>[]>;
    choices?: string[] | PromptChoiceInput<Value>[];
}
```

<!-- Description -->

## Description

Searchable prompt that fetches choices dynamically.

<!-- Members -->

## type

```ts
type: "autocomplete";
```

## source:

```ts
source?: (answers: Record<string, any>) => MaybePromise<PromptChoice<Value>[]>;
```

Async loader returning the set of choices filtered by the keyword.

## choices

```ts
choices?: string[] | PromptChoiceInput<Value>[];
```

Available choices displayed to the user.
