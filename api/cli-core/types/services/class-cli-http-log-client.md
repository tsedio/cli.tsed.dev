---
url: /api/cli-core/types/services/class-cli-http-log-client.md
description: api documentation of CliHttpLogClient from @tsed/cli-core
---

## Usage

```typescript
import { CliHttpLogClient } from "@tsed/cli-core/src/services/CliHttpLogClient";
```

> See [/packages/cli-core/src/services/CliHttpLogClient.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliHttpLogClient.ts#L0-L0).

## Overview

```ts
class CliHttpLogClient {
    callee: string;
    protected logger: Logger;
    constructor(options?: Partial<BaseLogClientOptions>);
    protected onSuccess(options: Record<string, unknown>): void;
    protected onError(error: any, options: any): void;
    protected logToCurl(options: any): string;
    protected getStatusCodeFromError(error: any): any;
    protected getHeadersFromError(error: any): any;
    protected getResponseBodyFromError(error: any): any;
    protected formatLog(options: Record<string, any>): {
        callee: string;
        url: any;
        method: any;
        callee_qs: any;
        duration: number | undefined;
    };
    protected errorMapper(error: Error): {
        message: any;
        code: any;
        headers: any;
        body: any;
        x_request_id: any;
    };
}
```

## callee

```ts
callee: string;
```

## protected logger

```ts
protected logger: Logger;
```

## protected onSuccess

```ts
protected onSuccess(options: Record<string, unknown>): void;
```

## protected onError

```ts
protected onError(error: any, options: any): void;
```

## protected logToCurl

```ts
protected logToCurl(options: any): string;
```

## protected getStatusCodeFromError

```ts
protected getStatusCodeFromError(error: any): any;
```

## protected getHeadersFromError

```ts
protected getHeadersFromError(error: any): any;
```

## protected getResponseBodyFromError

```ts
protected getResponseBodyFromError(error: any): any;
```

## protected formatLog

```ts
protected formatLog(options: Record<string, any>): {
     callee: string;
     url: any;
     method: any;
     callee_qs: any;
     duration: number | undefined;
 };
```

## protected errorMapper

```ts
protected errorMapper(error: Error): {
     message: any;
     code: any;
     headers: any;
     body: any;
     x_request_id: any;
 };
```
