---
title: GenerateHttpClientCtx from @tsed/cli-generate-http-client
description: api documentation of GenerateHttpClientCtx from @tsed/cli-generate-http-client
meta:
 - name: keywords
   description: api typescript node.js documentation GenerateHttpClientCtx interface
---
# GenerateHttpClientCtx - @tsed/cli-generate-http-client

## Usage

```typescript
import { GenerateHttpClientCtx } from "@tsed/cli-generate-http-client";
```

> See [/packages/cli-generate-http-client/src/commands/GenerateHttpClientCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-generate-http-client/src/commands/GenerateHttpClientCmd.ts#L0-L0).

## Overview

```ts
interface GenerateHttpClientCtx {
    output: string;
    type: "axios" | "fetch";
    name: string;
    suffix: string;
}
```

<!-- Members -->

## output

```ts
output: string;
```

## type

```ts
type: "axios" | "fetch";
```

## name

```ts
name: string;
```

## suffix

```ts
suffix: string;
```
