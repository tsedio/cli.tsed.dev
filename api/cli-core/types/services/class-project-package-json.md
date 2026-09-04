---
url: /api/cli-core/types/services/class-project-package-json.md
description: api documentation of ProjectPackageJson from @tsed/cli-core
---

## Usage

```typescript
import { ProjectPackageJson } from "@tsed/cli-core";
```

> See [/packages/cli-core/src/services/ProjectPackageJson.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli-core/src/services/ProjectPackageJson.ts#L0-L0).

## Overview

```ts
class ProjectPackageJson {
    rewrite: boolean;
    reinstall: boolean;
    GH_TOKEN?: string;
    protected fs: CliFs;
    constructor();
    get path(): string;
    get dir(): string;
    set dir(dir: string);
    get cwd(): string;
    get name(): string;
    set name(name: string);
    get version(): string;
    get description(): string;
    get scripts(): {
        [key: string]: string;
    };
    get dependencies(): {
        [key: string]: string;
    };
    get devDependencies(): {
        [key: string]: string;
    };
    get allDependencies(): {
        [key: string]: string;
    };
    get preferences(): ProjectPreferences;
    setCWD(dir: string): void;
    fillWithPreferences<T extends {}>(ctx: T): T & {
        packageManager: import("../interfaces/ProjectPreferences.js").PackageManager;
        runtime: any;
        architecture: any;
        convention: any;
    };
    $loadPackageJson(): this;
    toJSON(): PackageJson;
    read(): this;
    setRaw(pkg: any): void;
    addDevDependency(pkg: string, version?: string): this;
    addDevDependencies(modules: {
        [key: string]: string | undefined;
    }, scope?: any): this;
    addDependency(pkg: string, version?: string): this;
    addDependencies(modules: {
        [key: string]: string | undefined;
    }, ctx?: any): this;
    addScript(task: string, cmd: string): this;
    addScripts(scripts: {
        [key: string]: string;
    }): this;
    add(key: string, data: any): this;
    setPreference(key: keyof ProjectPreferences, value: any): void;
    set(key: string, value: any): void;
    get(key: string): any;
    write(): this;
    importModule(mod: string): Promise<any>;
    setGhToken(GH_TOKEN: string): void;
    refresh(): this;
    protected getPackageJson(): any;
    protected getEmptyPackageJson(name: string): {
        name: string;
        version: string;
        description: string;
        scripts: {};
        dependencies: {};
        devDependencies: {};
    };
}
```

## rewrite

```ts
rewrite: boolean;
```

## reinstall

```ts
reinstall: boolean;
```

## GH\_TOKEN

```ts
GH_TOKEN?: string;
```

## protected fs

```ts
protected fs: CliFs;
```

## get path

```ts
get path(): string;
```

## get dir

```ts
get dir(): string;
```

## set dir

```ts
set dir(dir: string);
```

## get cwd

```ts
get cwd(): string;
```

## get name

```ts
get name(): string;
```

## set name

```ts
set name(name: string);
```

## get version

```ts
get version(): string;
```

## get description

```ts
get description(): string;
```

## get scripts

```ts
get scripts(): {
     [key: string]: string;
 };
```

## get dependencies

```ts
get dependencies(): {
     [key: string]: string;
 };
```

## get devDependencies

```ts
get devDependencies(): {
     [key: string]: string;
 };
```

## get allDependencies

```ts
get allDependencies(): {
     [key: string]: string;
 };
```

## get preferences

```ts
get preferences(): ProjectPreferences;
```

## setCWD

```ts
setCWD(dir: string): void;
```

## fillWithPreferences

```ts
fillWithPreferences<T extends {}>(ctx: T): T & {
     packageManager: import("../interfaces/ProjectPreferences.js").PackageManager;
     runtime: any;
     architecture: any;
     convention: any;
 };
```

## $loadPackageJson

```ts
$loadPackageJson(): this;
```

## toJSON

```ts
toJSON(): PackageJson;
```

## read

```ts
read(): this;
```

## setRaw

```ts
setRaw(pkg: any): void;
```

## addDevDependency

```ts
addDevDependency(pkg: string, version?: string): this;
```

## addDevDependencies

```ts
addDevDependencies(modules: {
     [key: string]: string | undefined;
 }, scope?: any): this;
```

## addDependency

```ts
addDependency(pkg: string, version?: string): this;
```

## addDependencies

```ts
addDependencies(modules: {
     [key: string]: string | undefined;
 }, ctx?: any): this;
```

## addScript

```ts
addScript(task: string, cmd: string): this;
```

## addScripts

```ts
addScripts(scripts: {
     [key: string]: string;
 }): this;
```

## add

```ts
add(key: string, data: any): this;
```

## setPreference

```ts
setPreference(key: keyof ProjectPreferences, value: any): void;
```

## set

```ts
set(key: string, value: any): void;
```

## get

```ts
get(key: string): any;
```

## write

```ts
write(): this;
```

## importModule

```ts
importModule(mod: string): Promise<any>;
```

Import a module from the project workspace

## setGhToken

```ts
setGhToken(GH_TOKEN: string): void;
```

## refresh

```ts
refresh(): this;
```

## protected getPackageJson

```ts
protected getPackageJson(): any;
```

## protected getEmptyPackageJson

```ts
protected getEmptyPackageJson(name: string): {
     name: string;
     version: string;
     description: string;
     scripts: {};
     dependencies: {};
     devDependencies: {};
 };
```
