---
title: BaseCommandOptions from @tsed/cli-core
description: api documentation of BaseCommandOptions from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation BaseCommandOptions interface
---
# BaseCommandOptions - @tsed/cli-core

## Usage

```typescript
import { BaseCommandOptions } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/interfaces/CommandOptions.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/interfaces/CommandOptions.ts#L0-L0).

## Overview

```ts
interface BaseCommandOptions<Input> {
    name: string;
    alias?: string;
    description: string;
    args?: {
        [key: string]: CommandArg;
    };
    inputSchema?: JsonSchema<Input> | (() => JsonSchema<Input>);
    options?: {
        [key: string]: CommandOpts;
    };
    allowUnknownOption?: boolean;
    enableFeatures?: string[];
    disableReadUpPkg?: boolean;
    renderMode?: TasksOptions["renderMode"];
}
```

<!-- Members -->

## name

```ts
name: string;
```

name commands

## alias

```ts
alias?: string;
```

## description

```ts
description: string;
```

CommandProvider description

## args

```ts
args?: {
     [key: string]: CommandArg;
 };
```

CommandProvider arguments

## inputSchema: JsonSchema

```ts
inputSchema?: JsonSchema<Input> | (() => JsonSchema<Input>);
```

## options

```ts
options?: {
     [key: string]: CommandOpts;
 };
```

CommandProvider options

## allowUnknownOption

```ts
allowUnknownOption?: boolean;
```

## enableFeatures

```ts
enableFeatures?: string[];
```

## disableReadUpPkg

```ts
disableReadUpPkg?: boolean;
```

## renderMode

```ts
renderMode?: TasksOptions["renderMode"];
```
