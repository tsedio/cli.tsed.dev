---
title: PromptConfirmQuestion from @tsed/cli-prompts
description: api documentation of PromptConfirmQuestion from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation PromptConfirmQuestion interface
---
# PromptConfirmQuestion - @tsed/cli-prompts

## Usage

```typescript
import { PromptConfirmQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptConfirmQuestion extends PromptBaseQuestion<boolean>, Omit<ConfirmOptions, "message"> {
    type: "confirm";
}
```

<!-- Description -->

## Description

Boolean confirmation prompt (yes/no).

<!-- Members -->

## type

```ts
type: "confirm";
```
