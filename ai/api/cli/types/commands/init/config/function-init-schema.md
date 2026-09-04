---
title: InitSchema from @tsed/cli
description: api documentation of InitSchema from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation InitSchema function
---
# InitSchema - @tsed/cli

## Usage

```typescript
import { InitSchema } from "@tsed/cli/src/commands/init/config/InitSchema";
```

> See [/packages/cli/src/commands/init/config/InitSchema.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/init/config/InitSchema.ts#L0-L0).

## Overview

```ts
const InitSchema: () => import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
    root: import("@tsed/schema").JsonSchema<string>;
    projectName: import("@tsed/schema").JsonSchema<string | undefined>;
    platform: import("@tsed/schema").JsonSchema<PlatformType>;
    architecture: import("@tsed/schema").JsonSchema<ArchitectureConvention>;
    convention: import("@tsed/schema").JsonSchema<ProjectConvention>;
    features: import("@tsed/schema").JsonSchema<FeatureType[]>;
    runtime: import("@tsed/schema").JsonSchema<RuntimeTypes>;
    packageManager: import("@tsed/schema").JsonSchema<PackageManager>;
    GH_TOKEN: import("@tsed/schema").JsonSchema<string | undefined>;
    tsedVersion: import("@tsed/schema").JsonSchema<string | undefined>;
    file: import("@tsed/schema").JsonSchema<string | undefined>;
    skipPrompt: import("@tsed/schema").JsonSchema<boolean | undefined>;
}> & Record<string, unknown>>;
```

<!-- Members -->

## root: import

```ts
root: import("@tsed/schema").JsonSchema<string>;
```

## projectName: import

```ts
projectName: import("@tsed/schema").JsonSchema<string | undefined>;
```

## platform: import

```ts
platform: import("@tsed/schema").JsonSchema<PlatformType>;
```

## architecture: import

```ts
architecture: import("@tsed/schema").JsonSchema<ArchitectureConvention>;
```

## convention: import

```ts
convention: import("@tsed/schema").JsonSchema<ProjectConvention>;
```

## features: import

```ts
features: import("@tsed/schema").JsonSchema<FeatureType[]>;
```

## runtime: import

```ts
runtime: import("@tsed/schema").JsonSchema<RuntimeTypes>;
```

## packageManager: import

```ts
packageManager: import("@tsed/schema").JsonSchema<PackageManager>;
```

## GH_TOKEN: import

```ts
GH_TOKEN: import("@tsed/schema").JsonSchema<string | undefined>;
```

## tsedVersion: import

```ts
tsedVersion: import("@tsed/schema").JsonSchema<string | undefined>;
```

## file: import

```ts
file: import("@tsed/schema").JsonSchema<string | undefined>;
```

## skipPrompt: import

```ts
skipPrompt: import("@tsed/schema").JsonSchema<boolean | undefined>;
```
