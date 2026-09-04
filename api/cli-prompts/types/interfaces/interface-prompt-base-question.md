---
url: /api/cli-prompts/types/interfaces/interface-prompt-base-question.md
description: api documentation of PromptBaseQuestion from @tsed/cli-prompts
---

## Usage

```typescript
import { PromptBaseQuestion } from "@tsed/cli-prompts";
```

> See [/packages/cli-prompts/src/interfaces/PromptQuestion.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-prompts/src/interfaces/PromptQuestion.ts#L0-L0).

## Overview

```ts
interface PromptBaseQuestion<Value = any> {
    type: PromptType;
    name: string;
    message: string | ((answers: Record<string, any>) => MaybePromise<string>);
    when?: PromptWhen;
    default?: Value | ((answers: Record<string, any>) => MaybePromise<Value>);
    transformer?: PromptTransformer;
    filter?: PromptFilter;
    loop?: boolean;
}
```

## Description

Base contract shared by every question type.

## type

```ts
type: PromptType;
```

Prompt type to render.

## name

```ts
name: string;
```

Unique answer key assigned to the prompt.

## message: string |

```ts
message: string | ((answers: Record<string, any>) => MaybePromise<string>);
```

Prompt label. Accepts a string or function (resolved at runtime).

## when

```ts
when?: PromptWhen;
```

Allows skipping the prompt based on previous answers.

## default: Value |

```ts
default?: Value | ((answers: Record<string, any>) => MaybePromise<Value>);
```

Default input value or factory function returning one.

## transformer

```ts
transformer?: PromptTransformer;
```

Mutates the visual input while the user types.

## filter

```ts
filter?: PromptFilter;
```

Mutates the stored answer after validation.

## loop

```ts
loop?: boolean;
```

Whether select prompts loop when reaching boundaries.
