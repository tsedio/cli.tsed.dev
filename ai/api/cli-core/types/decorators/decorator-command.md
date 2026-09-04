---
title: Command from @tsed/cli-core
description: api documentation of Command from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation Command decorator
---
# Command - @tsed/cli-core

## Usage

```typescript
import { Command } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/decorators/command.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/decorators/command.ts#L0-L0).

## Overview

```ts
function Command<Input = any>(options: BaseCommandOptions<Input>): ClassDecorator;
```
