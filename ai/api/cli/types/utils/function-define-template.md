---
title: defineTemplate from @tsed/cli
description: api documentation of defineTemplate from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation defineTemplate function
---
# defineTemplate - @tsed/cli

## Usage

```typescript
import { defineTemplate } from "@tsed/cli";
```

> See [/packages/cli/src/utils/defineTemplate.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/utils/defineTemplate.ts#L0-L0).

## Overview

```ts
function defineTemplate(opts: DefineTemplateOptions): import("@tsed/cli-core").FactoryTokenProvider<{
    id: string;
    label: string;
    description?: string;
    outputDir: string;
    type?: string;
    fileName?: string;
    ext: string | null;
    hidden?: boolean;
    preserveCase?: boolean;
    preserveDirectory?: boolean;
    schema?: JsonSchema;
    render(symbolName: string, data: GenerateCmdContext): Promise<string | undefined | TemplateRenderReturnType> | string | undefined | TemplateRenderReturnType;
    prompts?(data: GenerateCmdContext): PromptQuestion[] | Promise<PromptQuestion[]>;
    hooks?: ProviderOpts["hooks"];
}>;
```

<!-- Members -->

## id

```ts
id: string;
```

## label

```ts
label: string;
```

## description

```ts
description?: string;
```

## outputDir

```ts
outputDir: string;
```

## type

```ts
type?: string;
```

## fileName

```ts
fileName?: string;
```

The file name format without the extension.

## ext

```ts
ext: string | null;
```

## hidden

```ts
hidden?: boolean;
```

If `true` the template will be hidden in the list of available templates
during the generate command.

## preserveCase

```ts
preserveCase?: boolean;
```

If `true` the file name won't be altered (e.g. `MyService` will always be `MyService.ts`)
If `false` the file name will be transformed depending on the project style (e.g. `MyService` could be `my-service.ts`).

## preserveDirectory

```ts
preserveDirectory?: boolean;
```

If `true` the directory structure will be preserved when generating the file.

## schema

```ts
schema?: JsonSchema;
```

Optional Ts.ED Schema describing template-specific arguments (exclude global fields like `type` and `name`).
Can be provided as a JsonSchema builder result (from @tsed/schema DSL) or any object exposing `toJSON()` to JSON Schema.

## render

```ts
render(symbolName: string, data: GenerateCmdContext): Promise<string | undefined | TemplateRenderReturnType> | string | undefined | TemplateRenderReturnType;
```

## prompts

```ts
prompts?(data: GenerateCmdContext): PromptQuestion[] | Promise<PromptQuestion[]>;
```

## hooks

```ts
hooks?: ProviderOpts["hooks"];
```
