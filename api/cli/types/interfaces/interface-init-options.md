---
url: /api/cli/types/interfaces/interface-init-options.md
description: api documentation of InitOptions from @tsed/cli
---

## Usage

```typescript
import { InitOptions } from "@tsed/cli";
```

> See [/packages/cli/src/interfaces/InitCmdOptions.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/interfaces/InitCmdOptions.ts#L0-L0).

## Overview

```ts
interface InitOptions extends RenderDataContext {
    root: string;
    srcDir: string;
    skipPrompt?: boolean;
    GH_TOKEN?: string;
}
```

## root

```ts
root: string;
```

## srcDir

```ts
srcDir: string;
```

## skipPrompt

```ts
skipPrompt?: boolean;
```

## GH\_TOKEN

```ts
GH_TOKEN?: string;
```
