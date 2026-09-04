---
url: /api/cli/types/platforms/supports/class-init-fastify-platform.md
description: api documentation of InitFastifyPlatform from @tsed/cli
---

## Usage

```typescript
import { InitFastifyPlatform } from "@tsed/cli/src/platforms/supports/InitFastifyPlatform";
```

> See [/packages/cli/src/platforms/supports/InitFastifyPlatform.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/platforms/supports/InitFastifyPlatform.ts#L0-L0).

## Overview

```ts
class InitFastifyPlatform implements InitBasePlatform {
    readonly name = "fastify";
    alterProjectFiles(project: ProjectClient): void;
    dependencies(ctx: any): {
        "@tsed/platform-fastify": any;
        "@fastify/accepts": string;
        "@fastify/middie": string;
        "@fastify/static": string;
        "@fastify/cookie": string;
        "@fastify/formbody": string;
        "@fastify/session": string;
        fastify: string;
        "fastify-raw-body": string;
    };
    devDependencies(): {
        "@types/content-disposition": string;
    };
}
```

## readonly name

```ts
readonly name = "fastify";
```

## alterProjectFiles

```ts
alterProjectFiles(project: ProjectClient): void;
```

## dependencies

```ts
dependencies(ctx: any): {
     "@tsed/platform-fastify": any;
     "@fastify/accepts": string;
     "@fastify/middie": string;
     "@fastify/static": string;
     "@fastify/cookie": string;
     "@fastify/formbody": string;
     "@fastify/session": string;
     fastify: string;
     "fastify-raw-body": string;
 };
```

## devDependencies

```ts
devDependencies(): {
     "@types/content-disposition": string;
 };
```
