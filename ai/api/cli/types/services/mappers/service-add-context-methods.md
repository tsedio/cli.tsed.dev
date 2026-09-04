---
title: addContextMethods from @tsed/cli
description: api documentation of addContextMethods from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation addContextMethods service
---
# addContextMethods - @tsed/cli

## Usage

```typescript
import { addContextMethods } from "@tsed/cli/src/services/mappers/addContextMethods";
```

> See [/packages/cli/src/services/mappers/addContextMethods.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/services/mappers/addContextMethods.ts#L0-L0).

## Overview

```ts
function addContextMethods(context: GenerateCmdContext): {
    getName: (state?: {
        type?: string;
        name?: string;
    }) => string;
    getRoute: (state: string | {
        type?: string;
        name?: string;
    }) => string;
    getDirectories: (dir: string) => string[];
};
```

<!-- Members -->

## getName:

```ts
getName: (state?: {
     type?: string;
     name?: string;
 }) => string;
```

## getRoute:

```ts
getRoute: (state: string | {
     type?: string;
     name?: string;
 }) => string;
```

## getDirectories:

```ts
getDirectories: (dir: string) => string[];
```
