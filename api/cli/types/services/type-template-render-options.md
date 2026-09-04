---
url: /api/cli/types/services/type-template-render-options.md
description: api documentation of TemplateRenderOptions from @tsed/cli
---

## Usage

```typescript
import { TemplateRenderOptions } from "@tsed/cli/src/services/CliTemplatesService";
```

> See [/packages/cli/src/services/CliTemplatesService.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/services/CliTemplatesService.ts#L0-L0).

## Overview

```ts
type TemplateRenderOptions = {
    name?: string;
    symbolName?: string;
    symbolPath?: string;
    directory?: string;
    from?: string;
} & Partial<RenderDataContext>;
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

## directory

```ts
directory?: string;
```

## from

```ts
from?: string;
```
