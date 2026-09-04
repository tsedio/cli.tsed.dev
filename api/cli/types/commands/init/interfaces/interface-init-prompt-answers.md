---
url: /api/cli/types/commands/init/interfaces/interface-init-prompt-answers.md
description: api documentation of InitPromptAnswers from @tsed/cli
---

## Usage

```typescript
import { InitPromptAnswers } from "@tsed/cli";
```

> See [/packages/cli/src/commands/init/interfaces/InitPromptAnswers.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/commands/init/interfaces/InitPromptAnswers.ts#L0-L0).

## Overview

```ts
interface InitPromptAnswers {
    projectName: string;
    platform: PlatformType;
    architecture: ArchitectureConvention;
    convention: ProjectConvention;
    features: string[];
    featuresDB: string[];
    featuresTypeORM: string;
    featuresTesting: string;
    featuresLinter: string;
    featuresEslintFormatter: string[];
    featuresOxlintFormatter: string[];
    featuresExtraLinter: string[];
    featuresBundler: string;
    oidcBasePath: string;
    packageManager: PackageManager;
}
```

## projectName

```ts
projectName: string;
```

## platform

```ts
platform: PlatformType;
```

## architecture

```ts
architecture: ArchitectureConvention;
```

## convention

```ts
convention: ProjectConvention;
```

## features

```ts
features: string[];
```

## featuresDB

```ts
featuresDB: string[];
```

## featuresTypeORM

```ts
featuresTypeORM: string;
```

## featuresTesting

```ts
featuresTesting: string;
```

## featuresLinter

```ts
featuresLinter: string;
```

## featuresEslintFormatter

```ts
featuresEslintFormatter: string[];
```

## featuresOxlintFormatter

```ts
featuresOxlintFormatter: string[];
```

## featuresExtraLinter

```ts
featuresExtraLinter: string[];
```

## featuresBundler

```ts
featuresBundler: string;
```

## oidcBasePath

```ts
oidcBasePath: string;
```

## packageManager

```ts
packageManager: PackageManager;
```
