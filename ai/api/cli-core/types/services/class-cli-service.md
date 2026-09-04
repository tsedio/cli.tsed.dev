---
title: CliService from @tsed/cli-core
description: api documentation of CliService from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CliService class
---
# CliService - @tsed/cli-core

## Usage

```typescript
import { CliService } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliService.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliService.ts#L0-L0).

## Overview

```ts
class CliService {
    readonly reinstallAfterRun: boolean;
    readonly program: Command;
    protected pkg: Record<string, any>;
    protected hooks: CliHooks;
    protected projectPkg: ProjectPackageJson;
    protected packageManagers: PackageManagersModule;
    protected promptRunner: PromptRunner;
    
    parseArgs(argv: string[]): Promise<void>;
    runLifecycle(cmdName: string, data: CommandData | undefined, $ctx: DIContext): Promise<Promise<void>>;
    exec(cmdName: string, data: any, $ctx: DIContext): Promise<void>;
    prompt(cmdName: string, data: CommandData | undefined, $ctx: DIContext): Promise<CommandData>;
    getTasks(cmdName: string, data: any): Promise<Task[]>;
    getPostInstallTasks(cmdName: string, data: any): Promise<Task<any>[]>;
    createCommand(metadata: CommandMetadata): any;
    load(): void;
    
    
    
}
```

<!-- Members -->

## readonly reinstallAfterRun

```ts
readonly reinstallAfterRun: boolean;
```

## readonly program

```ts
readonly program: Command;
```

## protected pkg

```ts
protected pkg: Record<string, any>;
```

## protected hooks

```ts
protected hooks: CliHooks;
```

## protected projectPkg

```ts
protected projectPkg: ProjectPackageJson;
```

## protected packageManagers

```ts
protected packageManagers: PackageManagersModule;
```

## protected promptRunner

```ts
protected promptRunner: PromptRunner;
```

## parseArgs

```ts
parseArgs(argv: string[]): Promise<void>;
```

Parse process.argv and runLifecycle action

## runLifecycle

```ts
runLifecycle(cmdName: string, data: CommandData | undefined, $ctx: DIContext): Promise<Promise<void>>;
```

Run lifecycle

## exec

```ts
exec(cmdName: string, data: any, $ctx: DIContext): Promise<void>;
```

## prompt

```ts
prompt(cmdName: string, data: CommandData | undefined, $ctx: DIContext): Promise<CommandData>;
```

Run prompt for a given command

## getTasks

```ts
getTasks(cmdName: string, data: any): Promise<Task[]>;
```

Run lifecycle

## getPostInstallTasks

```ts
getPostInstallTasks(cmdName: string, data: any): Promise<Task<any>[]>;
```

## createCommand

```ts
createCommand(metadata: CommandMetadata): any;
```

## load

```ts
load(): void;
```
