---
url: /api/cli-plugin-typeorm/types/hooks/class-type-orm-generate-hook.md
description: api documentation of TypeORMGenerateHook from @tsed/cli-plugin-typeorm
---

## Usage

```typescript
import { TypeORMGenerateHook } from "@tsed/cli-plugin-typeorm";
```

> See [/packages/cli-plugin-typeorm/src/hooks/TypeORMGenerateHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-typeorm/src/hooks/TypeORMGenerateHook.ts#L0-L0).

## Overview

```ts
class TypeORMGenerateHook implements AlterGenerateTasks {
    protected projectPackageJson: ProjectPackageJson;
    protected cliDockerComposeYaml: CliDockerComposeYaml;
    $alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[] | Promise<Task[]>;
}
```

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## protected cliDockerComposeYaml

```ts
protected cliDockerComposeYaml: CliDockerComposeYaml;
```

## $alterGenerateTasks

```ts
$alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[] | Promise<Task[]>;
```
