---
url: /api/cli-core/types/interfaces/type-command-options.md
description: api documentation of CommandOptions from @tsed/cli-core
---

## Usage

```typescript
import { CommandOptions } from "@tsed/cli-core/src/interfaces/CommandOptions";
```

> See [/packages/cli-core/src/interfaces/CommandOptions.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/interfaces/CommandOptions.ts#L0-L0).

## Overview

```ts
type CommandOptions<Input> = ClassCommandOptions<Input> | FunctionalCommandOptions<Input>;
```
