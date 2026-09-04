---
url: /api/cli/types/platforms/supports/class-init-express-platform.md
description: api documentation of InitExpressPlatform from @tsed/cli
---

## Usage

```typescript
import { InitExpressPlatform } from "@tsed/cli/src/platforms/supports/InitExpressPlatform";
```

> See [/packages/cli/src/platforms/supports/InitExpressPlatform.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/platforms/supports/InitExpressPlatform.ts#L0-L0).

## Overview

```ts
class InitExpressPlatform implements InitBasePlatform {
    readonly name = "express";
    alterProjectFiles(project: ProjectClient): void;
    dependencies(ctx: any): {
        "@tsed/platform-express": any;
        "body-parser": string;
        cors: string;
        compression: string;
        "cookie-parser": string;
        express: string;
        "method-override": string;
    };
    devDependencies(): {
        "@types/cors": string;
        "@types/express": string;
        "@types/compression": string;
        "@types/cookie-parser": string;
        "@types/method-override": string;
    };
}
```

## readonly name

```ts
readonly name = "express";
```

## alterProjectFiles

```ts
alterProjectFiles(project: ProjectClient): void;
```

## dependencies

```ts
dependencies(ctx: any): {
     "@tsed/platform-express": any;
     "body-parser": string;
     cors: string;
     compression: string;
     "cookie-parser": string;
     express: string;
     "method-override": string;
 };
```

## devDependencies

```ts
devDependencies(): {
     "@types/cors": string;
     "@types/express": string;
     "@types/compression": string;
     "@types/cookie-parser": string;
     "@types/method-override": string;
 };
```
