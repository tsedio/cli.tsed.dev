---
url: /api/cli-testing/types/class-fake-cli-execa.md
description: api documentation of FakeCliExeca from @tsed/cli-testing
---

## Usage

```typescript
import { FakeCliExeca } from "@tsed/cli-testing";
```

> See [/packages/cli-testing/src/FakeCliExeca.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-testing/src/FakeCliExeca.ts#L0-L0).

## Overview

```ts
class FakeCliExeca extends CliExeca {
    static entries: Map<string, string>;
    run(cmd: string, args: string[], _?: any): any;
    getAsync(cmd: string, args: string[], _?: any): Promise<any>;
    runSync(cmd: string, args: string[], _?: any): any;
}
```

## static entries

```ts
static entries: Map<string, string>;
```

## run

```ts
run(cmd: string, args: string[], _?: any): any;
```

## getAsync

```ts
getAsync(cmd: string, args: string[], _?: any): Promise<any>;
```

## runSync

```ts
runSync(cmd: string, args: string[], _?: any): any;
```
