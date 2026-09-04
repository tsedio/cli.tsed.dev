---
title: CliDockerComposeYaml from @tsed/cli-core
description: api documentation of CliDockerComposeYaml from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CliDockerComposeYaml class
---
# CliDockerComposeYaml - @tsed/cli-core

## Usage

```typescript
import { CliDockerComposeYaml } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliDockerComposeYaml.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliDockerComposeYaml.ts#L0-L0).

## Overview

```ts
class CliDockerComposeYaml {
    protected cliYaml: CliYaml;
    protected fs: CliFs;
    protected projectPackageJson: ProjectPackageJson;
    read(): Promise<unknown>;
    write(obj: any): Promise<void>;
    addDatabaseService(name: string, database: CliDatabases | undefined): Promise<void>;
}
```

<!-- Members -->

## protected cliYaml

```ts
protected cliYaml: CliYaml;
```

## protected fs

```ts
protected fs: CliFs;
```

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## read

```ts
read(): Promise<unknown>;
```

## write

```ts
write(obj: any): Promise<void>;
```

## addDatabaseService

```ts
addDatabaseService(name: string, database: CliDatabases | undefined): Promise<void>;
```
