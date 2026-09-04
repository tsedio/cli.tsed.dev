---
title: CommandData from @tsed/cli-core
description: api documentation of CommandData from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CommandData interface
---
# CommandData - @tsed/cli-core

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

<!-- Members -->

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
