---
title: PNpmManager from @tsed/cli-core
description: api documentation of PNpmManager from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation PNpmManager class
---
# PNpmManager - @tsed/cli-core

## Usage

```typescript
import { PNpmManager } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/packageManagers/supports/PNpmManager.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/packageManagers/supports/PNpmManager.ts#L0-L0).

## Overview

```ts
class PNpmManager extends BaseManager {
    readonly name = "pnpm";
    readonly cmd = "pnpm";
    add(deps: string[], options: ManagerCmdOpts): Observable<any>;
    addDev(deps: string[], options: ManagerCmdOpts): Observable<any>;
    install(options: ManagerCmdOpts): Observable<any>;
}
```

<!-- Members -->

## readonly name

```ts
readonly name = "pnpm";
```

## readonly cmd

```ts
readonly cmd = "pnpm";
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
