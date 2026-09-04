---
title: CliMongoose from @tsed/cli-plugin-mongoose
description: api documentation of CliMongoose from @tsed/cli-plugin-mongoose
meta:
 - name: keywords
   description: api typescript node.js documentation CliMongoose class
---
# CliMongoose - @tsed/cli-plugin-mongoose

## Usage

```typescript
import { CliMongoose } from "@tsed/cli-plugin-mongoose/src/services/CliMongoose";
```

> See [/packages/cli-plugin-mongoose/src/services/CliMongoose.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-mongoose/src/services/CliMongoose.ts#L0-L0).

## Overview

```ts
class CliMongoose {
    protected projectPackageJson: ProjectPackageJson;
    createMongooseConnection(project: ProjectClient, name: string): Promise<void>;
    updateMongooseConfig(project: ProjectClient, name: string): Promise<void>;
    getMongooseConfig(project: ProjectClient): Promise<{
        source: import("ts-morph").SourceFile;
        options: import("ts-morph").ArrayLiteralExpression | undefined;
    }>;
    updateConfigFile(project: ProjectClient): void;
}
```

<!-- Members -->

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## createMongooseConnection

```ts
createMongooseConnection(project: ProjectClient, name: string): Promise<void>;
```

## updateMongooseConfig

```ts
updateMongooseConfig(project: ProjectClient, name: string): Promise<void>;
```

## getMongooseConfig

```ts
getMongooseConfig(project: ProjectClient): Promise<{
     source: import("ts-morph").SourceFile;
     options: import("ts-morph").ArrayLiteralExpression | undefined;
 }>;
```

## updateConfigFile

```ts
updateConfigFile(project: ProjectClient): void;
```
