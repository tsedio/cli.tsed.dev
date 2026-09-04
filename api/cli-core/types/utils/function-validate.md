---
url: /api/cli-core/types/utils/function-validate.md
description: api documentation of validate from @tsed/cli-core
---

## Usage

```typescript
import { validate } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/utils/validate.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/utils/validate.ts#L0-L0).

## Overview

```ts
function validate<Value>(value: unknown, schema: JsonSchema<Value>): {
    isValid: boolean;
    errors: {
        path: string;
        message: string | undefined;
        expected: any;
    }[];
    value?: undefined;
} | {
    isValid: boolean;
    value: Value;
    errors?: undefined;
};
```

## isValid

```ts
isValid: boolean;
```

## errors

```ts
errors: {
     path: string;
     message: string | undefined;
     expected: any;
 }[];
```

## value

```ts
value?: undefined;
```

##

```ts
} | {
```

## isValid

```ts
isValid: boolean;
```

## value

```ts
value: Value;
```

## errors

```ts
errors?: undefined;
```
