---
title: CliStats from @tsed/cli
description: api documentation of CliStats from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation CliStats class
---
# CliStats - @tsed/cli

## Usage

```typescript
import { CliStats } from "@tsed/cli/src/services/CliStats";
```

> See [/packages/cli/src/services/CliStats.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/services/CliStats.ts#L0-L0).

## Overview

```ts
class CliStats extends CliHttpClient {
    protected disabled: boolean;
    protected host: string;
    protected projectPackage: ProjectPackageJson;
    sendInit(opts: Partial<InitStatPayload>): Promise<unknown> | undefined;
    $onFinish(data: {
        commandName?: string;
        features?: string[];
    }, er?: Error): Promise<unknown> | undefined;
    protected onSuccess(): void;
    protected onError(): void;
}
```

<!-- Members -->

## protected disabled

```ts
protected disabled: boolean;
```

## protected host

```ts
protected host: string;
```

## protected projectPackage

```ts
protected projectPackage: ProjectPackageJson;
```

## sendInit

```ts
sendInit(opts: Partial<InitStatPayload>): Promise<unknown> | undefined;
```

## $onFinish

```ts
$onFinish(data: {
     commandName?: string;
     features?: string[];
 }, er?: Error): Promise<unknown> | undefined;
```

## protected onSuccess

```ts
protected onSuccess(): void;
```

## protected onError

```ts
protected onError(): void;
```
