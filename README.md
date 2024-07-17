# Guide Complet pour Configurer un Monorepo TypeScript avec Turbo

- ## [Article de blog](https://apprendre-la-programmation.net/guide-complet-monorepo-typescript-turbo-vercel)
- ## Vidéo (Coming Soon)

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `api`: a [NestJS](https://nestjs.com) api
- `web`: a [Next.js](https://nextjs.org/) app
- `@repo/ui`: a stub React component library shared by both `web` and `docs` applications
- `@repo/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@repo/typescript-config`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

### Build

To build all apps and packages, run the following command:

```
cd tuto-monorepo-nextjs-nestjs-clerk-tinacms
pnpm build
```

### Develop

To develop all apps and packages, run the following command:

```
cd tuto-monorepo-nextjs-nestjs-clerk-tinacms
pnpm dev
```
