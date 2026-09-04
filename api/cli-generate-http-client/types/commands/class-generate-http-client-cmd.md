---
url: /api/cli-generate-http-client/types/commands/class-generate-http-client-cmd.md
description: api documentation of GenerateHttpClientCmd from @tsed/cli-generate-http-client
---

## Usage

```typescript
import { GenerateHttpClientCmd } from "@tsed/cli-generate-http-client";
```

> See [/packages/cli-generate-http-client/src/commands/GenerateHttpClientCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-generate-http-client/src/commands/GenerateHttpClientCmd.ts#L0-L0).

## Overview

```ts
class GenerateHttpClientCmd implements CommandProvider {
    protected fs: CliFs;
    protected serverModule: Type<any> | undefined;
    protected options: Partial<GenerateHttpClientOpts>;
    $mapContext($ctx: GenerateHttpClientCtx): {
        output: string;
        type: "axios" | "fetch";
        name: string;
        suffix: string;
    };
    $exec($ctx: GenerateHttpClientCtx): {
        title: string;
        task: () => Promise<void>;
    }[];
    
    
}
```

## protected fs

```ts
protected fs: CliFs;
```

## protected serverModule

```ts
protected serverModule: Type<any> | undefined;
```

## protected options

```ts
protected options: Partial<GenerateHttpClientOpts>;
```

## $mapContext

```ts
$mapContext($ctx: GenerateHttpClientCtx): {
     output: string;
     type: "axios" | "fetch";
     name: string;
     suffix: string;
 };
```

## $exec

```ts
$exec($ctx: GenerateHttpClientCtx): {
     title: string;
     task: () => Promise<void>;
 }[];
```
