---
url: /api/cli/types/commands/generate/class-generate-cmd.md
description: api documentation of GenerateCmd from @tsed/cli
---

## Usage

```typescript
import { GenerateCmd } from "@tsed/cli";
```

> See [/packages/cli/src/commands/generate/GenerateCmd.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/generate/GenerateCmd.ts#L0-L0).

## Overview

```ts
class GenerateCmd implements CommandProvider {
    protected projectPackageJson: ProjectPackageJson;
    protected projectService: CliProjectService;
    protected templates: CliTemplatesService;
    $prompt(data: Partial<GenerateCmdContext>): Promise<(import("@tsed/cli-core").PromptInputQuestion | import("@tsed/cli-core").PromptPasswordQuestion | import("@tsed/cli-core").PromptConfirmQuestion | import("@tsed/cli-core").PromptListQuestion<any> | import("@tsed/cli-core").PromptCheckboxQuestion<any> | import("@tsed/cli-core").PromptAutocompleteQuestion<any> | {
        type: "input";
        name: string;
        message: string;
        default: ((state: Partial<GenerateCmdContext>) => string) | undefined;
        when: boolean;
    })[]>;
    $mapContext(ctx: Partial<GenerateCmdContext>): GenerateCmdContext;
    $exec(ctx: GenerateCmdContext): Task[];
}
```

## protected projectPackageJson

```ts
protected projectPackageJson: ProjectPackageJson;
```

## protected projectService

```ts
protected projectService: CliProjectService;
```

## protected templates

```ts
protected templates: CliTemplatesService;
```

## $prompt

```ts
$prompt(data: Partial<GenerateCmdContext>): Promise<(import("@tsed/cli-core").PromptInputQuestion | import("@tsed/cli-core").PromptPasswordQuestion | import("@tsed/cli-core").PromptConfirmQuestion | import("@tsed/cli-core").PromptListQuestion<any> | import("@tsed/cli-core").PromptCheckboxQuestion<any> | import("@tsed/cli-core").PromptAutocompleteQuestion<any> | {
     type: "input";
     name: string;
     message: string;
     default: ((state: Partial<GenerateCmdContext>) => string) | undefined;
     when: boolean;
 })[]>;
```

## $mapContext

```ts
$mapContext(ctx: Partial<GenerateCmdContext>): GenerateCmdContext;
```

## $exec

```ts
$exec(ctx: GenerateCmdContext): Task[];
```
