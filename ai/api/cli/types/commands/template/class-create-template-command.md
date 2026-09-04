---
title: CreateTemplateCommand from @tsed/cli
description: api documentation of CreateTemplateCommand from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation CreateTemplateCommand class
---
# CreateTemplateCommand - @tsed/cli

## Usage

```typescript
import { CreateTemplateCommand } from "@tsed/cli/src/commands/template/CreateTemplateCommand";
```

> See [/packages/cli/src/commands/template/CreateTemplateCommand.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/template/CreateTemplateCommand.ts#L0-L0).

## Overview

```ts
class CreateTemplateCommand implements CommandProvider<CreateTemplateCmdContext> {
    protected projectPackageJson: ProjectPackageJson;
    protected templates: CliTemplatesService;
    $prompt(data: Partial<CreateTemplateCmdContext>): Promise<PromptQuestion[]>;
    $mapContext(ctx: Partial<any>): any;
    $exec(ctx: CreateTemplateCmdContext & {
        symbolName: string;
        symbolPath: string;
    }): {
        title: string;
        task: () => Promise<void>;
    }[];
}
```

<!-- Members -->

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## protected templates

```ts
protected templates: CliTemplatesService;
```

## $prompt

```ts
$prompt(data: Partial<CreateTemplateCmdContext>): Promise<PromptQuestion[]>;
```

## $mapContext

```ts
$mapContext(ctx: Partial<any>): any;
```

## $exec

```ts
$exec(ctx: CreateTemplateCmdContext & {
     symbolName: string;
     symbolPath: string;
 }): {
     title: string;
     task: () => Promise<void>;
 }[];
```
