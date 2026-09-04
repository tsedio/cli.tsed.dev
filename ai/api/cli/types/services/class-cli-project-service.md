---
title: CliProjectService from @tsed/cli
description: api documentation of CliProjectService from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation CliProjectService class
---
# CliProjectService - @tsed/cli

## Usage

```typescript
import { CliProjectService } from "@tsed/cli";
```

> See [/packages/cli/src/services/CliProjectService.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/services/CliProjectService.ts#L0-L0).

## Overview

```ts
class CliProjectService {
    readonly templates: CliTemplatesService;
    get rootDir(): string;
    get srcDir(): string;
    getRelativePath(path: string): string;
    getServerFileName(): "server" | "Server";
    create(): void;
    get(): ProjectClient;
    transformFiles(data: RenderDataContext): Promise<void>;
    createFromTemplate(templateId: string, data: TemplateRenderOptions): Promise<TemplateRenderReturnType | undefined>;
    getDirectories(dir: string): string[];
}
```

<!-- Members -->

## readonly templates

```ts
readonly templates: CliTemplatesService;
```

## get rootDir

```ts
get rootDir(): string;
```

## get srcDir

```ts
get srcDir(): string;
```

## getRelativePath

```ts
getRelativePath(path: string): string;
```

## getServerFileName

```ts
getServerFileName(): "server" | "Server";
```

## create

```ts
create(): void;
```

## get

```ts
get(): ProjectClient;
```

## transformFiles

```ts
transformFiles(data: RenderDataContext): Promise<void>;
```

## createFromTemplate

```ts
createFromTemplate(templateId: string, data: TemplateRenderOptions): Promise<TemplateRenderReturnType | undefined>;
```

## getDirectories

```ts
getDirectories(dir: string): string[];
```
