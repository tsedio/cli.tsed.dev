---
url: /api/cli-core/types/interfaces/interface-command-arg.md
description: api documentation of CommandArg from @tsed/cli-core
---

## Usage

```typescript
import { CommandArg } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/interfaces/CommandOptions.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/interfaces/CommandOptions.ts#L0-L0).

## Overview

```ts
interface CommandArg {
    description: string;
    type?: Type<any>;
    itemType?: Type<any>;
    defaultValue?: string | number | boolean | any;
    required?: boolean;
}
```

## description

```ts
description: string;
```

Description of the argument

## type

```ts
type?: Type<any>;
```

Use type to parse the option (String, Number, Boolean, Array)

## itemType

```ts
itemType?: Type<any>;
```

Use item type to parse items

## defaultValue

```ts
defaultValue?: string | number | boolean | any;
```

Default value

## required

```ts
required?: boolean;
```

Define a require option
