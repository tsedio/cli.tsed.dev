---
title: PromptTransformer from @tsed/cli-prompts
description: api documentation of PromptTransformer from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation PromptTransformer type
---
# PromptTransformer - @tsed/cli-prompts

## Usage

```typescript
import { PromptTransformer } from "@tsed/cli-prompts/src/interfaces/PromptQuestion";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
type PromptTransformer = (input: any, answers: Record<string, any>, flags?: {
    isFinal?: boolean;
}) => any;
```

<!-- Description -->

## Description

Transforms user input before it becomes part of the command context.

<!-- Members -->

## isFinal

```ts
isFinal?: boolean;
```
