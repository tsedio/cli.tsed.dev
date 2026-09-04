---
url: /api/cli-plugin-jest/types/hooks/class-jest-generate-hook.md
description: api documentation of JestGenerateHook from @tsed/cli-plugin-jest
---

## Usage

```typescript
import { JestGenerateHook } from "@tsed/cli-plugin-jest/src/hooks/JestGenerateHook";
```

> See [/packages/cli-plugin-jest/src/hooks/JestGenerateHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-jest/src/hooks/JestGenerateHook.ts#L0-L0).

## Overview

```ts
class JestGenerateHook implements AlterGenerateTasks {
    protected projectService: CliProjectService;
    $alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[];
}
```

## protected projectService

```ts
protected projectService: CliProjectService;
```

## $alterGenerateTasks

```ts
$alterGenerateTasks(tasks: Task[], data: GenerateCmdContext): Task[];
```
