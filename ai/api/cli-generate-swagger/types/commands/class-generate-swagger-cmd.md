---
title: GenerateSwaggerCmd from @tsed/cli-generate-swagger
description: api documentation of GenerateSwaggerCmd from @tsed/cli-generate-swagger
meta:
 - name: keywords
   description: api typescript node.js documentation GenerateSwaggerCmd class
---
# GenerateSwaggerCmd - @tsed/cli-generate-swagger

## Usage

```typescript
import { GenerateSwaggerCmd } from "@tsed/cli-generate-swagger";
```

> See [/packages/cli-generate-swagger/src/commands/GenerateSwaggerCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-generate-swagger/src/commands/GenerateSwaggerCmd.ts#L0-L0).

## Overview

```ts
class GenerateSwaggerCmd implements CommandProvider {
    protected fs: CliFs;
    protected cliYaml: CliYaml;
    protected serverModule: Type<any> | undefined;
    $mapContext($ctx: GenerateSwaggerCtx): {
        output: string;
    };
    $exec($ctx: GenerateSwaggerCtx): {
        title: string;
        task: () => Promise<void>;
    }[];
    
}
```

<!-- Members -->

## protected fs

```ts
protected fs: CliFs;
```

## protected cliYaml

```ts
protected cliYaml: CliYaml;
```

## protected serverModule

```ts
protected serverModule: Type<any> | undefined;
```

## $mapContext

```ts
$mapContext($ctx: GenerateSwaggerCtx): {
     output: string;
 };
```

## $exec

```ts
$exec($ctx: GenerateSwaggerCtx): {
     title: string;
     task: () => Promise<void>;
 }[];
```
