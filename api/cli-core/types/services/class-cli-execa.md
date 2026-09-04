---
url: /api/cli-core/types/services/class-cli-execa.md
description: api documentation of CliExeca from @tsed/cli-core
---

## Usage

```typescript
import { CliExeca } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliExeca.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliExeca.ts#L0-L0).

## Overview

```ts
class CliExeca {
    readonly raw: typeof execa;
    readonly rawSync: typeof execaSync;
    run(cmd: string, args: string[], opts?: Options): import("rxjs").Observable<any>;
    runSync(cmd: string, args: string[], opts?: SyncOptions): import("execa").ExecaReturnBase<string>;
    getAsync(cmd: string, args: readonly string[], opts?: Options): Promise<string>;
    get(cmd: string, args: string[], opts?: SyncOptions): string;
}
```

## readonly raw

```ts
readonly raw: typeof execa;
```

## readonly rawSync

```ts
readonly rawSync: typeof execaSync;
```

## run

```ts
run(cmd: string, args: string[], opts?: Options): import("rxjs").Observable<any>;
```

## runSync

```ts
runSync(cmd: string, args: string[], opts?: SyncOptions): import("execa").ExecaReturnBase<string>;
```

## getAsync

```ts
getAsync(cmd: string, args: readonly string[], opts?: Options): Promise<string>;
```

## get

```ts
get(cmd: string, args: string[], opts?: SyncOptions): string;
```
