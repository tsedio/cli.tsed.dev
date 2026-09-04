---
title: OutputFilePathPipe from @tsed/cli
description: api documentation of OutputFilePathPipe from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation OutputFilePathPipe class
---
# OutputFilePathPipe - @tsed/cli

## Usage

```typescript
import { OutputFilePathPipe } from "@tsed/cli";
```

> See [/packages/cli/src/pipes/OutputFilePathPipe.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/pipes/OutputFilePathPipe.ts#L0-L0).

## Overview

```ts
class OutputFilePathPipe {
    protected templatesService: CliTemplatesService;
    protected projectPackageJson: ProjectPackageJson;
    protected classNamePipe: SymbolNamePipe;
    transform(options: {
        name: string;
        type: string;
        subDir?: string;
        baseDir?: string;
        format?: ProjectConvention;
    }): string;
    getServerName(): string;
    getIndexControllerName(): string;
}
```

<!-- Members -->

## protected templatesService

```ts
protected templatesService: CliTemplatesService;
```

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## protected classNamePipe

```ts
protected classNamePipe: SymbolNamePipe;
```

## transform

```ts
transform(options: {
     name: string;
     type: string;
     subDir?: string;
     baseDir?: string;
     format?: ProjectConvention;
 }): string;
```

## getServerName

```ts
getServerName(): string;
```

## getIndexControllerName

```ts
getIndexControllerName(): string;
```
