---
title: RenderDataContext from @tsed/cli
description: api documentation of RenderDataContext from @tsed/cli
meta:
 - name: keywords
   description: api typescript node.js documentation RenderDataContext interface
---
# RenderDataContext - @tsed/cli

## Usage

```typescript
import { RenderDataContext } from "@tsed/cli";
```

> See [/packages/cli/src/interfaces/RenderDataContext.ts](https://github.com/tsedio/tsed-cli/blob/v7.7.0/packages/cli/src/interfaces/RenderDataContext.ts#L0-L0).

## Overview

```ts
interface RenderDataContext extends CommandData, TsED.RenderDataContext {
    commandName: string;
    platform: PlatformType;
    convention: ProjectConvention;
    packageManager: PackageManager;
    architecture: ArchitectureConvention;
    runtime: RuntimeTypes;
    features?: FeatureType[];
    root?: string;
    premium?: boolean;
    projectName?: string;
    tsedVersion?: string;
    cliVersion?: string;
    oidcBasePath?: string;
    file?: string;
    route: string;
    express?: boolean;
    koa?: boolean;
    fastify?: boolean;
    swagger?: boolean;
    oidc?: boolean;
    graphql?: boolean;
    scalar?: boolean;
    mongoose?: boolean;
    typeorm?: boolean;
    passportjs?: boolean;
    config?: boolean;
    configEnvs?: boolean;
    configDotenv?: boolean;
    configJson?: boolean;
    configYaml?: boolean;
    configIoredis?: boolean;
    configMongo?: boolean;
    configAwsSecrets?: boolean;
    configVault?: boolean;
    configPostgres?: boolean;
    barrels?: string;
    bun?: boolean;
    bunVite?: boolean;
    vite?: boolean;
    node?: boolean;
    compiled?: boolean;
    testing?: boolean;
    commands?: boolean;
    eslint?: boolean;
    oxlint?: boolean;
    jest?: boolean;
    prettier?: boolean;
    oxfmt?: boolean;
    vitest?: boolean;
    lintstaged?: boolean;
    prisma?: boolean;
    passport?: boolean;
}
```

<!-- Members -->

## commandName

```ts
commandName: string;
```

## platform

```ts
platform: PlatformType;
```

## convention

```ts
convention: ProjectConvention;
```

## packageManager

```ts
packageManager: PackageManager;
```

## architecture

```ts
architecture: ArchitectureConvention;
```

## runtime

```ts
runtime: RuntimeTypes;
```

## features

```ts
features?: FeatureType[];
```

## root

```ts
root?: string;
```

## premium

```ts
premium?: boolean;
```

## projectName

```ts
projectName?: string;
```

## tsedVersion

```ts
tsedVersion?: string;
```

## cliVersion

```ts
cliVersion?: string;
```

## oidcBasePath

```ts
oidcBasePath?: string;
```

## file

```ts
file?: string;
```

## route

```ts
route: string;
```

## express

```ts
express?: boolean;
```

## koa

```ts
koa?: boolean;
```

## fastify

```ts
fastify?: boolean;
```

## swagger

```ts
swagger?: boolean;
```

## oidc

```ts
oidc?: boolean;
```

## graphql

```ts
graphql?: boolean;
```

## scalar

```ts
scalar?: boolean;
```

## mongoose

```ts
mongoose?: boolean;
```

## typeorm

```ts
typeorm?: boolean;
```

## passportjs

```ts
passportjs?: boolean;
```

## config

```ts
config?: boolean;
```

## configEnvs

```ts
configEnvs?: boolean;
```

## configDotenv

```ts
configDotenv?: boolean;
```

## configJson

```ts
configJson?: boolean;
```

## configYaml

```ts
configYaml?: boolean;
```

## configIoredis

```ts
configIoredis?: boolean;
```

## configMongo

```ts
configMongo?: boolean;
```

## configAwsSecrets

```ts
configAwsSecrets?: boolean;
```

## configVault

```ts
configVault?: boolean;
```

## configPostgres

```ts
configPostgres?: boolean;
```

## barrels

```ts
barrels?: string;
```

## bun

```ts
bun?: boolean;
```

## bunVite

```ts
bunVite?: boolean;
```

## vite

```ts
vite?: boolean;
```

## node

```ts
node?: boolean;
```

## compiled

```ts
compiled?: boolean;
```

## testing

```ts
testing?: boolean;
```

## commands

```ts
commands?: boolean;
```

## eslint

```ts
eslint?: boolean;
```

## oxlint

```ts
oxlint?: boolean;
```

## jest

```ts
jest?: boolean;
```

## prettier

```ts
prettier?: boolean;
```

## oxfmt

```ts
oxfmt?: boolean;
```

## vitest

```ts
vitest?: boolean;
```

## lintstaged

```ts
lintstaged?: boolean;
```

## prisma

```ts
prisma?: boolean;
```

## passport

```ts
passport?: boolean;
```
