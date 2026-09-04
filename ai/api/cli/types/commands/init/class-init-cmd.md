---
title: InitCmd from @tsed/cli
description: api documentation of InitCmd from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation InitCmd class
---
# InitCmd - @tsed/cli

## Usage

```typescript
import { InitCmd } from "@tsed/cli";
```

> See [/packages/cli/src/commands/init/InitCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/init/InitCmd.ts#L0-L0).

## Overview

```ts
class InitCmd implements CommandProvider {
    protected configuration: any;
    protected cliPlugins: CliPlugins;
    protected packageJson: ProjectPackageJson;
    protected packageManagers: PackageManagersModule;
    protected runtimes: RuntimesModule;
    protected platforms: PlatformsModule;
    protected cliPackageJson: import("@tsed/cli-core").PackageJson;
    protected cliLoadFile: CliLoadFile;
    protected project: CliProjectService;
    protected execa: CliExeca;
    protected fs: CliFs;
    $prompt(initialOptions: Partial<InitOptions>): Promise<PromptQuestion[]>;
    $mapContext(ctx: any): InitOptions;
    protected isLaunchedWithBunx(): boolean;
    protected filterOnlyBun(values: string[]): string[];
    protected writeRcFiles(ctx: InitOptions): Promise<void>;
    preExec(ctx: InitOptions): Promise<void>;
    $exec(ctx: InitOptions): Promise<Task[]>;
    $afterPostInstall(): Task<any>[];
    resolveRootDir(ctx: Partial<InitOptions>): void;
    addScripts(ctx: InitOptions): void;
    addDependencies(ctx: InitOptions): void;
    addDevDependencies(ctx: InitOptions): void;
    addFeatures(ctx: InitOptions): void;
    baseFiles(ctx: InitCmdContext): Promise<void>;
    renderFiles(ctx: InitOptions): Promise<void>;
    $onFinish(data: {
        commandName?: string;
        rawArgs?: string[];
        features?: string[];
    }, er?: Error): void;
}
```

<!-- Members -->

## protected configuration

```ts
protected configuration: any;
```

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

## protected runtimes

```ts
protected runtimes: RuntimesModule;
```

## protected platforms

```ts
protected platforms: PlatformsModule;
```

## protected cliPackageJson: import

```ts
protected cliPackageJson: import("@tsed/cli-core").PackageJson;
```

## protected cliLoadFile

```ts
protected cliLoadFile: CliLoadFile;
```

## protected project

```ts
protected project: CliProjectService;
```

## protected execa

```ts
protected execa: CliExeca;
```

## protected fs

```ts
protected fs: CliFs;
```

## $prompt

```ts
$prompt(initialOptions: Partial<InitOptions>): Promise<PromptQuestion[]>;
```

## $mapContext

```ts
$mapContext(ctx: any): InitOptions;
```

## protected isLaunchedWithBunx

```ts
protected isLaunchedWithBunx(): boolean;
```

## protected filterOnlyBun

```ts
protected filterOnlyBun(values: string[]): string[];
```

## protected writeRcFiles

```ts
protected writeRcFiles(ctx: InitOptions): Promise<void>;
```

## preExec

```ts
preExec(ctx: InitOptions): Promise<void>;
```

## $exec

```ts
$exec(ctx: InitOptions): Promise<Task[]>;
```

## $afterPostInstall

```ts
$afterPostInstall(): Task<any>[];
```

## resolveRootDir

```ts
resolveRootDir(ctx: Partial<InitOptions>): void;
```

## addScripts

```ts
addScripts(ctx: InitOptions): void;
```

## addDependencies

```ts
addDependencies(ctx: InitOptions): void;
```

## addDevDependencies

```ts
addDevDependencies(ctx: InitOptions): void;
```

## addFeatures

```ts
addFeatures(ctx: InitOptions): void;
```

## baseFiles

```ts
baseFiles(ctx: InitCmdContext): Promise<void>;
```

## renderFiles

```ts
renderFiles(ctx: InitOptions): Promise<void>;
```

## $onFinish

```ts
$onFinish(data: {
     commandName?: string;
     rawArgs?: string[];
     features?: string[];
 }, er?: Error): void;
```
