---
title: GenerateHttpClientOpts from @tsed/cli-generate-http-client
description: api documentation of GenerateHttpClientOpts from @tsed/cli-generate-http-client
meta:
 - name: keywords
   description: api typescript node.js documentation GenerateHttpClientOpts interface
---
# GenerateHttpClientOpts - @tsed/cli-generate-http-client

## Usage

```typescript
import { GenerateHttpClientOpts } from "@tsed/cli-generate-http-client";
```

> See [/packages/cli-generate-http-client/src/commands/GenerateHttpClientCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-generate-http-client/src/commands/GenerateHttpClientCmd.ts#L0-L0).

## Overview

```ts
interface GenerateHttpClientOpts {
    hooks?: Partial<Hooks>;
    transformOperationId?(operationId: string, routeNameInfo: RouteNameInfo, raw: RawRouteInfo): string;
}
```

<!-- Members -->

## hooks

```ts
hooks?: Partial<Hooks>;
```

## transformOperationId

```ts
transformOperationId?(operationId: string, routeNameInfo: RouteNameInfo, raw: RawRouteInfo): string;
```
