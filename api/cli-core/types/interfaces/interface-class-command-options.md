---
url: /api/cli-core/types/interfaces/interface-class-command-options.md
description: api documentation of ClassCommandOptions from @tsed/cli-core
---

## Usage

```typescript
import { ClassCommandOptions } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/interfaces/CommandOptions.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/interfaces/CommandOptions.ts#L0-L0).

## Overview

```ts
interface ClassCommandOptions<Input> extends BaseCommandOptions<Input> {
    token: TokenProvider<CommandProvider>;
    [key: string]: any;
}
```

## token

```ts
token: TokenProvider<CommandProvider>;
```

## \[key: string]

```ts
[key: string]: any;
```
