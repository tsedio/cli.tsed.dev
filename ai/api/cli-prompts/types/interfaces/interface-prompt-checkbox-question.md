---
title: PromptCheckboxQuestion from @tsed/cli-prompts
description: api documentation of PromptCheckboxQuestion from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation PromptCheckboxQuestion interface
---
# PromptCheckboxQuestion - @tsed/cli-prompts

## Usage

```typescript
import { PromptCheckboxQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptCheckboxQuestion<Value = any> extends PromptBaseQuestion<Value[]>, Omit<MultiSelectOptions<Value>, "message" | "options"> {
    type: "checkbox";
    choices: string[] | PromptChoice<Value>[];
}
```

<!-- Description -->

## Description

Multi-select prompt where the result is an array of chosen values.

<!-- Members -->

## type

```ts
type: "checkbox";
```

## choices

```ts
choices: string[] | PromptChoice<Value>[];
```

Available choices displayed to the user.
