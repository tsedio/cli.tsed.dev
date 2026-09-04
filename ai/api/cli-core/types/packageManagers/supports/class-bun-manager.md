---
title: BunManager from @tsed/cli-core
description: api documentation of BunManager from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation BunManager class
---
# BunManager - @tsed/cli-core

## Usage

```typescript
import { BunManager } from "@tsed/cli-core/src/packageManagers/supports/BunManager";
```

> See [/packages/cli-core/src/packageManagers/supports/BunManager.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/packageManagers/supports/BunManager.ts#L0-L0).

## Overview

```ts
class BunManager extends BaseManager {
    readonly name = "bun";
    readonly cmd = "bun";
    add(deps: string[], options: ManagerCmdOpts): Observable<any>;
    addDev(deps: string[], options: ManagerCmdOpts): Observable<any>;
    install(options: {
        verbose?: boolean;
    } & Options): Observable<any>;
}
```

<!-- Members -->

## readonly name

```ts
readonly name = "bun";
```

## readonly cmd

```ts
readonly cmd = "bun";
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
install(options: {
     verbose?: boolean;
 } & Options): Observable<any>;
```
