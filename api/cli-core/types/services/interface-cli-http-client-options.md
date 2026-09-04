---
url: /api/cli-core/types/services/interface-cli-http-client-options.md
description: api documentation of CliHttpClientOptions from @tsed/cli-core
---

## Usage

```typescript
import { CliHttpClientOptions } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliHttpClient.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliHttpClient.ts#L0-L0).

## Overview

```ts
interface CliHttpClientOptions extends AxiosRequestConfig, Record<string, unknown> {
    qs?: Record<string, unknown>;
    withHeaders?: boolean;
}
```

## qs

```ts
qs?: Record<string, unknown>;
```

## withHeaders

```ts
withHeaders?: boolean;
```
