---
title: InitBasePlatform from @tsed/cli
description: api documentation of InitBasePlatform from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation InitBasePlatform interface
---
# InitBasePlatform - @tsed/cli

## Usage

```typescript
import { InitBasePlatform } from "@tsed/cli";
```

> See [/packages/cli/src/platforms/supports/InitBasePlatform.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/platforms/supports/InitBasePlatform.ts#L0-L0).

## Overview

```ts
interface InitBasePlatform {
    readonly name: string;
    alterProjectFiles(project: ProjectClient, ctx: RenderDataContext): void;
    dependencies(ctx: any): Record<string, string>;
    devDependencies(ctx: any): Record<string, string>;
}
```

<!-- Members -->

## readonly name

```ts
readonly name: string;
```

## alterProjectFiles

```ts
alterProjectFiles(project: ProjectClient, ctx: RenderDataContext): void;
```

## dependencies

```ts
dependencies(ctx: any): Record<string, string>;
```

## devDependencies

```ts
devDependencies(ctx: any): Record<string, string>;
```
