# NxN Starter

This is a boilerplate for building full-stack applications using the T3 Stack. It includes:

- [Next.js](https://nextjs.org) for the client
- [NestJS](https://nestjs.com) for the server
- [tRPC](https://trpc.io) for typesafe API routes
- [Turborepo](https://turborepo.org) for monorepo management
- [PNPM](https://pnpm.io) for package management

## Getting Started

To get started, clone the repository and install the dependencies:

```bash
git clone https://github.com/your-username/nxn-starter.git
cd nxn-starter
pnpm install
```

Then, start the development servers:

```bash
turbo dev
```

This will start the client and server applications in development mode.

## Monorepo Structure

This repository is a monorepo managed by [Turborepo](https://turborepo.org). The applications and packages are organized as follows:

- `apps/client`: The Next.js client application
- `apps/server`: The NestJS server application
- `packages/eslint-config`: Shared ESLint configuration
- `packages/trpc`: tRPC router and types
- `packages/typescript-config`: Shared TypeScript configuration