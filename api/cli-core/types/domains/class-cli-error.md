---
url: /api/cli-core/types/domains/class-cli-error.md
description: api documentation of CliError from @tsed/cli-core
---

## Usage

```typescript
import { CliError } from "@tsed/cli-core/src/domains/CliError";
```

> See [/packages/cli-core/src/domains/CliError.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/domains/CliError.ts#L0-L0).

## Overview

```ts
class CliError extends Error {
    name: string;
    readonly cli: CliCore;
    readonly origin: Error;
    constructor({ cli, origin }: {
        cli: CliCore;
        origin: Error;
    });
}
```

## name

```ts
name: string;
```

## readonly cli

```ts
readonly cli: CliCore;
```

## readonly origin

```ts
readonly origin: Error;
```
