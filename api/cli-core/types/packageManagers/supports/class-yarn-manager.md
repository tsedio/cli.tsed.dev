---
url: /api/cli-core/types/packageManagers/supports/class-yarn-manager.md
description: api documentation of YarnManager from @tsed/cli-core
---

## Usage

```typescript
import { YarnManager } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/packageManagers/supports/YarnManager.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/packageManagers/supports/YarnManager.ts#L0-L0).

## Overview

```ts
class YarnManager extends BaseManager {
    readonly name = "yarn";
    readonly cmd = "yarn";
    add(deps: string[], options: ManagerCmdOpts): Observable<any>;
    addDev(deps: string[], options: ManagerCmdOpts): Observable<any>;
    install(options: {
        verbose?: boolean;
    } & Options): Observable<any>;
}
```

## readonly name

```ts
readonly name = "yarn";
```

## readonly cmd

```ts
readonly cmd = "yarn";
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
