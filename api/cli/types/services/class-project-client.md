---
url: /api/cli/types/services/class-project-client.md
description: api documentation of ProjectClient from @tsed/cli
---

## Usage

```typescript
import { ProjectClient } from "@tsed/cli";
```

> See [/packages/cli/src/services/ProjectClient.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/services/ProjectClient.ts#L0-L0).

## Overview

```ts
class ProjectClient extends Project {
    readonly pkg: ProjectPackageJson;
    readonly fs: CliFs;
    readonly dockerCompose: CliDockerComposeYaml;
    rootDir: string;
    constructor({ rootDir, ...options }: ProjectOptions & {
        rootDir: string;
    });
    get srcDir(): string;
    get serverSourceFile(): SourceFile | undefined;
    get configSourceFile(): SourceFile | undefined;
    get indexSourceFile(): SourceFile | undefined;
    get binSourceFile(): SourceFile | undefined;
    get serverName(): string;
    getSource(path: string): SourceFile | undefined;
    createSource(path: string, sourceFileText?: string | OptionalKind<SourceFileStructure> | WriterFunction, options?: SourceFileCreateOptions): Promise<SourceFile | undefined>;
    findClassDecorator(sourceFile: SourceFile, name: string): import("ts-morph").Decorator | undefined;
    addMountPath(path: string, specifier: string): void;
    addNamespaceImport(sourceFile: SourceFile, moduleSpecifier: string, name: string): import("ts-morph").Identifier | undefined;
    findConfiguration(kind: "server" | "config" | "bin"): ObjectLiteralExpression | undefined;
    getPropertyAssignment<TKind extends SyntaxKind>(input: ObjectLiteralExpression, { name, initializer, kind }: {
        name: string;
        initializer: string | WriterFunction;
        kind: TKind;
    }): KindToNodeMappings[TKind];
    getPropertyAssignment<TKind extends SyntaxKind>(input: ObjectLiteralExpression, { name, initializer, kind }: {
        name: string;
        initializer?: string | WriterFunction;
        kind: TKind;
    }): KindToNodeMappings[TKind] | undefined;
    addConfigSource(name: string, { content, moduleSpecifier }: {
        content?: string;
        moduleSpecifier: string;
    }): void;
    protected findConfigurationDecorationOptions(): ObjectLiteralExpression | undefined;
    protected findConfigConfiguration(): ObjectLiteralExpression | undefined;
    protected findBinConfiguration(): ObjectLiteralExpression | undefined;
}
```

## readonly pkg

```ts
readonly pkg: ProjectPackageJson;
```

## readonly fs

```ts
readonly fs: CliFs;
```

## readonly dockerCompose

```ts
readonly dockerCompose: CliDockerComposeYaml;
```

## rootDir

```ts
rootDir: string;
```

## get srcDir

```ts
get srcDir(): string;
```

## get serverSourceFile

```ts
get serverSourceFile(): SourceFile | undefined;
```

## get configSourceFile

```ts
get configSourceFile(): SourceFile | undefined;
```

## get indexSourceFile

```ts
get indexSourceFile(): SourceFile | undefined;
```

## get binSourceFile

```ts
get binSourceFile(): SourceFile | undefined;
```

## get serverName

```ts
get serverName(): string;
```

## getSource

```ts
getSource(path: string): SourceFile | undefined;
```

## createSource

```ts
createSource(path: string, sourceFileText?: string | OptionalKind<SourceFileStructure> | WriterFunction, options?: SourceFileCreateOptions): Promise<SourceFile | undefined>;
```

## findClassDecorator

```ts
findClassDecorator(sourceFile: SourceFile, name: string): import("ts-morph").Decorator | undefined;
```

## addMountPath

```ts
addMountPath(path: string, specifier: string): void;
```

## addNamespaceImport

```ts
addNamespaceImport(sourceFile: SourceFile, moduleSpecifier: string, name: string): import("ts-morph").Identifier | undefined;
```

## findConfiguration

```ts
findConfiguration(kind: "server" | "config" | "bin"): ObjectLiteralExpression | undefined;
```

## getPropertyAssignment

```ts
getPropertyAssignment<TKind extends SyntaxKind>(input: ObjectLiteralExpression, { name, initializer, kind }: {
     name: string;
     initializer: string | WriterFunction;
     kind: TKind;
 }): KindToNodeMappings[TKind];
```

## getPropertyAssignment

```ts
getPropertyAssignment<TKind extends SyntaxKind>(input: ObjectLiteralExpression, { name, initializer, kind }: {
     name: string;
     initializer?: string | WriterFunction;
     kind: TKind;
 }): KindToNodeMappings[TKind] | undefined;
```

## addConfigSource

```ts
addConfigSource(name: string, { content, moduleSpecifier }: {
     content?: string;
     moduleSpecifier: string;
 }): void;
```

## protected findConfigurationDecorationOptions

```ts
protected findConfigurationDecorationOptions(): ObjectLiteralExpression | undefined;
```

## protected findConfigConfiguration

```ts
protected findConfigConfiguration(): ObjectLiteralExpression | undefined;
```

## protected findBinConfiguration

```ts
protected findBinConfiguration(): ObjectLiteralExpression | undefined;
```
