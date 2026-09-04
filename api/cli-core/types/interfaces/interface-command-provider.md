---
url: /api/cli-core/types/interfaces/interface-command-provider.md
description: api documentation of CommandProvider from @tsed/cli-core
---

## Usage

```typescript
import { CommandProvider } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/interfaces/CommandProvider.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/interfaces/CommandProvider.ts#L0-L0).

## Overview

```ts
interface CommandProvider<Ctx = any> {
    $prompt?(initialOptions: Partial<Ctx>): PromptQuestion[] | Promise<PromptQuestion[]>;
    $mapContext?(ctx: Partial<Ctx>): Ctx;
    $exec(ctx: Ctx): MaybePromise<Task<Ctx>[] | void>;
    $postInstall?(ctx: Ctx): MaybePromise<Task<Ctx>[] | void>;
    $afterPostInstall?(ctx: Ctx): MaybePromise<Task<Ctx>[] | void>;
}
```

## $prompt

```ts
$prompt?(initialOptions: Partial<Ctx>): PromptQuestion[] | Promise<PromptQuestion[]>;
```

Hook to create the main prompt for the command. Refer to {@link PromptQuestion}
for supported question attributes.

## $mapContext

```ts
$mapContext?(ctx: Partial<Ctx>): Ctx;
```

Hook to map options

## $exec

```ts
$exec(ctx: Ctx): MaybePromise<Task<Ctx>[] | void>;
```

Run a command

## $postInstall

```ts
$postInstall?(ctx: Ctx): MaybePromise<Task<Ctx>[] | void>;
```

Run commands after the npm/yarn install

## $afterPostInstall

```ts
$afterPostInstall?(ctx: Ctx): MaybePromise<Task<Ctx>[] | void>;
```
