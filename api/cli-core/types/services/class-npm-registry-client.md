---
url: /api/cli-core/types/services/class-npm-registry-client.md
description: api documentation of NpmRegistryClient from @tsed/cli-core
---

## Usage

```typescript
import { NpmRegistryClient } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/NpmRegistryClient.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/NpmRegistryClient.ts#L0-L0).

## Overview

```ts
class NpmRegistryClient {
    
    static escapeName(name: string): string;
    request(pathname: string, opts?: any): Promise<any>;
    getRequestUrl(registry: string, pathname: string): string;
    search(text: string, options?: {
        size?: number;
        from?: number;
        quality?: number;
        popularity?: number;
        maintenance?: number;
    }): Promise<any>;
    info(packageName: string, retry?: number): Promise<PackageInfo | null>;
    
}
```

## static escapeName

```ts
static escapeName(name: string): string;
```

## request

```ts
request(pathname: string, opts?: any): Promise<any>;
```

## getRequestUrl

```ts
getRequestUrl(registry: string, pathname: string): string;
```

## search

```ts
search(text: string, options?: {
     size?: number;
     from?: number;
     quality?: number;
     popularity?: number;
     maintenance?: number;
 }): Promise<any>;
```

Search a module on npm registry

## info

```ts
info(packageName: string, retry?: number): Promise<PackageInfo | null>;
```
