---
title: CliHttpClient from @tsed/cli-core
description: api documentation of CliHttpClient from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CliHttpClient class
---
# CliHttpClient - @tsed/cli-core

## Usage

```typescript
import { CliHttpClient } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliHttpClient.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliHttpClient.ts#L0-L0).

## Overview

```ts
class CliHttpClient extends CliHttpLogClient {
    protected cliProxyAgent: CliProxyAgent;
    protected host?: string;
    
    static getParamsSerializer(params: any): string;
    head<T = Record<string, any>>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
    get<T = unknown>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
    post<T = unknown>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
    put<T = any>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
    patch<T = any>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
    delete<T = any>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
    protected getRequestParameters(method: Method, endpoint: string, options: CliHttpClientOptions): Promise<CliHttpClientOptions>;
    protected configureProxy(endpoint: string, options: CliHttpClientOptions): Promise<void>;
    protected send(options: AxiosRequestConfig): Promise<import("axios").AxiosResponse<any, any, {}>>;
    protected mapResponse(result: any, options: CliHttpClientOptions): any;
}
```

<!-- Members -->

## protected cliProxyAgent

```ts
protected cliProxyAgent: CliProxyAgent;
```

## protected host

```ts
protected host?: string;
```

## static getParamsSerializer

```ts
static getParamsSerializer(params: any): string;
```

## head

```ts
head<T = Record<string, any>>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
```

## get

```ts
get<T = unknown>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
```

## post

```ts
post<T = unknown>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
```

## put

```ts
put<T = any>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
```

## patch

```ts
patch<T = any>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
```

## delete

```ts
delete<T = any>(endpoint: string, options?: CliHttpClientOptions): Promise<T>;
```

## protected getRequestParameters

```ts
protected getRequestParameters(method: Method, endpoint: string, options: CliHttpClientOptions): Promise<CliHttpClientOptions>;
```

## protected configureProxy

```ts
protected configureProxy(endpoint: string, options: CliHttpClientOptions): Promise<void>;
```

## protected send

```ts
protected send(options: AxiosRequestConfig): Promise<import("axios").AxiosResponse<any, any, {}>>;
```

## protected mapResponse

```ts
protected mapResponse(result: any, options: CliHttpClientOptions): any;
```
