---
title: AlterPackageJson from @tsed/cli
description: api documentation of AlterPackageJson from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation AlterPackageJson interface
---
# AlterPackageJson - @tsed/cli

## Usage

```typescript
import { AlterPackageJson } from "@tsed/cli";
```

> See [/packages/cli/src/interfaces/AlterPackageJson.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/interfaces/AlterPackageJson.ts#L0-L0).

## Overview

```ts
interface AlterPackageJson {
    $alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson | Promise<ProjectPackageJson>;
}
```

<!-- Members -->

## $alterPackageJson

```ts
$alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson | Promise<ProjectPackageJson>;
```
