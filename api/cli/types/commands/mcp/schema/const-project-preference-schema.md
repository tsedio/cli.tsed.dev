---
url: /api/cli/types/commands/mcp/schema/const-project-preference-schema.md
description: api documentation of ProjectPreferenceSchema from @tsed/cli
---

## Usage

```typescript
import { ProjectPreferenceSchema } from "@tsed/cli/src/commands/mcp/schema/ProjectPreferencesSchema";
```

> See [/packages/cli/src/commands/mcp/schema/ProjectPreferencesSchema.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/mcp/schema/ProjectPreferencesSchema.ts#L0-L0).

## Overview

```ts
const ProjectPreferenceSchema: import("@tsed/schema").JsonSchema<import("@tsed/schema").PropsToShape<{
    convention: import("@tsed/schema").JsonSchema<ProjectConvention>;
    packageManager: import("@tsed/schema").JsonSchema<PackageManager>;
    runtime: import("@tsed/schema").JsonSchema<"vite" | "bun-vite" | "node" | "babel" | "webpack" | "bun" | "swc">;
    platform: import("@tsed/schema").JsonSchema<PlatformType>;
}> | undefined>;
```

## convention: import

```ts
convention: import("@tsed/schema").JsonSchema<ProjectConvention>;
```

## packageManager: import

```ts
packageManager: import("@tsed/schema").JsonSchema<PackageManager>;
```

## runtime: import

```ts
runtime: import("@tsed/schema").JsonSchema<"vite" | "bun-vite" | "node" | "babel" | "webpack" | "bun" | "swc">;
```

## platform: import

```ts
platform: import("@tsed/schema").JsonSchema<PlatformType>;
```
