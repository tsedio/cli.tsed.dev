---
title: PromptPasswordQuestion from @tsed/cli-prompts
description: api documentation of PromptPasswordQuestion from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation PromptPasswordQuestion interface
---
# PromptPasswordQuestion - @tsed/cli-prompts

## Usage

```typescript
import { PromptPasswordQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptPasswordQuestion extends PromptBaseQuestion<string>, Omit<PasswordOptions, "message"> {
    type: "password";
}
```

<!-- Description -->

## Description

Hidden text prompt (e.g., passwords or tokens).

<!-- Members -->

## type

```ts
type: "password";
```
