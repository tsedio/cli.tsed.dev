---
title: YarnBerryManager from @tsed/cli-core
description: api documentation of YarnBerryManager from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation YarnBerryManager class
---
# YarnBerryManager - @tsed/cli-core

## Usage

```typescript
import { YarnBerryManager } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/packageManagers/supports/YarnBerryManager.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/packageManagers/supports/YarnBerryManager.ts#L0-L0).

## Overview

```ts
class YarnBerryManager extends BaseManager {
    readonly name = "yarn_berry";
    readonly cmd = "yarn";
    protected verboseOpt: string;
    protected cliYaml: CliYaml;
    protected fs: CliFs;
    init(options: ManagerCmdOpts): Promise<void>;
    add(deps: string[], options: ManagerCmdOpts): Observable<any>;
    addDev(deps: string[], options: ManagerCmdOpts): Observable<any>;
    install(options: ManagerCmdOpts): Observable<any>;
}
```

<!-- Members -->

## readonly name

```ts
readonly name = "yarn_berry";
```

## readonly cmd

```ts
readonly cmd = "yarn";
```

## protected verboseOpt

```ts
protected verboseOpt: string;
```

## protected cliYaml

```ts
protected cliYaml: CliYaml;
```

## protected fs

```ts
protected fs: CliFs;
```

## init

```ts
init(options: ManagerCmdOpts): Promise<void>;
```

## add

```ts
add(deps: string[], options: ManagerCmdOpts): Observable<any>;
```

## addDev

```ts
addDev(deps: string[], options: ManagerCmdOpts): Observable<any>;
```

## install

```ts
install(options: ManagerCmdOpts): Observable<any>;
```
