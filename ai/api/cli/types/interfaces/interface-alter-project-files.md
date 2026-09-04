---
title: AlterProjectFiles from @tsed/cli
description: api documentation of AlterProjectFiles from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation AlterProjectFiles interface
---
# AlterProjectFiles - @tsed/cli

## Usage

```typescript
import { AlterProjectFiles } from "@tsed/cli";
```

> See [/packages/cli/src/interfaces/AlterProjectFiles.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/interfaces/AlterProjectFiles.ts#L0-L0).

## Overview

```ts
interface AlterProjectFiles {
    $alterProjectFiles(project: ProjectClient, data: RenderDataContext): ProjectClient | Promise<ProjectClient>;
}
```

<!-- Members -->

## $alterProjectFiles

```ts
$alterProjectFiles(project: ProjectClient, data: RenderDataContext): ProjectClient | Promise<ProjectClient>;
```
