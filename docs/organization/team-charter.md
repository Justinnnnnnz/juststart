# Team charter

Date: 2026-10-22 | Status: organization approved by Founder as the operating basis; no implementation/release authority granted

## Lean structure

The Founder owns priorities and approval. One AI delivery coordinator integrates work and maintains the backlog and decision register. Product/UX, Engineering, and Assurance are temporary workstreams, not permanent agent departments. Specialists are invoked only when a bounded task requires their expertise. Assurance combines QA, safety and privacy coordination, but qualified human reviewers are required where specified.

| Function | Responsibility | Inputs → outputs / main deliverables | Dependencies | Founder approval required |
| --- | --- | --- | --- | --- |
| Product Management | Problem selection, positioning, prioritization, PRD, roadmap, backlog, stories and acceptance criteria | Vision, evidence, constraints → hypothesis register, PRD, release scope | UX, business, safety, engineering estimates | Target segment, requirements, MVP, roadmap and scope changes |
| UX Research & UI/UX | Ethical research, journey, information architecture, flows, wireframes, design system, mobile usability and accessibility | Research questions, consent constraints, PRD → study plan, synthesis, prototypes and accessible specifications | Product, safety, privacy, frontend | Recruitment/data protocol, significant interaction model, final UX scope |
| Behavioral Science & Safety | Evidence appraisal, support-strategy boundaries and risk review | Research, candidate copy/flows → evidence ledger, risk assessment, content review and safety evaluation cases | UX, AI, QA, qualified professional | Psychological support scope, claims, residual material risk; expert review also mandatory |
| Engineering: Architect / Tech Lead | Module boundaries, API contracts, data design, ADRs and integration | Approved PRD, risk controls → architecture, contracts, slices, technical decisions | All engineering roles, privacy, operations | Stack, vendors, authentication, data hosting, major architecture |
| Engineering: Frontend | Accessible responsive flows and client state | Approved UX and contracts → interface, component documentation and tests | UX, backend, QA | Material scope or UX deviation |
| Engineering: Backend | Business rules, authorization, persistence and API implementation | Approved contracts/data model → modules, migrations, integration tests | Architect, frontend, privacy, operations | Material data/security or architecture deviation |
| Engineering: AI | Model adapter, structured outputs, prompt versions, validation and fallback | Approved support strategy, contract, eval cases → constrained AI integration and eval report | Safety, backend, QA, privacy | Provider, data transfer, model behavior boundary and cost cap |
| QA & AI Evaluation | Independent acceptance, regression, API, integration, E2E and AI behavior evaluation | Requirements, contracts and changes → test plan, defect reports, release recommendation | Engineering, UX, safety | Material risk exceptions and release; QA cannot waive critical failures |
| Security & Privacy | Threat model, least privilege, data lifecycle, security testing and jurisdiction questions | Data map, vendors, architecture → controls, privacy review, deletion plan and legal questions | Engineering, safety, operations, counsel | Collection/retention, subprocessors, jurisdiction, residual material risks |
| DevOps & Operations | CI/CD, Docker, deployment, logs, monitoring, cost and incidents | Approved architecture/SLOs → pipeline, runbooks, rollback and cost reports | Engineering, QA, security | Service enablement, spending, environment exposure and deployment |
| Data & Analytics | Operational definitions, instrumentation, experiments and feedback analysis | Hypotheses, consent and privacy constraints → metric dictionary, analysis plan, aggregate findings | Product, UX, privacy, engineering | Event collection, experiments, success thresholds |
| Growth & Business | Market positioning, pricing hypotheses, landing-page plan, acquisition and business viability | Discovery evidence and unit-cost estimates → business assumptions, message tests, pricing research | Product, safety, analytics | Pricing, claims, publication, paid acquisition and commercial commitments |

## Working agreements

Every task has one accountable owner; reviewers supply evidence and can request rework. Owners do not self-certify independent review. The coordinator resolves routine sequencing and escalates scope, safety and architecture disagreements with options and consequences. The Founder can choose among safe proposals but approval cannot substitute for required clinical/legal review or an unresolved critical safety blocker.

No real clinicians, users or research sessions have been recruited. For this explicitly authorized discovery round, three temporary independent Subagents perform Product, UX and Behavioral Science research in parallel and then cross-review. They are not permanent departments or qualified clinical reviewers. Actual contributions and review findings are recorded in the research synthesis.

A handoff contains purpose, source documents, allowed paths, decision limits, expected artifact, acceptance criteria, dependency version and review owner. Tasks end with a concise evidence-backed handoff, not merely a claim of completion.
