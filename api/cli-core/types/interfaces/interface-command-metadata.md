---
url: /api/cli-core/types/interfaces/interface-command-metadata.md
description: api documentation of CommandMetadata from @tsed/cli-core
---

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
