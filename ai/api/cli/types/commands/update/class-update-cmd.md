---
title: UpdateCmd from @tsed/cli
description: api documentation of UpdateCmd from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation UpdateCmd class
---
# UpdateCmd - @tsed/cli

## Usage

```typescript
import { UpdateCmd } from "@tsed/cli";
```

> See [/packages/cli/src/commands/update/UpdateCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/update/UpdateCmd.ts#L0-L0).

## Overview

```ts
class UpdateCmd implements CommandProvider {
    protected npmRegistryClient: NpmRegistryClient;
    protected projectPackage: ProjectPackageJson;
    protected packageManagers: PackageManagersModule;
    protected cliPackage: any;
    $prompt(initialOptions: Partial<UpdateCmdContext>): Promise<PromptQuestion[]>;
    $exec(ctx: UpdateCmdContext): Promise<Task[]>;
    
}
```

<!-- Members -->

## protected npmRegistryClient

```ts
protected npmRegistryClient: NpmRegistryClient;
```

## protected projectPackage

```ts
protected projectPackage: ProjectPackageJson;
```

## protected packageManagers

```ts
protected packageManagers: PackageManagersModule;
```

## protected cliPackage

```ts
protected cliPackage: any;
```

## $prompt

```ts
$prompt(initialOptions: Partial<UpdateCmdContext>): Promise<PromptQuestion[]>;
```

## $exec

```ts
$exec(ctx: UpdateCmdContext): Promise<Task[]>;
```
