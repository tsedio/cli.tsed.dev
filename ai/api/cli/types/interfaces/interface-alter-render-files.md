---
title: AlterRenderFiles from @tsed/cli
description: api documentation of AlterRenderFiles from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation AlterRenderFiles interface
---
# AlterRenderFiles - @tsed/cli

## Usage

```typescript
import { AlterRenderFiles } from "@tsed/cli";
```

> See [/packages/cli/src/interfaces/AlterRenderFiles.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/interfaces/AlterRenderFiles.ts#L0-L0).

## Overview

```ts
interface AlterRenderFiles {
    $alterRenderFiles(files: string[], data: RenderDataContext): (string | {
        id: string;
        from: string;
    })[] | Promise<(string | {
        id: string;
        from: string;
    })[]>;
}
```

<!-- Members -->

## $alterRenderFiles

```ts
$alterRenderFiles(files: string[], data: RenderDataContext): (string | {
     id: string;
     from: string;
 })[] | Promise<(string | {
     id: string;
     from: string;
 })[]>;
```
