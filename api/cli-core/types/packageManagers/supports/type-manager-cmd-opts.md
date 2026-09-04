---
url: /api/cli-core/types/packageManagers/supports/type-manager-cmd-opts.md
description: api documentation of ManagerCmdOpts from @tsed/cli-core
---

## Usage

```typescript
import { ManagerCmdOpts } from "@tsed/cli-core/src/packageManagers/supports/BaseManager";
```

> See [/packages/cli-core/src/packageManagers/supports/BaseManager.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/packageManagers/supports/BaseManager.ts#L0-L0).

## Overview

```ts
type ManagerCmdOpts = {
    verbose?: boolean;
} & Omit<Options, "verbose">;
```

## verbose

```ts
verbose?: boolean;
```
