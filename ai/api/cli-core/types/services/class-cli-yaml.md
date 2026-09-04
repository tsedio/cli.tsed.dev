---
title: CliYaml from @tsed/cli-core
description: api documentation of CliYaml from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CliYaml class
---
# CliYaml - @tsed/cli-core

## Usage

```typescript
import { CliYaml } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliYaml.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliYaml.ts#L0-L0).

## Overview

```ts
class CliYaml {
    protected fs: CliFs;
    read(path: string): Promise<unknown>;
    write(path: string, obj: any): Promise<void>;
}
```

<!-- Members -->

## protected fs

```ts
protected fs: CliFs;
```

## read

```ts
read(path: string): Promise<unknown>;
```

## write

```ts
write(path: string, obj: any): Promise<void>;
```
