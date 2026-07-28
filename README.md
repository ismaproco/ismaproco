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

### [Coersu Store](https://github.com/ismaproco/coersu-store)

A revisioned content and feature-management API built around external IDs,
idempotent mutations, soft deletion, and an incremental change feed. The same
PostgreSQL-backed contract has TypeScript, Go, and FastAPI implementations, plus
load-testing tooling and CI.

`TypeScript` · `FastAPI` · `Go` · `PostgreSQL` · `Prisma` · `Docker`

### [BoomBoom](https://github.com/ismaproco/boomboom)

A full-stack markets dashboard with persisted background jobs, bounded data
ingestion, explicit operational controls, and an OpenAPI-generated client. Its
test suite covers storage, queues, services, API routes, and portfolio logic.

`React` · `TypeScript` · `Bun` · `Elysia` · `SQLite` · `OpenAPI` · `Playwright`

### [Escriba](https://github.com/ismaproco/escriba)

A writing assistant whose backend owns provider credentials, request
concurrency, retries, durable benchmark jobs, and analysis history. It supports
SQLite for local operation and PostgreSQL for shared deployments, with explicit
migration and recovery paths.

`React` · `TypeScript` · `Express` · `SQLite` · `PostgreSQL` · `Docker`

### [Casa Mapa](https://github.com/ismaproco/casa-m)

A local-first, bilingual explorer for Bogotá apartment listings. It separates a
validated static-data pipeline from private browser persistence and includes
typed routing, unit tests, browser tests, and a complete local verification
workflow.

`React` · `TypeScript` · `TanStack Router/Query` · `Dexie` · `Playwright`

## Current direction

These public projects now show API design, durable jobs, revisioned data,
idempotency, cross-runtime implementation, and operational testing. They do not
yet include a representative public AWS/Terraform system; that remains the most
important portfolio gap relative to my production experience.

## Elsewhere

- [Website](https://isma.club/)
- [GitHub repositories](https://github.com/ismaproco?tab=repositories)
