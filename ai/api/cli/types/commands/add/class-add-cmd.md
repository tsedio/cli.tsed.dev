---
title: AddCmd from @tsed/cli
description: api documentation of AddCmd from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation AddCmd class
---
# AddCmd - @tsed/cli

## Usage

```typescript
import { AddCmd } from "@tsed/cli";
```

> See [/packages/cli/src/commands/add/AddCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/add/AddCmd.ts#L0-L0).

## Overview

```ts
class AddCmd implements CommandProvider {
    protected cliPlugins: CliPlugins;
    protected packageJson: ProjectPackageJson;
    protected packageManagers: PackageManagersModule;
    $prompt(initialOptions: any): PromptQuestion[];
    $exec(ctx: AddCmdOptions): Task[];
}
```

<!-- Members -->

## protected cliPlugins

```ts
protected cliPlugins: CliPlugins;
```

## protected packageJson

```ts
protected packageJson: ProjectPackageJson;
```

## protected packageManagers

```ts
protected packageManagers: PackageManagersModule;
```

## $prompt

```ts
$prompt(initialOptions: any): PromptQuestion[];
```

## $exec

```ts
$exec(ctx: AddCmdOptions): Task[];
```
