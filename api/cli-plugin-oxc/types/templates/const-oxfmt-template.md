---
url: /api/cli-plugin-oxc/types/templates/const-oxfmt-template.md
description: api documentation of oxfmtTemplate from @tsed/cli-plugin-oxc
---

## Usage

```typescript
import { oxfmtTemplate } from "@tsed/cli-plugin-oxc/src/templates/oxc.template";
```

> See [/packages/cli-plugin-oxc/src/templates/oxc.template.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-oxc/src/templates/oxc.template.ts#L0-L0).

## Overview

```ts
const oxfmtTemplate: import("@tsed/di").FactoryTokenProvider<{
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
    schema?: import("@tsed/schema").JsonSchema;
    render(symbolName: string, data: import("@tsed/cli").GenerateCmdContext): Promise<string | undefined | import("@tsed/cli").TemplateRenderReturnType> | string | undefined | import("@tsed/cli").TemplateRenderReturnType;
    prompts?(data: import("@tsed/cli").GenerateCmdContext): import("@tsed/cli-prompts").PromptQuestion[] | Promise<import("@tsed/cli-prompts").PromptQuestion[]>;
    hooks?: import("@tsed/di").ProviderOpts["hooks"];
}>;
```

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

## ext

```ts
ext: string | null;
```

## hidden

```ts
hidden?: boolean;
```

## preserveCase

```ts
preserveCase?: boolean;
```

## preserveDirectory

```ts
preserveDirectory?: boolean;
```

## schema: import

```ts
schema?: import("@tsed/schema").JsonSchema;
```

## render

```ts
render(symbolName: string, data: import("@tsed/cli").GenerateCmdContext): Promise<string | undefined | import("@tsed/cli").TemplateRenderReturnType> | string | undefined | import("@tsed/cli").TemplateRenderReturnType;
```

## prompts

```ts
prompts?(data: import("@tsed/cli").GenerateCmdContext): import("@tsed/cli-prompts").PromptQuestion[] | Promise<import("@tsed/cli-prompts").PromptQuestion[]>;
```

## hooks: import

```ts
hooks?: import("@tsed/di").ProviderOpts["hooks"];
```
