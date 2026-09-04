---
title: resolveListDefault from @tsed/cli-prompts
description: api documentation of resolveListDefault from @tsed/cli-prompts
meta:
 - name: keywords
   description: api typescript node.js documentation resolveListDefault function
---
# resolveListDefault - @tsed/cli-prompts

## Usage

```typescript
import { resolveListDefault } from "@tsed/cli-prompts/src/utils/resolveListDefault";
```

> See [/packages/cli-prompts/src/utils/resolveListDefault.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/utils/resolveListDefault.ts#L0-L0).

## Overview

```ts
function resolveListDefault(question: Pick<PromptListQuestion | PromptAutocompleteQuestion, "default">, choices: NormalizedChoice[]): any;
```
