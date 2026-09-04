---
title: CliFs from @tsed/cli-core
description: api documentation of CliFs from @tsed/cli-core
meta:
 - name: keywords
   description: api typescript node.js documentation CliFs class
---
# CliFs - @tsed/cli-core

## Usage

```typescript
import { CliFs } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/CliFs.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/CliFs.ts#L0-L0).

## Overview

```ts
class CliFs extends RealFileSystemHost {
    raw: typeof Fs;
    exists(path: string): boolean;
    join(...args: string[]): string;
    readFile(file: string | Buffer | number, encoding?: any): Promise<string>;
    readFileSync(file: string | Buffer | number, encoding?: any): any;
    readJson(file: string, encoding?: any): Promise<any>;
    readJsonSync(file: string, encoding?: any): any;
    writeJson(file: string | Buffer | number, data: any, options?: WriteFileOptions | string): Promise<any>;
    writeJsonSync(file: string | Buffer | number, data: any, options?: WriteFileOptions | string): void;
    writeFileSync(path: PathLike | number, data: any, options?: WriteFileOptions): void;
    writeFile(file: string | Buffer | number, data: any, options?: WriteFileOptions | string): Promise<void>;
    ensureDir(path: string, options?: EnsureDirOptions | number): Promise<void>;
    ensureDirSync(path: string, options?: EnsureDirOptions | number): void;
    findUpFile(root: string, file: string): string | undefined;
    importModule(mod: string, root?: string): Promise<any>;
}
```

<!-- Members -->

## raw

```ts
raw: typeof Fs;
```

## exists

```ts
exists(path: string): boolean;
```

## join

```ts
join(...args: string[]): string;
```

## readFile

```ts
readFile(file: string | Buffer | number, encoding?: any): Promise<string>;
```

## readFileSync

```ts
readFileSync(file: string | Buffer | number, encoding?: any): any;
```

## readJson

```ts
readJson(file: string, encoding?: any): Promise<any>;
```

## readJsonSync

```ts
readJsonSync(file: string, encoding?: any): any;
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
writeFileSync(path: PathLike | number, data: any, options?: WriteFileOptions): void;
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
ensureDirSync(path: string, options?: EnsureDirOptions | number): void;
```

## findUpFile

```ts
findUpFile(root: string, file: string): string | undefined;
```

## importModule

```ts
importModule(mod: string, root?: string): Promise<any>;
```
