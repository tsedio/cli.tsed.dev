---
title: MongooseGenerateHook from @tsed/cli-plugin-mongoose
description: api documentation of MongooseGenerateHook from @tsed/cli-plugin-mongoose
meta:
 - name: keywords
   description: api typescript node.js documentation MongooseGenerateHook class
---
# MongooseGenerateHook - @tsed/cli-plugin-mongoose

## Usage

```typescript
import { MongooseGenerateHook } from "@tsed/cli-plugin-mongoose/src/hooks/MongooseGenerateHook";
```

> See [/packages/cli-plugin-mongoose/src/hooks/MongooseGenerateHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-mongoose/src/hooks/MongooseGenerateHook.ts#L0-L0).

## Overview

```ts
class MongooseGenerateHook implements AlterGenerateTasks, AlterProjectFiles {
    protected projectPackageJson: ProjectPackageJson;
    protected cliMongoose: CliMongoose;
    protected packages: any[];
    protected cliDockerComposeYaml: CliDockerComposeYaml;
    $alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[] | Promise<Task[]>;
    $alterProjectFiles(project: ProjectClient, data: GenerateCmdContext): Promise<ProjectClient> | ProjectClient;
}
```

<!-- Members -->

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## protected cliMongoose

```ts
protected cliMongoose: CliMongoose;
```

## protected packages

```ts
protected packages: any[];
```

## protected cliDockerComposeYaml

```ts
protected cliDockerComposeYaml: CliDockerComposeYaml;
```

## $alterGenerateTasks

```ts
$alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[] | Promise<Task[]>;
```

## $alterProjectFiles

```ts
$alterProjectFiles(project: ProjectClient, data: GenerateCmdContext): Promise<ProjectClient> | ProjectClient;
```
