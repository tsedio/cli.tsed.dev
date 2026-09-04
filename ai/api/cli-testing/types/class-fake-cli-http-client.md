---
title: FakeCliHttpClient from @tsed/cli-testing
description: api documentation of FakeCliHttpClient from @tsed/cli-testing
meta:
 - name: keywords
   description: api typescript node.js documentation FakeCliHttpClient class
---
# FakeCliHttpClient - @tsed/cli-testing

## Usage

```typescript
import { FakeCliHttpClient } from "@tsed/cli-testing";
```

> See [/packages/cli-testing/src/FakeCliHttpClient.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-testing/src/FakeCliHttpClient.ts#L0-L0).

## Overview

```ts
class FakeCliHttpClient extends CliHttpClient {
    static entries: Map<string, (endpoint: string, options: CliHttpClientOptions) => any>;
    get(endpoint: string, options?: CliHttpClientOptions): Promise<any>;
}
```

<!-- Members -->

## static entries: Map

```ts
static entries: Map<string, (endpoint: string, options: CliHttpClientOptions) => any>;
```

## get

```ts
get(endpoint: string, options?: CliHttpClientOptions): Promise<any>;
```
