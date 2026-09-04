---
url: /api/cli-core/types/services/class-cli-proxy-agent.md
description: api documentation of CliProxyAgent from @tsed/cli-core
---

## Usage

```typescript
import { CliProxyAgent } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliProxyAgent.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliProxyAgent.ts#L0-L0).

## Overview

```ts
class CliProxyAgent {
    readonly proxySettings: {
        value: CliProxySettings;
    };
    protected projectPackageJson: ProjectPackageJson;
    protected cliExeca: CliExeca;
    hasProxy(): boolean;
    get(type: "http" | "https"): Promise<any>;
    resolveProxySettings(): Promise<void>;
}
```

## readonly proxySettings

```ts
readonly proxySettings: {
     value: CliProxySettings;
 };
```

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## protected cliExeca

```ts
protected cliExeca: CliExeca;
```

## hasProxy

```ts
hasProxy(): boolean;
```

## get

```ts
get(type: "http" | "https"): Promise<any>;
```

## resolveProxySettings

```ts
resolveProxySettings(): Promise<void>;
```
