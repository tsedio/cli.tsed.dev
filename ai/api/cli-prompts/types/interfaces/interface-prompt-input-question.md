---
title: PromptInputQuestion from @tsed/cli-prompts
description: api documentation of PromptInputQuestion from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation PromptInputQuestion interface
---
# PromptInputQuestion - @tsed/cli-prompts

## Usage

```typescript
import { PromptInputQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptInputQuestion extends PromptBaseQuestion<string>, Omit<TextOptions, "message"> {
    type: "input";
}
```

<!-- Description -->

## Description

Plain text prompt.

<!-- Members -->

## type

```ts
type: "input";
```
