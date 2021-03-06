# @himenon/argo-rollouts-typescript-openapi

```bash
npm  i   @himenon/argo-rollouts-typescript-openapi
pnpm i   @himenon/argo-rollouts-typescript-openapi
yarn add @himenon/argo-rollouts-typescript-openapi
```

## Usage

```ts
import * as fs from "fs";
import * as yaml from "js-yaml"; // pnpm i -D js-yaml @types/js-yaml
import type { Schemas } from "@himenon/argo-rollouts-typescript-openapi/v1.22.3";
```

## Build

```ts
pnpm run build
```

## Update Schemas

```bash
# Fetch and Build
pnpm run build:all

# Fetch schemas
pnpm run fetch:schemas

# Generate source code
pnpm run generate:code
```

## OpenAPI Source for argo-rollouts

- <https://github.com/argoproj/argo-rollouts/blob/master/pkg/apiclient/rollout/rollout.swagger.json>

## OpenAPI TypeScript Code Generator

- [@himenon/openapi-typescript-code-generator](https://github.com/Himenon/openapi-typescript-code-generator)

You can also just use the type definition

## Use Another Version

Edit [config.ts](./scripts/config.ts)

## LICENCE

[@Himenon/argo-rollouts-typescript-openapi](https://github.com/Himenon/argo-rollouts-typescript-openapi)・MIT
