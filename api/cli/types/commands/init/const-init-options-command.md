---
url: /api/cli/types/commands/init/const-init-options-command.md
description: api documentation of InitOptionsCommand from @tsed/cli
---

## Usage

```typescript
import { InitOptionsCommand } from "@tsed/cli/src/commands/init/InitOptionsCmd";
```

> See [/packages/cli/src/commands/init/InitOptionsCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/init/InitOptionsCmd.ts#L0-L0).

## Overview

```ts
const InitOptionsCommand: import("@tsed/cli-core").FactoryTokenProvider<{
    $prompt: any;
    $exec: any;
    token: import("@tsed/cli-core").TokenProvider<import("@tsed/cli-core").CommandProvider>;
    name: string;
    alias?: string;
    description: string;
    args?: {
        [key: string]: import("@tsed/cli-core").CommandArg;
    };
    inputSchema?: import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
        indent: import("@tsed/schema").JsonSchema<number>;
    }>> | (() => import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
        indent: import("@tsed/schema").JsonSchema<number>;
    }>>) | undefined;
    options?: {
        [key: string]: import("@tsed/cli-core").CommandOpts;
    };
    allowUnknownOption?: boolean;
    enableFeatures?: string[];
    disableReadUpPkg?: boolean;
    renderMode?: import("@tsed/cli-core").TasksOptions["renderMode"];
} | {
    $prompt: any;
    $exec: any;
    handler: (data: import("@tsed/schema").PropsToShape<{
        indent: import("@tsed/schema").JsonSchema<number>;
    }>) => import("@tsed/cli-core").MaybePromise<void | import("@tsed/cli-core").Task<import("@tsed/schema").PropsToShape<{
        indent: import("@tsed/schema").JsonSchema<number>;
    }>>[]>;
    prompt?(initialOptions: Partial<import("@tsed/schema").PropsToShape<{
        indent: import("@tsed/schema").JsonSchema<number>;
    }>>): import("@tsed/cli-core").PromptQuestion[] | Promise<import("@tsed/cli-core").PromptQuestion[]>;
    name: string;
    alias?: string;
    description: string;
    args?: {
        [key: string]: import("@tsed/cli-core").CommandArg;
    };
    inputSchema?: import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
        indent: import("@tsed/schema").JsonSchema<number>;
    }>> | (() => import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
        indent: import("@tsed/schema").JsonSchema<number>;
    }>>) | undefined;
    options?: {
        [key: string]: import("@tsed/cli-core").CommandOpts;
    };
    allowUnknownOption?: boolean;
    enableFeatures?: string[];
    disableReadUpPkg?: boolean;
    renderMode?: import("@tsed/cli-core").TasksOptions["renderMode"];
}> | import("@tsed/cli-core").Type<import("@tsed/cli-core").CommandProvider<import("@tsed/schema").PropsToShape<{
    indent: import("@tsed/schema").JsonSchema<number>;
}>>>;
```

## $prompt

```ts
$prompt: any;
```

## $exec

```ts
$exec: any;
```

## token: import

```ts
token: import("@tsed/cli-core").TokenProvider<import("@tsed/cli-core").CommandProvider>;
```

## name

```ts
name: string;
```

## alias

```ts
alias?: string;
```

## description

```ts
description: string;
```

## args

```ts
args?: {
     [key: string]: import("@tsed/cli-core").CommandArg;
 };
```

## inputSchema: import

```ts
inputSchema?: import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
     indent: import("@tsed/schema").JsonSchema<number>;
 }>> | (() => import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
     indent: import("@tsed/schema").JsonSchema<number>;
 }>>) | undefined;
```

## options

```ts
options?: {
     [key: string]: import("@tsed/cli-core").CommandOpts;
 };
```

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

## renderMode: import

```ts
renderMode?: import("@tsed/cli-core").TasksOptions["renderMode"];
```

##

```ts
} | {
```

## $prompt

```ts
$prompt: any;
```

## $exec

```ts
$exec: any;
```

## handler:

```ts
handler: (data: import("@tsed/schema").PropsToShape<{
     indent: import("@tsed/schema").JsonSchema<number>;
 }>) => import("@tsed/cli-core").MaybePromise<void | import("@tsed/cli-core").Task<import("@tsed/schema").PropsToShape<{
     indent: import("@tsed/schema").JsonSchema<number>;
 }>>[]>;
```

## prompt

```ts
prompt?(initialOptions: Partial<import("@tsed/schema").PropsToShape<{
     indent: import("@tsed/schema").JsonSchema<number>;
 }>>): import("@tsed/cli-core").PromptQuestion[] | Promise<import("@tsed/cli-core").PromptQuestion[]>;
```

## name

```ts
name: string;
```

## alias

```ts
alias?: string;
```

## description

```ts
description: string;
```

## args

```ts
args?: {
     [key: string]: import("@tsed/cli-core").CommandArg;
 };
```

## inputSchema: import

```ts
inputSchema?: import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
     indent: import("@tsed/schema").JsonSchema<number>;
 }>> | (() => import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
     indent: import("@tsed/schema").JsonSchema<number>;
 }>>) | undefined;
```

## options

```ts
options?: {
     [key: string]: import("@tsed/cli-core").CommandOpts;
 };
```

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

## renderMode: import

```ts
renderMode?: import("@tsed/cli-core").TasksOptions["renderMode"];
```

## }> | import

```ts
}> | import("@tsed/cli-core").Type<import("@tsed/cli-core").CommandProvider<import("@tsed/schema").PropsToShape<{
```

## indent: import

```ts
indent: import("@tsed/schema").JsonSchema<number>;
```
