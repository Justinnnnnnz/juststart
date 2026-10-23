# Development workflow

Date: 2026-10-22 | Status: workflow approved by Founder as the future operating basis; current activity remains public research and local Markdown only

## Idea to approved requirement

Idea → hypothesis with source and risk class → discovery evidence → product decision → PRD draft → UX/safety/privacy/feasibility review → explicit Founder approval. A feature list is not a PRD. Record alternatives, counterevidence and reasons to defer.

Future PRD template: problem and user/job; evidence; goal and non-goals; approved scope; journey; functional behavior; accessibility; safety/privacy controls; data lifecycle; measurable nonfunctional targets; analytics; acceptance scenarios; dependencies; rollout/rollback; unresolved decisions; version and approval reference. Each change to approved behavior requires an impact review and renewed approval if material.

## PRD to engineering issues

1. Trace each approved behavior to acceptance criteria with stable IDs.
2. Define module ownership and OpenAPI contract first: request/response schemas, errors, auth/ownership, validation, retries/idempotency where relevant, versioning and sensitive-data rules. Define AI output schemas and failure behavior too.
3. Review the contract with frontend/backend/AI/QA and freeze a task-specific version. Contract changes require a coordinated review, not unilateral edits.
4. Decompose into small vertical slices delivering a usable end-to-end outcome; avoid building every backend layer before validating a user flow.
5. Draft local issue specifications, dependency graph and test plan. Create GitHub Issues/Milestones only after explicit authorization.

Local issue template (not an external issue):

```text
Title / ID / owner / reviewers / priority / risk
Approved PRD version + approval reference / acceptance IDs
User story: As <user>, I want <behavior>, so <outcome>
Scope and exclusions / allowed files / dependencies
Contract version / data and safety controls
Given-When-Then acceptance criteria
Test and AI evaluation plan / observable evidence
Estimate range and uncertainty / rollback / blockers
Definition-of-done checklist / links to review and decision
```

Illustrative, unapproved acceptance scenario: Given an invalid AI output, when a next step is requested, then show an editable manual fallback without exposing raw model output. It is an example of testable wording, not authorization to build.

## Branch and pull request policy (future)

Use protected `main` and short-lived `codex/<issue>-<description>` branches after Git write authorization. No direct main commits, force-push or bypass of required review. The present documentation package stays uncommitted on the existing branch per Founder instructions.

PRs link approved requirement, contract and decisions; explain behavior, tests/evaluations, accessibility/safety/privacy impact, migration and rollback. Independent reviewer checks requirements and failure cases. Required checks pass; material objections resolved before merge. Merge/release authority is explicit and never inferred from a passing pipeline. No external PR or push in Phase 0 initial authorization.

## Agent assignment and conflict prevention

Use one coordinator and temporary task owners. A handoff names allowed paths, base revision, contract version, dependencies, acceptance criteria and reviewer. Independent frontend mock work, backend work against a frozen contract, UX specifications and synthetic QA cases may run in parallel after approval. Shared schema, migration, lockfile, contract and cross-cutting policy changes are serialized under a single owner.

Prefer separate branches/worktrees for authorized concurrent code work. Never have agents edit the same shared checkout paths concurrently. The coordinator integrates dependency order, reviews diffs, resolves conflicts with authors, then runs integration checks; no automatic last-write-wins. A conflict that changes approved behavior returns to Product/Founder. Agents must not approve their own implementation as independent review.

## Sprint planning and delivery

Proposed cadence: one-week iterations, adjustable to actual capacity. Discovery iterations produce decisions and evidence; they do not require code. Founder orders the backlog. Coordinator plans a clear outcome, dependencies, reviewer availability and risk buffer; limit work in progress to a small number of independently reviewable items. Do not estimate velocity before actual delivery data.

Definition of ready: approved scope and acceptance criteria, known dependencies, review owner, bounded data/safety implications and contract/design ready where needed. During work, report blockers and evidence, not just percentage complete. End with demonstration or document review, acceptance, metric/guardrail review and a short retrospective. Carry unresolved work visibly; no silent scope reduction.

## Quality and delivery

QA maps acceptance IDs to tests. Use JUnit/Mockito for business behavior, Testcontainers for PostgreSQL/integration, OpenAPI contract validation, Playwright for critical browser paths, manual accessibility checks and synthetic AI evaluation where appropriate. No tests or application scaffolds are required for this Markdown-only package; validate paths, completeness, references and scope instead.

For future AI changes pin model/prompt/schema/policy versions; test malformed output, unavailable provider, timeouts, safety boundaries and prompt injection. Target latency/cost and regression thresholds must be approved before implementation. Separate product usefulness, deterministic API correctness and probabilistic AI behavior.

Future CI: static checks, type/build, focused unit/integration/contract/E2E checks, dependency/security review and versioned AI evaluations as applicable. Secrets remain outside source; Docker images pin dependencies. Operations defines consented logging, monitoring, cost limits, rollback and incident ownership before release. CI/CD and deployment configuration are not created in this phase.

## Decision and change control

Use [decision register](../organization/decision-rights.md) with PDR/ADR IDs. Version docs through future reviewed Git changes. Every feature links evidence → PRD → acceptance IDs → issue → PR → tests/evals → release decision. “Done” follows the [completion standard](definition-of-done.md); approved implementation, merge, deployed and accepted are distinct states.
