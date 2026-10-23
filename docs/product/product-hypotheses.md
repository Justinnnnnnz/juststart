# Product hypothesis and feature register

Date: 2026-10-22 | Status: all feature hypotheses unvalidated; no MVP requirements approved

## Reading the register

Value and cost are relative planning judgments, not market evidence or delivery estimates. Cost S/M/L reflects implementation, assurance and operations together. Confidence is low unless a cited source supports the exact claim. Priority means research sequence: R0 = first, R1 = after core signal, R2 = defer. Clinical evidence does not establish effectiveness of an AI implementation.

| ID / feature | User-value hypothesis | Cost | Main risk | Dependencies | Research priority / falsification test |
| --- | --- | --- | --- | --- | --- |
| H01 AI task management / planning | Less manual planning burden | L | Overplanning, unrealistic schedule, calendar exposure | Task model, explicit user control, integrations if later approved | R1; compare with current method; reject if setup exceeds benefit |
| H02 Complex-task breakdown | One concrete action reduces overwhelm | M | Wrong, unsafe or excessive steps | Constrained generation, edit/undo, safe task boundaries | R0; compare small-step proposal with manual next action |
| H03 Starting-difficulty assistant | Context-specific prompt helps users begin | M | Nagging, false psychological inference | Blocker choice, H02 or manual fallback, optional feedback | R0; measure observed/self-reported start and pressure |
| H04 AI body doubling / focus companionship | Optional check-ins sustain effort | L | Dependency, distraction, confusing AI with human support | Session state, safety policy, check-in controls, model budget | R1; compare timer-only vs labeled AI support; human coworking evidence cannot transfer |
| H05 Immediate rewards / XP | Acknowledgment makes action feel worthwhile | M | Shame, compulsive loops, reward fatigue | Progress model, opt-out, no loss penalties | R1; compare neutral acknowledgment vs optional reward; reject if pressure grows |
| H06 Interruption recovery | Remembering the next step lowers restart cost | M | Stale context, sensitive memory retention | Minimal saved context, edit/delete and user-triggered resume | R0 research; test interruption scenario before expanding A |
| H07 Energy/state-adaptive plans | User-chosen capacity yields feasible actions | M–L | Over-inference, intrusive mood collection | Optional self-description, transparent rules, no passive sensing | R1; compare simple user choice with fixed step size |
| H08 CBT-informed skills | Practical planning/problem-solving skills may help | L with review | Therapy drift, invalid transfer of evidence | Exact skill evidence, professional review and scope controls | R1 evidence review; do not ship a therapy protocol |
| H09 ACT-informed values/action skills | Optional values reflection may aid meaningful action | L with review | Moral pressure, unsupported ADHD/AI claim | Adult ADHD evidence appraisal, qualified review | R2; evidence and acceptability before prototype |
| H10 Emotional support / EFT exploration | Acknowledgment may reduce friction | L with review | Mislabeling emotion, trauma processing, ambiguous EFT | Clarify emotion-focused therapy vs emotional freedom techniques; separate evidence searches | R2; do not infer emotional state or equate methods |
| H11 Personalized intervention selection | User-selected preferences improve fit | L | Sensitive profiling, unstable or biased advice | Proven strategies, consent, explainable selection, evaluation | R2; prefer explicit preferences before learned recommendations |
| H12 Behavior-pattern analytics | Optional reflection reveals useful patterns | L | Surveillance, misleading causality, diagnosis inference | Consented minimal events, sufficient data, deletion, uncertainty labels | R2; test aggregate summaries before person-level modeling |

## Cross-cutting assumptions

- H13: users prefer a low-friction start flow to adding another planner. Test against actual existing workflows.
- H14: AI adds useful value over a deterministic small-step template. If it does not, remove AI from the core path.
- H15: users voluntarily return after novelty fades. Short prototype studies cannot establish retention.
- H16: a sustainable price can cover provider and support costs without coercive monetization. No willingness-to-pay data exists.

For each future test record participant context, method, result, counterexamples, confidence, risks and next decision. Distinguish “not tested” from “failed.” See [discovery](discovery-plan.md) and [MVP comparison](mvp-options.md).

## Public-research round update

Audience and direction are now Founder-confirmed: adults with ADHD, English market first with future English/Chinese capability, A first for validation, B/C preserved. Public evidence can strengthen plausibility and reveal constraints; it does not validate H01–H16 for JustStart. See the [research synthesis](../research/phase-00-research-synthesis.md) for disagreements and decision rationale.

| Hypothesis | Updated decision implication | Evidence limitation / next falsification |
| --- | --- | --- |
| H02/H03/H13 | Prototype an immediate one-action path alongside users' existing tools; do not require importing a planner | Goblin Tools Taskmaster already overlaps; compare burden and useful action against it and a manual template |
| H06 | Research a tiny same-attempt return card with optional editable bookmark, no passive monitoring | Accessibility guidance supports recovery; incremental value and privacy/persistence tradeoff untested |
| H04 | Preserve B; do not claim AI body doubling has no research at all | Early small VR-task research is not evidence that everyday conversational companionship works; compare with quiet timer/human alternatives |
| H05 | Separate neutral acknowledgment in A from a rewards/XP system in B | Reward-response findings do not specify a universally beneficial gamification mechanic; test pressure and novelty loss |
| H08 | Retain reviewed practical skills and professional gate | Digital CBT trials exist; exact intervention/comparator/outcome matters and cannot transfer to a generated one-step assistant |
| H09/H10 | ACT and emotion support remain bounded future investigations; EFT remains ambiguous/excluded pending clarification | Preliminary/indirect work does not establish an ADHD-specific AI therapy claim |
| H11/H12 | Prefer explicit preferences and minimal user-selected context to inferred psychological profiling | No evidence here supports collecting sensitive behavioral histories or building prediction models |
| H14 | AI value must be earned through context-specific adaptation | If a fixed template is equally useful with less waiting, reading, error or cost, simplify/remove AI from the critical path |

New product experiments (all unvalidated): a user-controlled “smaller version” ladder; a temporary restart bookmark; an optional “good enough for this attempt” stopping boundary; and explicit user preferences for brief/silent support. No experiment has run. They are design candidates, not approved features.
