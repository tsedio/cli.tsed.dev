---
title: GenerateCmdContext from @tsed/cli
description: api documentation of GenerateCmdContext from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation GenerateCmdContext interface
---
# GenerateCmdContext - @tsed/cli

## Usage

```typescript
import { GenerateCmdContext } from "@tsed/cli";
```

> See [/packages/cli/src/interfaces/GenerateCmdContext.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/interfaces/GenerateCmdContext.ts#L0-L0).

## Overview

```ts
interface GenerateCmdContext extends RenderDataContext, TsED.GenerateOptions {
    type: string;
    name: string;
    route: string;
    directory: string;
    templateType: string;
    middlewarePosition: "before" | "after";
    symbolName: string;
    symbolPath: string;
    symbolPathBasename: string;
    getName: (state: Partial<GenerateCmdContext>) => string;
    getRoute: (state: Partial<GenerateCmdContext> | string) => string;
    getDirectories: (dir: string) => string[];
}
```

<!-- Members -->

## type

```ts
type: string;
```

## name

```ts
name: string;
```

## route

```ts
route: string;
```

## directory

```ts
directory: string;
```

## templateType

```ts
templateType: string;
```

## middlewarePosition

```ts
middlewarePosition: "before" | "after";
```

## symbolName

```ts
symbolName: string;
```

## symbolPath

```ts
symbolPath: string;
```

## symbolPathBasename

```ts
symbolPathBasename: string;
```

## getName:

```ts
getName: (state: Partial<GenerateCmdContext>) => string;
```

## getRoute:

```ts
getRoute: (state: Partial<GenerateCmdContext> | string) => string;
```

## getDirectories:

```ts
getDirectories: (dir: string) => string[];
```
