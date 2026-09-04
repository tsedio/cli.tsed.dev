---
title: BabelRuntime from @tsed/cli
description: api documentation of BabelRuntime from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation BabelRuntime class
---
# BabelRuntime - @tsed/cli

## Usage

```typescript
import { BabelRuntime } from "@tsed/cli";
```

> See [/packages/cli/src/runtimes/supports/BabelRuntime.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/runtimes/supports/BabelRuntime.ts#L0-L0).

## Overview

```ts
class BabelRuntime extends NodeRuntime {
    readonly name: string;
    readonly order: number;
    isCompiled(): boolean;
    files(): string[];
    startDev(main: string): string;
    startProd(args: string): string;
    compile(src: string, out: string): string;
    devDependencies(): {
        "@babel/cli": string;
        "@babel/core": string;
        "@babel/node": string;
        "@babel/plugin-proposal-class-properties": string;
        "@babel/plugin-proposal-decorators": string;
        "@babel/preset-env": string;
        "@babel/preset-typescript": string;
        "@babel/plugin-proposal-object-rest-spread": string;
        "babel-plugin-transform-typescript-metadata": string;
        "babel-watch": string;
        typescript: string;
    };
}
```

<!-- Members -->

## readonly name

```ts
readonly name: string;
```

## readonly order

```ts
readonly order: number;
```

## isCompiled

```ts
isCompiled(): boolean;
```

## files

```ts
files(): string[];
```

## startDev

```ts
startDev(main: string): string;
```

## startProd

```ts
startProd(args: string): string;
```

## compile

```ts
compile(src: string, out: string): string;
```

## devDependencies

```ts
devDependencies(): {
     "@babel/cli": string;
     "@babel/core": string;
     "@babel/node": string;
     "@babel/plugin-proposal-class-properties": string;
     "@babel/plugin-proposal-decorators": string;
     "@babel/preset-env": string;
     "@babel/preset-typescript": string;
     "@babel/plugin-proposal-object-rest-spread": string;
     "babel-plugin-transform-typescript-metadata": string;
     "babel-watch": string;
     typescript: string;
 };
```
