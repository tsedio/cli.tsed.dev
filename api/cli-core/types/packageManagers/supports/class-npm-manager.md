---
url: /api/cli-core/types/packageManagers/supports/class-npm-manager.md
description: api documentation of NpmManager from @tsed/cli-core
---

## Usage

```typescript
import { NpmManager } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/packageManagers/supports/NpmManager.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/packageManagers/supports/NpmManager.ts#L0-L0).

## Overview

```ts
class NpmManager extends BaseManager {
    readonly name: string;
    readonly cmd: string;
    add(deps: string[], options: ManagerCmdOpts): Observable<any>;
    addDev(deps: string[], options: ManagerCmdOpts): Observable<any>;
    install(options: ManagerCmdOpts): Observable<any>;
}
```

## readonly name

```ts
readonly name: string;
```

## readonly cmd

```ts
readonly cmd: string;
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
