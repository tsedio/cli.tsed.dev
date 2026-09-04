---
title: PromptWhen from @tsed/cli-prompts
description: api documentation of PromptWhen from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation PromptWhen type
---
# PromptWhen - @tsed/cli-prompts

## Usage

```typescript
import { PromptWhen } from "@tsed/cli-prompts/src/interfaces/PromptQuestion";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
type PromptWhen = boolean | ((answers: Record<string, any>) => MaybePromise<boolean>);
```

<!-- Description -->

## Description

Determines whether a prompt should run.
