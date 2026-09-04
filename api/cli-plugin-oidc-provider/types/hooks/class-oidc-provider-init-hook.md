---
url: /api/cli-plugin-oidc-provider/types/hooks/class-oidc-provider-init-hook.md
description: api documentation of OidcProviderInitHook from @tsed/cli-plugin-oidc-provider
---

## Usage

```typescript
import { OidcProviderInitHook } from "@tsed/cli-plugin-oidc-provider";
```

> See [/packages/cli-plugin-oidc-provider/src/hooks/OidcProviderInitHook.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-plugin-oidc-provider/src/hooks/OidcProviderInitHook.ts#L0-L0).

## Overview

```ts
class OidcProviderInitHook implements CliCommandHooks {
    $alterBarrels(barrels: any): any;
    $alterRenderFiles(files: string[], data: RenderDataContext): (string | {
        id: string;
        from: string;
    })[];
    $alterProjectFiles(project: ProjectClient, data: RenderDataContext): Promise<ProjectClient>;
    
}
```

## $alterBarrels

```ts
$alterBarrels(barrels: any): any;
```

## $alterRenderFiles

```ts
$alterRenderFiles(files: string[], data: RenderDataContext): (string | {
     id: string;
     from: string;
 })[];
```

## $alterProjectFiles

```ts
$alterProjectFiles(project: ProjectClient, data: RenderDataContext): Promise<ProjectClient>;
```
