# Ismael Jimenez

Senior full-stack engineer focused on turning complex product domains into
maintainable systems. Over 19 years, I have worked across browser applications,
backend services, distributed workflows, and cloud infrastructure.

My strongest work tends to sit at the boundaries: translating domain rules into
clear service contracts, making failure modes explicit, and giving teams enough
automation and observability to change software safely.

## What I optimize for

- Domain boundaries that keep business rules independent from frameworks.
- Typed contracts between React clients, APIs, events, and persistence.
- Reliable asynchronous processing with explicit retries and idempotency.
- Infrastructure that is reviewable, repeatable, and operated with evidence.
- Tests that protect behavior and architecture rather than implementation
  details.
- Simple designs first, with complexity added only for a measured reason.

## Selected work

### [Casa Mapa](https://github.com/ismaproco/casa-m)

A local-first, bilingual explorer for Bogotá apartment listings. It separates a
validated static-data pipeline from private browser persistence and includes
typed routing, unit tests, browser tests, and a complete local verification
workflow.

`React` · `TypeScript` · `TanStack Router/Query` · `Dexie` · `Playwright`

### [Chess Review](https://github.com/ismaproco/chess-review)

A client-side PGN analysis tool that integrates Stockfish through Web Workers.
The engine protocol, sequential game analysis, FEN-based caching, navigation
state, and presentation are kept in distinct modules.

`React` · `TypeScript` · `Web Workers` · `Stockfish` · `chess.js`

### [Hono API Template](https://github.com/ismaproco/hono-template)

An experimental TypeScript API composition using Hono, PostgreSQL, Prisma, JWT,
MinIO, and Docker Compose. Its README documents both the architectural choices
and the hardening work still required before production use.

`TypeScript` · `Hono` · `PostgreSQL` · `Prisma` · `Docker`

## Current direction

I am preparing a public backend case study that brings together the parts of my
professional work that smaller frontend repositories cannot demonstrate:
domain-driven FastAPI services, event-driven processing, AWS infrastructure
defined with Terraform, operational telemetry, and failure-oriented testing.

## Elsewhere

- [Website](https://isma.club/)
- [GitHub repositories](https://github.com/ismaproco?tab=repositories)
