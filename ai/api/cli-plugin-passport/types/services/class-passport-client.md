---
title: PassportClient from @tsed/cli-plugin-passport
description: api documentation of PassportClient from @tsed/cli-plugin-passport
meta:
 - name: keywords
   description: api typescript node.js documentation PassportClient class
---
# PassportClient - @tsed/cli-plugin-passport

## Usage

```typescript
import { PassportClient } from "@tsed/cli-plugin-passport";
```

> See [/packages/cli-plugin-passport/src/services/PassportClient.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-passport/src/services/PassportClient.ts#L0-L0).

## Overview

```ts
class PassportClient {
    protected httpClient: CliHttpClient;
    getPackages(): Promise<PassportPackage[]>;
    getPackage(name: string): Promise<PassportPackage | undefined>;
    getPackageVersion(name: string): Promise<string>;
    getChoices(input?: string): Promise<{
        name: string;
        value: string;
    }[]>;
}
```

<!-- Members -->

## protected httpClient

```ts
protected httpClient: CliHttpClient;
```

## getPackages

```ts
getPackages(): Promise<PassportPackage[]>;
```

## getPackage

```ts
getPackage(name: string): Promise<PassportPackage | undefined>;
```

## getPackageVersion

```ts
getPackageVersion(name: string): Promise<string>;
```

## getChoices

```ts
getChoices(input?: string): Promise<{
     name: string;
     value: string;
 }[]>;
```
