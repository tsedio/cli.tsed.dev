---
title: PackageInfo from @tsed/cli-core
description: api documentation of PackageInfo from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation PackageInfo interface
---
# PackageInfo - @tsed/cli-core

## Usage

```typescript
import { PackageInfo } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/interfaces/PackageJson.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/interfaces/PackageJson.ts#L0-L0).

## Overview

```ts
interface PackageInfo {
    _id: string;
    _rev: string;
    name: string;
    type: "module";
    "dist-tags": {
        [key: string]: string;
    };
    versions: {
        [key: string]: PackageJson;
    };
    time: {
        [key: string]: string;
    };
    maintainers: {
        email: string;
        name: string;
    }[];
    description: string;
    homepage: string;
    keywords: string[];
    repository: {
        type: string;
        url: string;
    };
    author: {
        name: string;
    };
    bugs: {
        url: string;
    };
    license: string;
    readme: string;
}
```

<!-- Members -->

## \_id

```ts
_id: string;
```

## \_rev

```ts
_rev: string;
```

## name

```ts
name: string;
```

## type

```ts
type: "module";
```

## "dist-tags"

```ts
"dist-tags": {
     [key: string]: string;
 };
```

## versions

```ts
versions: {
     [key: string]: PackageJson;
 };
```

## time

```ts
time: {
     [key: string]: string;
 };
```

## maintainers

```ts
maintainers: {
     email: string;
     name: string;
 }[];
```

## description

```ts
description: string;
```

## homepage

```ts
homepage: string;
```

## keywords

```ts
keywords: string[];
```

## repository

```ts
repository: {
     type: string;
     url: string;
 };
```

## author

```ts
author: {
     name: string;
 };
```

## bugs

```ts
bugs: {
     url: string;
 };
```

## license

```ts
license: string;
```

## readme

```ts
readme: string;
```
