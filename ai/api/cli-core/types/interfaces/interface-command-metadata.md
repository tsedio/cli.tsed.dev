---
title: CommandMetadata from @tsed/cli-core
description: api documentation of CommandMetadata from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CommandMetadata interface
---
# CommandMetadata - @tsed/cli-core

## Usage

```typescript
import { CommandMetadata } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/interfaces/CommandMetadata.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/interfaces/CommandMetadata.ts#L0-L0).

## Overview

```ts
interface CommandMetadata extends Omit<BaseCommandOptions<any>, "args" | "options" | "allowUnknownOption"> {
    enableFeatures: string[];
    disableReadUpPkg: boolean;
    renderMode?: TasksOptions["renderMode"];
    getOptions(): {
        args: {
            [key: string]: CommandArg;
        };
        options: {
            [key: string]: CommandOpts;
        };
        allowUnknownOption?: boolean;
    };
}
```

<!-- Members -->

## enableFeatures

```ts
enableFeatures: string[];
```

## disableReadUpPkg

```ts
disableReadUpPkg: boolean;
```

## renderMode

```ts
renderMode?: TasksOptions["renderMode"];
```

## getOptions

```ts
getOptions(): {
     args: {
         [key: string]: CommandArg;
     };
     options: {
         [key: string]: CommandOpts;
     };
     allowUnknownOption?: boolean;
 };
```
