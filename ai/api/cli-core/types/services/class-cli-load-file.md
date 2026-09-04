---
title: CliLoadFile from @tsed/cli-core
description: api documentation of CliLoadFile from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CliLoadFile class
---
# CliLoadFile - @tsed/cli-core

## Usage

```typescript
import { CliLoadFile } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliLoadFile.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliLoadFile.ts#L0-L0).

## Overview

```ts
class CliLoadFile {
    protected cliYaml: CliYaml;
    protected cliFs: CliFs;
    loadFile<Model = any>(path: string, schema?: JsonSchema<Model>): Promise<Model>;
}
```

<!-- Members -->

## protected cliYaml

```ts
protected cliYaml: CliYaml;
```

## protected cliFs

```ts
protected cliFs: CliFs;
```

## loadFile

```ts
loadFile<Model = any>(path: string, schema?: JsonSchema<Model>): Promise<Model>;
```

Load a configuration file from yaml, json
