---
url: /api/cli-core/types/packageManagers/supports/class-p-npm-manager.md
description: api documentation of PNpmManager from @tsed/cli-core
---

## Usage

```typescript
import { PNpmManager } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/packageManagers/supports/PNpmManager.ts](https://github.com/tsedio/tsed-cli/blob/v7.9.1/packages/cli-core/src/packageManagers/supports/PNpmManager.ts#L0-L0).

## Overview

```ts
class PNpmManager extends BaseManager {
    readonly name = "pnpm";
    readonly cmd = "pnpm";
    protected cliYaml: CliYaml;
    protected fs: CliFs;
    init(options: ManagerCmdOpts): Promise<void>;
    add(deps: string[], options: ManagerCmdOpts): Observable<any>;
    addDev(deps: string[], options: ManagerCmdOpts): Observable<any>;
    install(options: ManagerCmdOpts): Observable<any>;
    protected getMajorVersion(options: ManagerCmdOpts): number | undefined;
}
```

## readonly name

```ts
readonly name = "pnpm";
```

## readonly cmd

```ts
readonly cmd = "pnpm";
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

## protected getMajorVersion

```ts
protected getMajorVersion(options: ManagerCmdOpts): number | undefined;
```
