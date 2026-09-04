---
url: /api/cli/types/commands/run/class-run-cmd.md
description: api documentation of RunCmd from @tsed/cli
---

## Usage

```typescript
import { RunCmd } from "@tsed/cli/src/commands/run/RunCmd";
```

> See [/packages/cli/src/commands/run/RunCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/run/RunCmd.ts#L0-L0).

## Overview

```ts
class RunCmd implements CommandProvider {
    protected fs: CliFs;
    protected projectPackageJson: ProjectPackageJson;
    protected runScript: CliRunScript;
    $exec(ctx: RunCmdContext): Promise<void>;
}
```

## protected fs

```ts
protected fs: CliFs;
```

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## protected runScript

```ts
protected runScript: CliRunScript;
```

## $exec

```ts
$exec(ctx: RunCmdContext): Promise<void>;
```
