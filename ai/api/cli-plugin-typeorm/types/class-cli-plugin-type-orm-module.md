---
title: CliPluginTypeORMModule from @tsed/cli-plugin-typeorm
description: api documentation of CliPluginTypeORMModule from @tsed/cli-plugin-typeorm
meta:
 - name: keywords
   description: api typescript node.js documentation CliPluginTypeORMModule class
---
# CliPluginTypeORMModule - @tsed/cli-plugin-typeorm

## Usage

```typescript
import { CliPluginTypeORMModule } from "@tsed/cli-plugin-typeorm/src/CliPluginTypeORMModule";
```

> See [/packages/cli-plugin-typeorm/src/CliPluginTypeORMModule.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-typeorm/src/CliPluginTypeORMModule.ts#L0-L0).

## Overview

```ts
class CliPluginTypeORMModule implements AlterPackageJson {
    protected packageJson: ProjectPackageJson;
    $alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson;
}
```

<!-- Members -->

## protected packageJson

```ts
protected packageJson: ProjectPackageJson;
```

## $alterPackageJson

```ts
$alterPackageJson(packageJson: ProjectPackageJson, data: RenderDataContext): ProjectPackageJson;
```
