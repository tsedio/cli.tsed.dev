---
title: FakeCliFs from @tsed/cli-testing
description: api documentation of FakeCliFs from @tsed/cli-testing
meta:
 - name: keywords
   description: api typescript node.js documentation FakeCliFs class
---
# FakeCliFs - @tsed/cli-testing

## Usage

```typescript
import { FakeCliFs } from "@tsed/cli-testing";
```

> See [/packages/cli-testing/src/FakeCliFs.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-testing/src/FakeCliFs.ts#L0-L0).

## Overview

```ts
class FakeCliFs implements FileSystemHost {
    static files: Map<any, string>;
    static directories: Set<string>;
    static getKeys(): any;
    findUpFile(): null;
    exists(path: string): boolean;
    readFile(file: string | Buffer | number, encoding?: any): Promise<string>;
    readFileSync(file: string | Buffer | number, encoding?: any): string;
    readJson(file: string | Buffer | number, encoding?: any): Promise<any>;
    readJsonSync(file: string | Buffer | number, encoding?: any): any;
    writeJson(file: string | Buffer | number, data: any, options?: WriteFileOptions | string): Promise<any>;
    writeJsonSync(file: string | Buffer | number, data: any, options?: WriteFileOptions | string): void;
    writeFileSync(path: PathLike | number, data: any, _?: WriteFileOptions): void;
    writeFile(file: string | Buffer | number, data: any, options?: WriteFileOptions | string): Promise<void>;
    ensureDir(path: string, options?: EnsureDirOptions | number): Promise<void>;
    ensureDirSync(path: string, _?: EnsureDirOptions | number): void;
    isCaseSensitive(): boolean;
    delete(path: string): Promise<void>;
    deleteSync(path: string): void;
    readDirSync(dirPath: string): RuntimeDirEntry[];
    mkdir(dirPath: string): Promise<void>;
    mkdirSync(dirPath: string): void;
    move(srcPath: string, destPath: string): Promise<void>;
    moveSync(srcPath: string, destPath: string): void;
    copy(srcPath: string, destPath: string): Promise<void>;
    copySync(srcPath: string, destPath: string): void;
    fileExists(filePath: string): Promise<boolean>;
    fileExistsSync(filePath: string): boolean;
    directoryExists(dirPath: string): Promise<boolean>;
    directoryExistsSync(dirPath: string): boolean;
    realpathSync(path: string): string;
    getCurrentDirectory(): string;
    glob(patterns: ReadonlyArray<string>): Promise<string[]>;
    globSync(patterns: ReadonlyArray<string>): string[];
}
```

<!-- Members -->

## static files

```ts
static files: Map<any, string>;
```

## static directories

```ts
static directories: Set<string>;
```

## static getKeys

```ts
static getKeys(): any;
```

## findUpFile

```ts
findUpFile(): null;
```

## exists

```ts
exists(path: string): boolean;
```

## readFile

```ts
readFile(file: string | Buffer | number, encoding?: any): Promise<string>;
```

## readFileSync

```ts
readFileSync(file: string | Buffer | number, encoding?: any): string;
```

## readJson

```ts
readJson(file: string | Buffer | number, encoding?: any): Promise<any>;
```

## readJsonSync

```ts
readJsonSync(file: string | Buffer | number, encoding?: any): any;
```

## writeJson

```ts
writeJson(file: string | Buffer | number, data: any, options?: WriteFileOptions | string): Promise<any>;
```

## writeJsonSync

```ts
writeJsonSync(file: string | Buffer | number, data: any, options?: WriteFileOptions | string): void;
```

## writeFileSync

```ts
writeFileSync(path: PathLike | number, data: any, _?: WriteFileOptions): void;
```

## writeFile

```ts
writeFile(file: string | Buffer | number, data: any, options?: WriteFileOptions | string): Promise<void>;
```

## ensureDir

```ts
ensureDir(path: string, options?: EnsureDirOptions | number): Promise<void>;
```

## ensureDirSync

```ts
ensureDirSync(path: string, _?: EnsureDirOptions | number): void;
```

## isCaseSensitive

```ts
isCaseSensitive(): boolean;
```

## delete

```ts
delete(path: string): Promise<void>;
```

##

```ts
```

## deleteSync

```ts
deleteSync(path: string): void;
```

##

```ts
```

## readDirSync

```ts
readDirSync(dirPath: string): RuntimeDirEntry[];
```

## mkdir

```ts
mkdir(dirPath: string): Promise<void>;
```

## mkdirSync

```ts
mkdirSync(dirPath: string): void;
```

## move

```ts
move(srcPath: string, destPath: string): Promise<void>;
```

## moveSync

```ts
moveSync(srcPath: string, destPath: string): void;
```

## copy

```ts
copy(srcPath: string, destPath: string): Promise<void>;
```

## copySync

```ts
copySync(srcPath: string, destPath: string): void;
```

## fileExists

```ts
fileExists(filePath: string): Promise<boolean>;
```

## fileExistsSync

```ts
fileExistsSync(filePath: string): boolean;
```

## directoryExists

```ts
directoryExists(dirPath: string): Promise<boolean>;
```

## directoryExistsSync

```ts
directoryExistsSync(dirPath: string): boolean;
```

## realpathSync

```ts
realpathSync(path: string): string;
```

## getCurrentDirectory

```ts
getCurrentDirectory(): string;
```

## glob

```ts
glob(patterns: ReadonlyArray<string>): Promise<string[]>;
```

##

```ts
```

## globSync

```ts
globSync(patterns: ReadonlyArray<string>): string[];
```
