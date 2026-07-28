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
load-testing tooling and CI. Its TypeScript AI gateway presents one authenticated
API across Gemini, OpenAI, OpenRouter, Ollama, and LocalAI, with text and image
inputs, separate system instructions, provider routing, and normalized reasoning
controls.

`TypeScript` · `FastAPI` · `Go` · `PostgreSQL` · `Prisma` · `Docker` · `Multi-provider AI`

### [BoomBoom](https://github.com/ismaproco/boomboom)

A full-stack markets dashboard with persisted background jobs, bounded data
ingestion, explicit operational controls, and an OpenAPI-generated client. Its
test suite covers storage, queues, services, API routes, and portfolio logic.

`React` · `TypeScript` · `Bun` · `Elysia` · `SQLite` · `OpenAPI` · `Playwright`

### [Escriba](https://github.com/ismaproco/escriba)

A writing assistant with an AI orchestration pipeline for context-aware
batching, prompt-budget selection, configurable detection and rewriting, and
piecewise score calibration. Its backend protects provider credentials, bounds
concurrency, retries transient failures, records full analysis evidence, and
checkpoints long-running benchmark jobs for recovery. It supports SQLite locally
and PostgreSQL for shared deployments.

`React` · `TypeScript` · `Express` · `SQLite` · `PostgreSQL` · `Docker` · `LLM orchestration`

### [Casa Mapa](https://github.com/ismaproco/casa-m)

A local-first, bilingual explorer for Bogotá apartment listings. It separates a
validated static-data pipeline from private browser persistence and includes
typed routing, unit tests, browser tests, and a complete local verification
workflow.

`React` · `TypeScript` · `TanStack Router/Query` · `Dexie` · `Playwright`
