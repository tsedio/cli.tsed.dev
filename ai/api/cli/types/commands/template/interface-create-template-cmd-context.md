---
title: CreateTemplateCmdContext from @tsed/cli
description: api documentation of CreateTemplateCmdContext from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation CreateTemplateCmdContext interface
---
# CreateTemplateCmdContext - @tsed/cli

## Usage

```typescript
import { CreateTemplateCmdContext } from "@tsed/cli";
```

> See [/packages/cli/src/commands/template/CreateTemplateCommand.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/template/CreateTemplateCommand.ts#L0-L0).

## Overview

```ts
interface CreateTemplateCmdContext extends RenderDataContext {
    name: string;
    from?: string | "new";
    override?: string;
    templateId?: string;
    template?: DefineTemplateOptions;
}
```

<!-- Members -->

## name

```ts
name: string;
```

## from

```ts
from?: string | "new";
```

## override

```ts
override?: string;
```

## templateId

```ts
templateId?: string;
```

## template

```ts
template?: DefineTemplateOptions;
```
