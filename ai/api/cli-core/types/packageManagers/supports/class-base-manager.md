---
title: BaseManager from @tsed/cli-core
description: api documentation of BaseManager from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation BaseManager class
---
# BaseManager - @tsed/cli-core

## Usage

```typescript
import { BaseManager } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/packageManagers/supports/BaseManager.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/packageManagers/supports/BaseManager.ts#L0-L0).

## Overview

```ts
abstract class BaseManager {
    abstract readonly name: string;
    abstract readonly cmd: string;
    protected verboseOpt: string;
    protected cliExeca: CliExeca;
    has(): boolean;
    init(_: ManagerCmdOpts): Promise<void>;
    abstract install(options: ManagerCmdOpts): Observable<any>;
    abstract add(deps: string[], options: ManagerCmdOpts): Observable<any>;
    abstract addDev(deps: string[], options: ManagerCmdOpts): Observable<any>;
    runScript(script: string, options: ManagerCmdOpts): Observable<any>;
    run(cmd: string, args: any[], options: ManagerCmdOpts): Observable<any>;
}
```

<!-- Members -->

## abstract readonly name

```ts
abstract readonly name: string;
```

## abstract readonly cmd

```ts
abstract readonly cmd: string;
```

## protected verboseOpt

```ts
protected verboseOpt: string;
```

## protected cliExeca

```ts
protected cliExeca: CliExeca;
```

## has

```ts
has(): boolean;
```

## init

```ts
init(_: ManagerCmdOpts): Promise<void>;
```

## abstract install

```ts
abstract install(options: ManagerCmdOpts): Observable<any>;
```

## abstract add

```ts
abstract add(deps: string[], options: ManagerCmdOpts): Observable<any>;
```

## abstract addDev

```ts
abstract addDev(deps: string[], options: ManagerCmdOpts): Observable<any>;
```

## runScript

```ts
runScript(script: string, options: ManagerCmdOpts): Observable<any>;
```

## run

```ts
run(cmd: string, args: any[], options: ManagerCmdOpts): Observable<any>;
```
