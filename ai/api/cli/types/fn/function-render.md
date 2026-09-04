---
title: render from @tsed/cli
description: api documentation of render from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation render function
---
# render - @tsed/cli

## Usage

```typescript
import { render } from "@tsed/cli";
```

> See [/packages/cli/src/fn/render.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/fn/render.ts#L0-L0).

## Overview

```ts
function render(id: string, data: Parameters<typeof CliProjectService.prototype.createFromTemplate>[1]): Promise<import("../index.js").TemplateRenderReturnType | undefined>;
```
