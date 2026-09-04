---
title: SymbolNamePipe from @tsed/cli
description: api documentation of SymbolNamePipe from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation SymbolNamePipe class
---
# SymbolNamePipe - @tsed/cli

## Usage

```typescript
import { SymbolNamePipe } from "@tsed/cli";
```

> See [/packages/cli/src/pipes/SymbolNamePipe.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/pipes/SymbolNamePipe.ts#L0-L0).

## Overview

```ts
class SymbolNamePipe {
    protected projectPackageJson: ProjectPackageJson;
    protected templates: CliTemplatesService;
    transform(options: {
        name: string;
        type: string;
        format?: ProjectConvention;
    }): string;
}
```

<!-- Members -->

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## protected templates

```ts
protected templates: CliTemplatesService;
```

## transform

```ts
transform(options: {
     name: string;
     type: string;
     format?: ProjectConvention;
 }): string;
```
