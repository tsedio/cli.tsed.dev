---
url: /api/cli-core/types/interfaces/interface-command-data.md
description: api documentation of CommandData from @tsed/cli-core
---

## Usage

```typescript
import { CommandData } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/interfaces/CommandData.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/interfaces/CommandData.ts#L0-L0).

## Overview

```ts
interface CommandData extends TsED.InitialCommandData {
    commandName?: string;
    verbose?: TasksOptions["verbose"];
    renderMode?: TasksOptions["renderMode"];
    rawArgs?: string[];
    [key: string]: any;
}
```

## commandName

```ts
commandName?: string;
```

## verbose

```ts
verbose?: TasksOptions["verbose"];
```

## renderMode

```ts
renderMode?: TasksOptions["renderMode"];
```

## rawArgs

```ts
rawArgs?: string[];
```

## \[key: string]

```ts
[key: string]: any;
```
