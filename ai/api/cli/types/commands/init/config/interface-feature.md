---
title: Feature from @tsed/cli
description: api documentation of Feature from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation Feature interface
---
# Feature - @tsed/cli

## Usage

```typescript
import { Feature } from "@tsed/cli";
```

> See [/packages/cli/src/commands/init/config/FeaturesPrompt.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/init/config/FeaturesPrompt.ts#L0-L0).

## Overview

```ts
interface Feature {
    name: string;
    value?: any;
    checked?: boolean | ((opts: Partial<InitOptions>) => boolean);
    when?: (opts: any) => boolean;
    dependencies?: Record<string, any>;
    devDependencies?: Record<string, any>;
}
```

<!-- Members -->

## name

```ts
name: string;
```

## value

```ts
value?: any;
```

## checked: boolean |

```ts
checked?: boolean | ((opts: Partial<InitOptions>) => boolean);
```

## when:

```ts
when?: (opts: any) => boolean;
```

## dependencies

```ts
dependencies?: Record<string, any>;
```

## devDependencies

```ts
devDependencies?: Record<string, any>;
```
