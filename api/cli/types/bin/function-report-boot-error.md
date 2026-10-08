---
url: /api/cli/types/bin/function-report-boot-error.md
description: api documentation of reportBootError from @tsed/cli
---

## Usage

```typescript
import { reportBootError } from "@tsed/cli/src/bin/reportBootError";
```

> See [/packages/cli/src/bin/reportBootError.ts](https://github.com/tsedio/tsed-cli/blob/v7.8.1/packages/cli/src/bin/reportBootError.ts#L0-L0).

## Overview

```ts
function reportBootError(error: unknown, commandName?: string): Promise<void>;
```

## Description

Report an error raised while the CLI is booting, before the injector (and therefore CliStats) exists.

This module must only depend on Node.js built-ins: it runs precisely when a dependency of the CLI cannot be loaded.
