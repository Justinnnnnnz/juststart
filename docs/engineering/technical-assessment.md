# Preliminary technical assessment

Date: 2026-10-22 | Status: preferences assessed; no stack or architecture approved

## Proposed shape

A responsive Next.js/React/TypeScript client and a Java/Spring modular-monolith API with PostgreSQL fit the stated preference. Candidate backend boundaries are tasks/attempts, AI orchestration and consent/preferences; add sessions/rewards only if their product scope is approved. Keep business rules in the backend and provider credentials server-side. A separate frontend runtime plus one modular backend is not a microservice strategy. No repositories, applications or infrastructure are scaffolded here.

## Tradeoffs and open checks

| Preference | Potential fit | Cost / risk / approval question |
| --- | --- | --- |
| Next.js / React / TypeScript | Responsive browser delivery and typed UI | Separate Node runtime, server/client boundary and accessibility; compare need for SSR vs simpler client before approval |
| Java 17 / Spring Boot 3.x | Familiar typed backend, mature authorization/testing | Two-language operations overhead; exact supported release, Java lifecycle and dependency/security maintenance must be verified before pinning |
| PostgreSQL | Transactions and clear ownership for structured state | Decide minimal data, deletion/backups, hosting region, migrations and access model first |
| LLM API + structured output | Candidate small-step generation behind a provider adapter | Schema validity does not ensure safe/useful content; validate output, bound retries, timeout, redact logs and provide manual fallback |
| REST / OpenAPI | Frontend/backend contract and independent tests | Contract/version owner; errors, authorization and generated client policy must be agreed |
| JUnit / Mockito / Testcontainers / Playwright | Layered behavior/integration/browser verification | Docker-capable CI, reproducibility and meaningful test boundaries; avoid excessive mocking |
| Docker / GitHub Actions | Reproducible packaging and checks | Secret management, runner cost, image lifecycle, deployment and provider approvals pending |

Official [Spring Boot 3.5 system requirements](https://docs.spring.io/spring-boot/3.5/system-requirements.html), accessed 2026-10-22, identify Java 17 as a minimum. This is compatibility information, not assurance of lifecycle support or a recommendation to freeze on 3.x. Recheck security/support policy at the Phase 2 decision.

Official [Next.js installation documentation](https://nextjs.org/docs/app/getting-started/installation), accessed 2026-10-22, identifies a Node.js runtime requirement. Resolve the chosen Next.js/React/Node versions together at approval time; do not install an unpinned latest version as part of discovery.

## Alternatives worth evaluating

A manual or deterministic prototype can test the starting problem before AI infrastructure. A simpler single-runtime stack might reduce operational load, but switching from the Founder's Java preference needs an explicit tradeoff decision. Choose a modular monolith before considering microservices; no demonstrated scaling or team-boundary need justifies distributed backend services now.

## Phase 2 decision packet

Confirm MVP flow, concurrency/latency assumptions, auth approach, retention, model/provider data terms, region, maintenance lifecycle, accessibility, threat model, cost ceiling and team expertise. Compare options, document an ADR and seek Founder approval. Use synthetic data for any separately approved technical spike. No dependency installation, benchmark, cost commitment or provider account connection is authorized now.
