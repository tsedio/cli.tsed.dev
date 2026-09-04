---
title: PromptListQuestion from @tsed/cli-prompts
description: api documentation of PromptListQuestion from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation PromptListQuestion interface
---
# PromptListQuestion - @tsed/cli-prompts

## Usage

```typescript
import { PromptListQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptListQuestion<Value = any> extends PromptBaseQuestion<Value>, Omit<SelectOptions<Value>, "message" | "options"> {
    type: "list";
    choices: string[] | PromptChoice<Value>[];
}
```

<!-- Description -->

## Description

Single-select prompt with predefined choices.

<!-- Members -->

## type

```ts
type: "list";
```

## choices

```ts
choices: string[] | PromptChoice<Value>[];
```

Available choices displayed to the user.
