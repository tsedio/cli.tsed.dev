---
title: command from @tsed/cli-core
description: api documentation of command from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation command function
---
# command - @tsed/cli-core

## Usage

```typescript
import { command } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/fn/command.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/fn/command.ts#L0-L0).

## Overview

```ts
function command<Input>(options: CommandOptions<Input>): TsED.ProviderBuilder<FactoryTokenProvider<{
    $prompt: any;
    $exec: any;
    token: import("@tsed/di").TokenProvider<CommandProvider>;
    name: string;
    alias?: string;
    description: string;
    args?: {
        [key: string]: import("../interfaces/CommandOptions.js").CommandArg;
    };
    inputSchema?: JsonSchema<Input> | (() => JsonSchema<Input>) | undefined;
    options?: {
        [key: string]: import("../interfaces/CommandOptions.js").CommandOpts;
    };
    allowUnknownOption?: boolean;
    enableFeatures?: string[];
    disableReadUpPkg?: boolean;
    renderMode?: import("@tsed/cli-tasks").TasksOptions["renderMode"];
} | {
    $prompt: any;
    $exec: any;
    handler: (data: Input) => import("@tsed/cli-tasks").MaybePromise<void | import("../interfaces/index.js").Task<Input>[]>;
    prompt?(initialOptions: Partial<Input>): import("@tsed/cli-prompts").PromptQuestion[] | Promise<import("@tsed/cli-prompts").PromptQuestion[]>;
    name: string;
    alias?: string;
    description: string;
    args?: {
        [key: string]: import("../interfaces/CommandOptions.js").CommandArg;
    };
    inputSchema?: JsonSchema<Input> | (() => JsonSchema<Input>) | undefined;
    options?: {
        [key: string]: import("../interfaces/CommandOptions.js").CommandOpts;
    };
    allowUnknownOption?: boolean;
    enableFeatures?: string[];
    disableReadUpPkg?: boolean;
    renderMode?: import("@tsed/cli-tasks").TasksOptions["renderMode"];
}>> | TsED.ClassProviderBuilder<Type<CommandProvider<Input>>>;
```

<!-- Members -->

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
token: import("@tsed/di").TokenProvider<CommandProvider>;
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
     [key: string]: import("../interfaces/CommandOptions.js").CommandArg;
 };
```

## inputSchema: JsonSchema

```ts
inputSchema?: JsonSchema<Input> | (() => JsonSchema<Input>) | undefined;
```

## options

```ts
options?: {
     [key: string]: import("../interfaces/CommandOptions.js").CommandOpts;
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
renderMode?: import("@tsed/cli-tasks").TasksOptions["renderMode"];
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
handler: (data: Input) => import("@tsed/cli-tasks").MaybePromise<void | import("../interfaces/index.js").Task<Input>[]>;
```

## prompt

```ts
prompt?(initialOptions: Partial<Input>): import("@tsed/cli-prompts").PromptQuestion[] | Promise<import("@tsed/cli-prompts").PromptQuestion[]>;
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
     [key: string]: import("../interfaces/CommandOptions.js").CommandArg;
 };
```

## inputSchema: JsonSchema

```ts
inputSchema?: JsonSchema<Input> | (() => JsonSchema<Input>) | undefined;
```

## options

```ts
options?: {
     [key: string]: import("../interfaces/CommandOptions.js").CommandOpts;
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
renderMode?: import("@tsed/cli-tasks").TasksOptions["renderMode"];
```
