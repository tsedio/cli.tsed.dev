---
title: MongooseInitHook from @tsed/cli-plugin-mongoose
description: api documentation of MongooseInitHook from @tsed/cli-plugin-mongoose
meta:
 - name: keywords
   description: api typescript node.js documentation MongooseInitHook class
---
# MongooseInitHook - @tsed/cli-plugin-mongoose

## Usage

```typescript
import { MongooseInitHook } from "@tsed/cli-plugin-mongoose/src/hooks/MongooseInitHook";
```

> See [/packages/cli-plugin-mongoose/src/hooks/MongooseInitHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-mongoose/src/hooks/MongooseInitHook.ts#L0-L0).

## Overview

```ts
class MongooseInitHook implements CliCommandHooks {
    protected cliMongoose: CliMongoose;
    $alterProjectFiles(project: ProjectClient, data: RenderDataContext): Promise<ProjectClient>;
}
```

<!-- Members -->

## protected cliMongoose

```ts
protected cliMongoose: CliMongoose;
```

## $alterProjectFiles

```ts
$alterProjectFiles(project: ProjectClient, data: RenderDataContext): Promise<ProjectClient>;
```
