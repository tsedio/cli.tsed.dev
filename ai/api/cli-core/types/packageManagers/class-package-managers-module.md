---
title: PackageManagersModule from @tsed/cli-core
description: api documentation of PackageManagersModule from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation PackageManagersModule class
---
# PackageManagersModule - @tsed/cli-core

## Usage

```typescript
import { PackageManagersModule } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/packageManagers/PackageManagersModule.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/packageManagers/PackageManagersModule.ts#L0-L0).

## Overview

```ts
class PackageManagersModule {
    protected projectPackageJson: ProjectPackageJson;
    protected packageManagers: BaseManager[];
    init(options?: InstallOptions): Promise<void>;
    task(title: string, ctx?: InstallOptions): Task;
    install(options?: InstallOptions): Task[];
    list(): string[];
    get(name?: string): BaseManager;
    runScript(scriptName: string, { ignoreError, ...opts }?: {
        ignoreError?: boolean;
    } & ManagerCmdOpts & Record<string, any>): import("rxjs").Observable<unknown>;
}
```

<!-- Members -->

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## protected packageManagers

```ts
protected packageManagers: BaseManager[];
```

## init

```ts
init(options?: InstallOptions): Promise<void>;
```

## task

```ts
task(title: string, ctx?: InstallOptions): Task;
```

## install

```ts
install(options?: InstallOptions): Task[];
```

## list

```ts
list(): string[];
```

## get

```ts
get(name?: string): BaseManager;
```

## runScript

```ts
runScript(scriptName: string, { ignoreError, ...opts }?: {
     ignoreError?: boolean;
 } & ManagerCmdOpts & Record<string, any>): import("rxjs").Observable<unknown>;
```
