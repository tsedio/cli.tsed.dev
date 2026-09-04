---
title: PackageJson from @tsed/cli-core
description: api documentation of PackageJson from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation PackageJson interface
---
# PackageJson - @tsed/cli-core

## Usage

```typescript
import { PackageJson } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/interfaces/PackageJson.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/interfaces/PackageJson.ts#L0-L0).

## Overview

```ts
interface PackageJson {
    name: string;
    version: string;
    description: string;
    type: "module";
    scripts: {
        [key: string]: string;
    };
    dependencies: {
        [key: string]: string;
    };
    devDependencies: {
        [key: string]: string;
    };
    [key: string]: any;
}
```

<!-- Members -->

## name

```ts
name: string;
```

## version

```ts
version: string;
```

## description

```ts
description: string;
```

## type

```ts
type: "module";
```

## scripts

```ts
scripts: {
     [key: string]: string;
 };
```

## dependencies

```ts
dependencies: {
     [key: string]: string;
 };
```

## devDependencies

```ts
devDependencies: {
     [key: string]: string;
 };
```

## \[key: string]

```ts
[key: string]: any;
```
