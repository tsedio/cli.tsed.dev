---
title: InitKoaPlatform from @tsed/cli
description: api documentation of InitKoaPlatform from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation InitKoaPlatform class
---
# InitKoaPlatform - @tsed/cli

## Usage

```typescript
import { InitKoaPlatform } from "@tsed/cli/src/platforms/supports/InitKoaPlatform";
```

> See [/packages/cli/src/platforms/supports/InitKoaPlatform.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/platforms/supports/InitKoaPlatform.ts#L0-L0).

## Overview

```ts
class InitKoaPlatform implements InitBasePlatform {
    readonly name = "koa";
    alterProjectFiles(project: ProjectClient): void;
    dependencies(ctx: any): {
        "@tsed/platform-koa": any;
        koa: string;
        "@koa/cors": string;
        "@koa/router": string;
        "koa-qs": string;
        "koa-bodyparser": string;
        "koa-override": string;
        "koa-compress": string;
    };
    devDependencies(): {
        "@types/koa": string;
        "@types/koa-qs": string;
        "@types/koa-json": string;
        "@types/koa-bodyparser": string;
        "@types/koa__router": string;
        "@types/koa-compress": string;
        "@types/koa-send": string;
        "@types/koa__cors": string;
    };
}
```

<!-- Members -->

## readonly name

```ts
readonly name = "koa";
```

## alterProjectFiles

```ts
alterProjectFiles(project: ProjectClient): void;
```

## dependencies

```ts
dependencies(ctx: any): {
     "@tsed/platform-koa": any;
     koa: string;
     "@koa/cors": string;
     "@koa/router": string;
     "koa-qs": string;
     "koa-bodyparser": string;
     "koa-override": string;
     "koa-compress": string;
 };
```

## devDependencies

```ts
devDependencies(): {
     "@types/koa": string;
     "@types/koa-qs": string;
     "@types/koa-json": string;
     "@types/koa-bodyparser": string;
     "@types/koa__router": string;
     "@types/koa-compress": string;
     "@types/koa-send": string;
     "@types/koa__cors": string;
 };
```
