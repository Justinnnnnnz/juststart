# Decision rights and approval register

Date: 2026-10-22 | Status: organization/workflow accepted as operating basis; approval register updated from explicit Founder instructions

## Authority matrix

| Decision | Proposer | Required consultation | Final authority |
| --- | --- | --- | --- |
| Local Phase 0 documentation and public desk research | Coordinator | Relevant roles | Already authorized within current limits |
| Target user, problem, MVP, PRD, roadmap, acceptance changes | Product | UX, engineering, safety | Founder |
| Recruitment, participant consent, sensitive data or experiments | UX / Analytics | Privacy, safety; qualified reviewers as appropriate | Founder after review |
| Psychological methods, support scripts, clinical claims | Safety | Qualified mental-health professional; counsel for regulated claims | Founder within professionally reviewed boundaries |
| Stack, providers, architecture, hosting/authentication, major data changes | Tech Lead | Privacy, security, operations | Founder |
| Routine reversible implementation within an approved PRD/ADR | Task owner | Independent reviewer | Tech Lead within delegated authority; no current coding authority |
| External issues/projects, commits, pushes, publication, service activation, spending or deployment | Coordinator / Operations | Relevant reviewers | Explicit Founder authorization for the action |
| Release or phase transition | Coordinator | Product, QA, safety, privacy and engineering | Founder |
| Stop unsafe work | Any role | Inform coordinator and Founder | Immediate stop allowed; restart requires resolved controls and appropriate approval |

## Decision protocol

Prepare the decision with context, evidence links, alternatives including doing less, user impact, costs/risks, reversibility and recommendation. Statuses: proposed → under review → approved / rejected / deferred → superseded. Silence, agent consensus and a completed draft never mean approval. Record the Founder's explicit response verbatim or by faithful reference with date and exact scope. Material changes reopen approval.

Product decisions use PDR IDs; technical decisions use ADR IDs; cross-cutting governance uses DEC IDs. This file is the initial register. Create separate versioned records only when needed, with backlinks here. Proposed template:

```text
ID / title / date / status / owner
Question and constraints
Evidence (date, source, limitations)
Options, costs, safety/privacy implications
Recommendation and affected documents
Required reviewers and actual findings
Founder decision, date, scope and source instruction
Consequences, revisit trigger and superseded record
```

## Initial register

| ID | Question / proposal | Status | Required next action |
| --- | --- | --- | --- |
| DEC-000 | Initial local Phase 0 documents; prohibited actions as specified | Authorized by initial Founder request, 2026-10-22 | Deliver package, then stop |
| PDR-001 | Adult ADHD audience; English market first, future English/Chinese capability | Approved as discovery direction by Founder, 2026-10-22 | Specific launch country and narrow first task context still need selection |
| PDR-002 | Prioritize MVP A validation; preserve B/C as long-term vision | Approved direction by Founder, 2026-10-22 | Concrete feature list, PRD, implementation and phase transition remain unapproved |
| PDR-003 | Public-source research, independent PM/UX/Behavioral Subagents, local reports/static wireframes and cross-review | Approved explicitly by Founder, 2026-10-22 | No recruitment, sensitive-data collection, paid services, code, deployment, commit/push; participant protocols and metrics remain proposals |
| PDR-004 | Psychological support boundary; ACT/EFT held pending appraisal | Proposed | Founder plus qualified professional review before use |
| ADR-001 | Next.js/TypeScript + Java/Spring + PostgreSQL modular monolith | Preference under assessment | Confirm versions, lifecycle, team capacity, vendors and ADR in Phase 2 |
| DEC-001 | Phase 1 entry | Not approved | Complete discovery evidence and explicit gate decision |
| DEC-002 | Use current organization and development workflow as operating basis | Approved by Founder, 2026-10-22 | Apply governance; concrete product, technical and release decisions remain gated |

## Founder review bundle

Review organizational rules, problem/segment, research plan, three MVP options, evidence gaps and resource assumptions. Approval of document structure permits only that structure. Authorizing further Phase 0 research does not approve recruitment, sensitive-data handling, Phase 1, coding, external GitHub changes, commits or spending unless explicitly included.

## Approval provenance for this round

The Founder explicitly stated in this chat that the initial organization and development workflow were accepted, specified adult ADHD and English-market priority with future Chinese/English capability, prioritized validation of A while retaining B/C, reviewed the proposed three-agent research plan, and then instructed actual parallel execution. The final instruction authorizes public research and local documents only and requires stopping for review afterward. These are human approvals recorded from this conversation, not agent-created approvals.
