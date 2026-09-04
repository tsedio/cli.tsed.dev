---
title: FeaturesPrompt from @tsed/cli
description: api documentation of FeaturesPrompt from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation FeaturesPrompt function
---
# FeaturesPrompt - @tsed/cli

## Usage

```typescript
import { FeaturesPrompt } from "@tsed/cli";
```

> See [/packages/cli/src/commands/init/config/FeaturesPrompt.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/init/config/FeaturesPrompt.ts#L0-L0).

## Overview

```ts
const FeaturesPrompt: (availableRuntimes: string[], availablePackageManagers: string[]) => ({
    type: "checkbox";
    name: string;
    message: string;
    choices: FeatureType[];
    when?: undefined;
    source?: undefined;
    default?: undefined;
} | {
    type: "checkbox";
    message: string;
    name: string;
    when: (ctx: any) => boolean;
    choices: FeatureType[];
    source?: undefined;
    default?: undefined;
} | {
    type: "autocomplete";
    name: string;
    message: string;
    when: (ctx: any) => boolean;
    source(_: any): Promise<any[]>;
    choices?: undefined;
    default?: undefined;
} | {
    type: "password";
    name: string;
    message: string;
    when: (ctx: any) => boolean;
    choices?: undefined;
    source?: undefined;
    default?: undefined;
} | {
    message: string;
    name: string;
    default: string;
    when: (ctx: any) => boolean;
    type: "input";
    choices?: undefined;
    source?: undefined;
} | {
    message: string;
    type: "list";
    name: string;
    choices: string[];
    when?: undefined;
    source?: undefined;
    default?: undefined;
} | {
    message: string;
    type: "list";
    name: string;
    when: (ctx: any) => boolean;
    choices: string[];
    source?: undefined;
    default?: undefined;
})[];
```

<!-- Members -->

## type

```ts
type: "checkbox";
```

## name

```ts
name: string;
```

## message

```ts
message: string;
```

## choices

```ts
choices: FeatureType[];
```

## when

```ts
when?: undefined;
```

## source

```ts
source?: undefined;
```

## default

```ts
default?: undefined;
```

##

```ts
} | {
```

## type

```ts
type: "checkbox";
```

## message

```ts
message: string;
```

## name

```ts
name: string;
```

## when:

```ts
when: (ctx: any) => boolean;
```

## choices

```ts
choices: FeatureType[];
```

## source

```ts
source?: undefined;
```

## default

```ts
default?: undefined;
```

##

```ts
} | {
```

## type

```ts
type: "autocomplete";
```

## name

```ts
name: string;
```

## message

```ts
message: string;
```

## when:

```ts
when: (ctx: any) => boolean;
```

## source

```ts
source(_: any): Promise<any[]>;
```

## choices

```ts
choices?: undefined;
```

## default

```ts
default?: undefined;
```

##

```ts
} | {
```

## type

```ts
type: "password";
```

## name

```ts
name: string;
```

## message

```ts
message: string;
```

## when:

```ts
when: (ctx: any) => boolean;
```

## choices

```ts
choices?: undefined;
```

## source

```ts
source?: undefined;
```

## default

```ts
default?: undefined;
```

##

```ts
} | {
```

## message

```ts
message: string;
```

## name

```ts
name: string;
```

## default

```ts
default: string;
```

## when:

```ts
when: (ctx: any) => boolean;
```

## type

```ts
type: "input";
```

## choices

```ts
choices?: undefined;
```

## source

```ts
source?: undefined;
```

##

```ts
} | {
```

## message

```ts
message: string;
```

## type

```ts
type: "list";
```

## name

```ts
name: string;
```

## choices

```ts
choices: string[];
```

## when

```ts
when?: undefined;
```

## source

```ts
source?: undefined;
```

## default

```ts
default?: undefined;
```

##

```ts
} | {
```

## message

```ts
message: string;
```

## type

```ts
type: "list";
```

## name

```ts
name: string;
```

## when:

```ts
when: (ctx: any) => boolean;
```

## choices

```ts
choices: string[];
```

## source

```ts
source?: undefined;
```

## default

```ts
default?: undefined;
```
