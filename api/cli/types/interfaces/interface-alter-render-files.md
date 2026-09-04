---
url: /api/cli/types/interfaces/interface-alter-render-files.md
description: api documentation of AlterRenderFiles from @tsed/cli
---

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
