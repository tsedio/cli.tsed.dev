---
url: /api/cli/types/utils/function-summarize-schema.md
description: api documentation of summarizeSchema from @tsed/cli
---

## Usage

```typescript
import { summarizeSchema } from "@tsed/cli/src/utils/summarizeSchema";
```

> See [/packages/cli/src/utils/summarizeSchema.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/utils/summarizeSchema.ts#L0-L0).

## Overview

```ts
const summarizeSchema: (tpl: DefineTemplateOptions) => {
    required?: undefined;
    properties?: undefined;
} | {
    required: any;
    properties: Record<string, any> | undefined;
} | undefined;
```

## required

```ts
required?: undefined;
```

## properties

```ts
properties?: undefined;
```

##

```ts
} | {
```

## required

```ts
required: any;
```

## properties

```ts
properties: Record<string, any> | undefined;
```
