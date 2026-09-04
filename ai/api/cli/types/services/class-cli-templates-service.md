---
title: CliTemplatesService from @tsed/cli
description: api documentation of CliTemplatesService from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation CliTemplatesService class
---
# CliTemplatesService - @tsed/cli

## Usage

```typescript
import { CliTemplatesService } from "@tsed/cli";
```

> See [/packages/cli/src/services/CliTemplatesService.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/services/CliTemplatesService.ts#L0-L0).

## Overview

```ts
class CliTemplatesService {
    readonly fs: CliFs;
    get rootDir(): string;
    get srcDir(): string;
    get templatesDir(): string;
    $onInit(): Promise<void>;
    loadTemplates(): Promise<void>;
    getAll(): DefineTemplateOptions[];
    find(id?: string): DefineTemplateOptions[];
    get(id: string): DefineTemplateOptions | undefined;
    render(templateId: string, data: TemplateRenderOptions): Promise<TemplateRenderReturnType | undefined>;
    getRenderedFiles(): TemplateRenderReturnType[];
    protected pushRenderResult(renderedFile: TemplateRenderReturnType): TemplateRenderReturnType;
}
```

<!-- Members -->

## readonly fs

```ts
readonly fs: CliFs;
```

## get rootDir

```ts
get rootDir(): string;
```

## get srcDir

```ts
get srcDir(): string;
```

## get templatesDir

```ts
get templatesDir(): string;
```

## $onInit

```ts
$onInit(): Promise<void>;
```

## loadTemplates

```ts
loadTemplates(): Promise<void>;
```

## getAll

```ts
getAll(): DefineTemplateOptions[];
```

## find

```ts
find(id?: string): DefineTemplateOptions[];
```

## get

```ts
get(id: string): DefineTemplateOptions | undefined;
```

## render

```ts
render(templateId: string, data: TemplateRenderOptions): Promise<TemplateRenderReturnType | undefined>;
```

## getRenderedFiles

```ts
getRenderedFiles(): TemplateRenderReturnType[];
```

## protected pushRenderResult

```ts
protected pushRenderResult(renderedFile: TemplateRenderReturnType): TemplateRenderReturnType;
```
