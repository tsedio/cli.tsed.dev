---
url: /api/cli-plugin-mongoose/types/hooks/class-mongoose-init-hook.md
description: api documentation of MongooseInitHook from @tsed/cli-plugin-mongoose
---

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

## protected cliMongoose

```ts
protected cliMongoose: CliMongoose;
```

## $alterProjectFiles

```ts
$alterProjectFiles(project: ProjectClient, data: RenderDataContext): Promise<ProjectClient>;
```
