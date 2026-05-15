# StackForge

> **One command. Full production stack.** Scaffold a Next.js + NestJS + Supabase + Redis monorepo with Docker and GitHub Actions in seconds.

[![npm](https://img.shields.io/npm/v/stackforge)](https://npmjs.com/package/stackforge)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Quick Start

```bash
npx stackforge init
```

## What Gets Generated
- `apps/web` — Next.js 14 + TypeScript + Tailwind CSS
- `apps/api` — NestJS + TypeScript + Prisma
- `packages/shared` — Shared types and utilities
- Docker Compose (PostgreSQL + Redis)
- GitHub Actions (CI + Deploy)
- `.env.example` files for all services
- Turborepo + pnpm workspaces

## Tech Stack
`Node.js` · `TypeScript` · `Commander.js` · `Inquirer.js` · `Handlebars`

## Docs
See [PRD.md](PRD.md) for full architecture and feature roadmap.

## License
MIT
