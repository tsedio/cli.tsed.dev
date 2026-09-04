---
url: /api/cli/types/fn/function-render.md
description: api documentation of render from @tsed/cli
---

## Usage

```typescript
import { render } from "@tsed/cli";
```

> See [/packages/cli/src/fn/render.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/fn/render.ts#L0-L0).

## Overview

```ts
function render(id: string, data: Parameters<typeof CliProjectService.prototype.createFromTemplate>[1]): Promise<import("../index.js").TemplateRenderReturnType | undefined>;
```
