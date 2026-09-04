---
title: WebpackRuntime from @tsed/cli
description: api documentation of WebpackRuntime from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation WebpackRuntime class
---
# WebpackRuntime - @tsed/cli

## Usage

```typescript
import { WebpackRuntime } from "@tsed/cli";
```

> See [/packages/cli/src/runtimes/supports/WebpackRuntime.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/runtimes/supports/WebpackRuntime.ts#L0-L0).

## Overview

```ts
class WebpackRuntime extends BabelRuntime {
    readonly name = "webpack";
    readonly order: number;
    isCompiled(): boolean;
    files(): string[];
    compile(): string;
    startProd(main: string): string;
    devDependencies(): {
        typescript: string;
        "babel-loader": string;
        webpack: string;
        "webpack-cli": string;
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
    };
}
```

<!-- Members -->

## readonly name

```ts
readonly name = "webpack";
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

## compile

```ts
compile(): string;
```

## startProd

```ts
startProd(main: string): string;
```

## devDependencies

```ts
devDependencies(): {
     typescript: string;
     "babel-loader": string;
     webpack: string;
     "webpack-cli": string;
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
 };
```
