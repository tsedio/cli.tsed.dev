---
url: /api/cli/types/services/type-template-render-return-type.md
description: api documentation of TemplateRenderReturnType from @tsed/cli
---

## Usage

```typescript
import { TemplateRenderReturnType } from "@tsed/cli/src/services/CliTemplatesService";
```

> See [/packages/cli/src/services/CliTemplatesService.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/services/CliTemplatesService.ts#L0-L0).

## Overview

```ts
type TemplateRenderReturnType = {
    templateId: string;
    content: string;
    outputPath: string;
    name?: string;
    symbolName?: string;
    symbolPath?: string;
    symbolPathBasename?: string;
    source?: SourceFile;
};
```

## templateId

```ts
templateId: string;
```

## content

```ts
content: string;
```

## outputPath

```ts
outputPath: string;
```

## name

```ts
name?: string;
```

## symbolName

```ts
symbolName?: string;
```

## symbolPath

```ts
symbolPath?: string;
```

## symbolPathBasename

```ts
symbolPathBasename?: string;
```

## source

```ts
source?: SourceFile;
```
