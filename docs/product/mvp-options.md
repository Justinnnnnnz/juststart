# MVP options and recommendation

Date: 2026-10-22 | Status: Founder approved priority validation of A and preservation of B/C; concrete scope and implementation are not approved

## Comparison

| Dimension | A — Lightweight task-start assistant | B — Start + AI focus companion + immediate rewards | C — Broader ADHD life-management platform |
| --- | --- | --- | --- |
| Core value hypothesis | Move from being stuck to a first manageable action | Help start and sustain a short work session | Coordinate tasks, routines and longer-term life goals |
| Candidate scope | Short task input; one editable next step; optional brief attempt; progress/pause/exit; manual fallback | A plus bounded focus sessions, optional AI check-ins, session resume and opt-in acknowledgment/XP | B plus broader planning, capacity preferences, routines, integrations, analytics and personalization |
| Explicit exclusions | Full planner, calendar integration, XP economy, companion chat, therapy, diagnostic or medication features | Human matching/video, open-ended therapy, punitive streaks, broad life planner | Still excludes diagnosis, prescribing and autonomous therapy; modules require separate validation |
| Complexity / cost | Relative S–M; generation reliability, usable flow and safety still require work | Relative M–L; session lifecycle, notifications, state and recurring AI cost | Relative XL; integration, privacy, synchronization, personalization and operations multiply |
| Product risks | Generic output, another unused tool, no advantage over template | Distraction, anthropomorphism, pressure, dependency and reward fatigue | Scope creep, overwhelming setup, extensive sensitive data and unclear core value |
| Differentiation hypothesis | Immediate low-burden support when stuck | Adjustable support through the attempt and after interruption | Connected execution support across daily contexts |
| Verification | Compare A with current method and manual template; observe start, effort and useful action | Test incrementally: A vs A+timer, then optional AI check-in, then reward; isolate effects | Validate each job separately; test cross-context demand and integration necessity before breadth |
| Dependencies | Approved problem/PRD, safety content, simple UX, data boundary, eval/fallback | Core A signal plus explicit companion/reward approvals and cost controls | Repeated core use, approved data governance, sustainable operations and validated module demand |

No credible calendar or budget estimate exists until user evidence, acceptance criteria, staffing, review availability and infrastructure decisions are known. Relative sizes are planning judgments; do not turn them into delivery promises.

## Recommendation: validate A first

A tests the most central assumption with the fewest moving parts. Begin with manual research/prototypes after the appropriate approval; do not assume an LLM is necessary. Investigate interruption recovery in discovery and include it in A only if evidence justifies the extra state and scope. B is a conditional follow-up; C is a long-term exploration, not an initial backlog commitment.

A possible future vertical slice is intention → editable safe first action → reported attempt outcome. This is illustrative, not an approved requirement. A future PRD must specify exact behavior, exclusions, accessibility, data retention, latency/cost targets and acceptance criteria before coding.

## Proposed review criteria

Select A if the start moment is frequent, underserved and improves under a small-action prototype without added burden. Reconsider if the manual template is equally useful, existing products solve the job well, users need human support, or the flow increases distress. Consider B only after evidence shows that sustaining/restarting rather than selecting a next action is the limiting problem. Consider C only after several independently validated jobs and a clear reason they must share one product.

Founder has selected A for priority validation, adult ADHD users, English-market priority and public-source/local-document research. Specific geography, first task context, concrete feature scope and participant-study/resource approvals are still needed. Selecting A as a direction does not authorize implementation, recruitment, spending or Phase 1.

## Research-round candidate scope (recommendation only)

1. Enter one short intention without first reconstructing a full task list; a prefilled fictional example/manual path supports exploration.
2. Present one concrete editable next action with clear uncertainty and no mandatory long plan. Offer “Make smaller” or manual edit; ask a targeted clarification only when necessary for a useful/safe action.
3. Let the user elect a bounded attempt or simply act, pause or leave. Do not force a timer or a therapeutic exercise.
4. Include an in-attempt pause/return card retaining only the current approved step and optional user-written bookmark. Cross-session persistence is a separate data/scope decision; no passive distraction detection.
5. Offer optional progress reporting and neutral acknowledgment. “I started” is self-report, not observation; attempt election is not an actual start.
6. Define manual fallback, unsafe/irrelevant output handling, editable/deletable context and accessible English UI. Keep future localization capability without making bilingual launch a requirement.

This makes a minimal recovery concept explicit for prototype validation, rather than expanding A into ongoing AI companionship. Compare fresh start only vs start plus a same-attempt return card before adding persistent state. Strong overlap with Goblin Tools Taskmaster means this is a proposed experience improvement, not a demonstrated unique category. See the [cross-reviewed synthesis](../research/phase-00-research-synthesis.md) and [concrete UX artifact](../research/adhd-ux-and-initial-prototype.md).

Retain B: AI body doubling, optional check-ins, immediate rewards and personalized gamification. Retain B/C: professionally reviewed CBT/ACT skills, explicit energy/emotion adaptation and user-controlled behavioral preferences. Retain C: daily AI planning, learning/work assistance, longer-term life management and cross-context strategies. Each requires separate evidence and scope approval.
