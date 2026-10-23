# Phase 00 research synthesis and product recommendation

Research / review date: 2026-10-22 (America/Toronto). Owner: root coordinating Agent. Status: cross-reviewed public-source research and untested static design; Founder review pending. No participant validation, clinical sign-off, implementation or phase transition.

## Decision recommendation

Prioritize a narrow job: an adult with ADHD has already chosen a low-risk work/study or household task but is stuck before acting. Test whether JustStart can make the next useful action easier to choose, attempt and recover, alongside the person's existing planner. The first proposed scenario is an already-chosen writing/admin task; retain a household counterexample. This scenario selection remains a Founder decision, not an observed market segment.

Candidate promise: **“Bring one thing you want to start. Choose one manageable move. Come back without rebuilding the plan.”** It is a hypothesis, not a treatment or market claim. The proposed edge is lower end-to-end effort and better recovery, not the existence of task breakdown or AI. A useful result may involve less app use.

Recommend document/prototype validation of A with a complete manual/template path and optional contextual AI variant. Do not implement yet. Preserve B and C as long-term product horizons with explicit evidence and approval gates.

## Actual multi-agent execution and ownership

Three independent Subagents were actually created through the collaboration tools and worked concurrently. They inherited the project context, performed their own public-source research and wrote distinct files. The root Agent did not substitute three personas inside one report.

| Actual task identity | Independent deliverable | Actual work |
| --- | --- | --- |
| `/root/product_manager` | [Adult ADHD needs and competition](adult-adhd-needs-and-competition.md) | Needs/barrier model, scenario choices, current official competitor capabilities, AI-versus-template value, candidate scope, counterevidence and primary-source ledger |
| `/root/ux_researcher` | [ADHD UX and initial prototype](adhd-ux-and-initial-prototype.md) | Adult ADHD usability evidence, accessibility guidance, journey, IA, two home wireframes, initiation/re-entry diagrams, states/microcopy, manual/AI paths, localization and falsifiers |
| `/root/behavioral_science` | [Behavioral evidence and safety](behavioral-evidence-and-safety.md) | CBT/ACT/behavioral activation/rewards/implementation intentions/body-doubling appraisal, dated evidence ledger, safe interaction translations, professional gates and synthetic safety cases |
| `/root` | This synthesis and shared-document updates | Verified repository, assigned non-overlapping ownership, shared useful source leads, read all reports, checked key sources, reconciled findings and updated governance/product/roadmap documents |

No permanent agent departments were created. No new Git worktrees/branches were needed for non-overlapping Markdown ownership. Source discovery was independent within a shared mandate, not blinded scientific replication. Agreement between AI reviewers is not an independent empirical finding or professional clinical review.

## Method and strength of conclusions

This is a targeted narrative desk review with current official product sources, primary studies, original reviews and accessibility guidance; it is not a systematic review, market census, hands-on competitor benchmark or user-research dataset. Individual report ledgers identify publication/access dates and abstract-only or access-blocked limitations. No JustStart interviews, studies, recordings, personal-post collection or real-user sensitive data occurred.

Distinguish **source-backed evidence**, **provider descriptions**, **our design inferences** and **untested hypotheses**. Many of the strongest design recommendations are sensible extrapolations rather than proven ADHD interventions. English-market priority is Founder-confirmed, but target country, exact task context and cultural transfer still need decisions. Future English/Chinese capability is retained without a bilingual-launch commitment.

A particularly relevant 2026 [HCI preprint](https://arxiv.org/html/2603.17258v2) reports interviews and speculative concepts, not outcomes from a working AI product. PM found template publication metadata and inconsistent method wording in the consulted manuscript, so we use it only as exploratory support and do not rank features from its preference table. A small [MyADHD usability study](https://formative.jmir.org/2022/10/e37137) motivates clarity and short text, but cannot establish a universal interface preference. Both checked 2026-10-22. Broader [W3C COGA guidance](https://www.w3.org/TR/coga-usable/) is supplemental accessibility advice, not adult ADHD efficacy evidence or a mandatory WCAG requirement.

## Why a list may not lead to a start

A task list stores an intention. Acting can still require interpreting the task, choosing a first feasible move, handling an unpleasant or uncertain commitment, obtaining missing material and recovering after interruption. This is our product model, not a diagnostic classification; the same person may need different support on different days. See PM and Behavioral report sources for the bounded evidence.

| Situation | Concrete response to explore | Important countercase |
| --- | --- | --- |
| The task is vague | One observable, editable first action and a stopping boundary | User already knows the action; more suggestions add friction |
| The task feels too large | Make the commitment smaller without generating a whole project | Trivial steps feel patronizing or produce no meaningful progress |
| A prerequisite is missing | One optional practical clarification; identify the missing item | The right response is help, accommodation or deferral rather than more decomposition |
| The user is interrupted | Redisplay current user-approved action; optional return cue | Cue maintenance exposes private context or costs more than recovery |
| Capacity is low | Pause/rest/stop is valid; no productivity pressure | A smaller task is not always a substitute for rest or professional care |

This explains a possible unmet job; it does not prove people need another app. Task lists can work well and must be included as serious alternatives.

## Competition: real overlap and an unproven opportunity

Official sources checked 2026-10-22 show substantial overlap: [Goblin Tools Taskmaster](https://goblin.tools/Taskmaster) already describes sequential tasks, estimated timers, next-task suggestions and breakdown when stuck; [Tiimo](https://www.tiimoapp.com/) advertises AI planning and execution-support tools; [Structured](https://structured.app/planning-assistance) advertises AI planning/Replan; [Finch](https://finchcare.com/) uses pet-framed self-care; [Focusmate](https://www.focusmate.com/how-it-works/) supplies human video coworking. Provider pages establish offers, not comparative quality or benefit.

We have not established that these products are difficult, clinically unsafe, ineffective or missing a particular flow. Potential gaps are questions: how much setup before action, whether a user must rebuild a plan, whether current task context survives interruption, whether support adds pressure, and whether the user can avoid irrelevant chat. Compare actual journeys before asserting superiority. The competitive test must include Taskmaster, not only an empty to-do list.

The tentative opportunity is a small, low-demand support layer usable with an existing planner. Switching costs, willingness to pay and sustained benefit are unknown. Digital therapeutic alternatives such as attexis are relevant to professional/structured support, not interchangeable with a lightweight consumer task-start aid.

## Concrete candidate A experience

The detailed artifact is the [UX report](adhd-ux-and-initial-prototype.md); it contains journey, IA, home wireframes, initiation and interruption flows and state specifications. All are untested static proposals.

**Default path:** enter a short intention → use an editable practical template or own action → choose “Try this step” → act outside the app → optional outcome. AI is an explicit alternative with data disclosure before any future transmission, not a required second mode-selection screen. Manual mode must not silently send text to a model. Default ordering is a prototype variant, not a final product decision.

Synthetic example: “Draft a meeting agenda” → “Open a blank note and type one agenda topic.” Offer edit, make smaller or stop. A meaningful action advances the job or a necessary prerequisite; merely opening the app is not progress.

On interruption, show the last user-approved action wording, not a claim that the action occurred. An optional note such as “Next: add the budget question” can be explored. A same-attempt card is the initial candidate; cross-session/cross-device persistence and automatic memory require separate need, privacy and scope decisions. If context is unavailable, state that honestly instead of inventing history.

Candidate feature list for Founder review:

1. One task input and an own-next-action bypass; no mandatory planner rebuild, diagnostic/mood questionnaire or account in the static concept.
2. One concrete editable action, bounded repair and optional clarification only where useful/safe.
3. A quiet attempt card with no default timer, forced conversation or background distraction detection.
4. Pause/stop/skip and same-attempt orientation; optional return note as a separate comparison.
5. Optional truthful progress report and neutral acknowledgment; no reporting reward, streak debt or punitive outcome.
6. Complete manual fallback, clear AI limitations/data handling and accessible English interaction with future localization capability.

Exclude companion sessions, XP economy, calendar integration, passive emotion inference, clinical exercises and broad personalization from A by default. Exclusion from this candidate scope does not remove them from the vision.

## What AI must add

Rules can display a saved action, provide a smallest-step prompt and redisplay a bookmark immediately. The possible AI advantage is interpreting messy language or adapting an action to an explicitly stated obstacle. This is unvalidated. Latency, reading/correction effort, wrong assumptions, private text transfer and cost can outweigh it.

Static examples can test comprehension, acceptability and the plausibility of the flow. They cannot estimate real generation quality, latency, model failures, cost or incremental benefit. A future separately authorized model evaluation would use synthetic cases; actual comparative usefulness and repeated use would require separately approved participant research. There is no live model integration or evaluation result in this round.

Measure total entry-to-action time including typing, mode/disclosure reading, generation and editing, as well as the defined attempt window. Record intention markers, self-reported action, observed action and missing outcomes separately. Leaving the app can mean useful action or abandonment; neither should be assumed. If template/manual is equally useful with lower burden, keep AI optional, simplify the product or reconsider the direction.

## Behavioral methods: safe product translations and limits

The [Behavioral report](behavioral-evidence-and-safety.md) contains the full population/comparator/outcome/limitation ledger and exact candidate wording. These are product suggestions, not approved therapeutic scripts.

| Method | Reason to investigate | Candidate interaction / boundary |
| --- | --- | --- |
| CBT-related practical skills | Adult ADHD structured packages have trial/guideline support | Editable next step or missing-prerequisite question; do not claim an isolated AI prompt reproduces CBT |
| ACT | Preliminary and heterogeneous work, including feasibility evidence | Later optional self-chosen action/values or flexibility card, with skip/rest and qualified review; no pressure to endure unsafe demands |
| Behavioral activation | Depression evidence does not directly establish ADHD efficacy | User-chosen small activity/rest; do not brand this as depression therapy or a validated ADHD BA protocol |
| Immediate feedback/rewards | Reward-timing association is not proof of a good XP system | Neutral acknowledgment in A; optional personalized rewards in B only if useful without pressure or distraction |
| If-then/restart cues | Some relevant mechanism evidence is indirect, including child lab work | User-owned return cue; no adult treatment or normalized-executive-function claim |
| AI body doubling | Preliminary specialized evidence exists; broad everyday benefit unknown | B: transparent quiet AI presence, user-chosen check-ins, exit and no claim to see/verify work or equal a human companion |

Two important counterexamples prevent overly broad negative claims. A 2026 [attexis RCT](https://doi.org/10.1017/S0033291726103390) studied a defined digital CBT/mindfulness program with usual care, not generative AI or a smallest-step template comparator; self-report/unblinded design and developer involvement limit inference. A 2025 [VR body-doubling preprint](https://arxiv.org/abs/2509.12153) has a small task-specific comparison, not durable conversational-coach evidence. Both checked 2026-10-22. Neither validates JustStart.

No diagnosis, medication advice, psychotherapy, trauma processing, coercive rewards or inferred health profile. Urgent danger suspends productivity/reward flows and requires a professionally reviewed human-help route; no invented resources or monitoring promises. Qualified mental-health/privacy/legal reviews remain separate from AI cross-review. EFT remains excluded pending clarification and evidence appraisal.

## Conflicts, actual cross-review and resolutions

| Reviewer → artifact | Finding | Resolution / remaining uncertainty |
| --- | --- | --- |
| UX → PM | Medium: time-to-action clock could hide setup; “confirmed step” could imply performed action; retention ambiguous. Low: explicit skip missing | PM revised end-to-end time, user-approved wording vs execution, session vs persistent scope and Skip/unknown outcomes |
| PM → UX | Medium: home and mode/disclosure flow inconsistent; static AI examples could be mistaken for real AI evaluation. Low: historical UX findings could imply current market gap | UX aligned template/own-step/optional-AI paths, separated static vs model/live evaluation, linked current competitor matrix |
| Behavioral → UX | Medium: generic elevated-risk manual fallback unsuitable for immediate danger. Low: low-capacity variant should allow rest | UX separated clinical/dangerous and urgent states, suspended productivity/rewards for urgent danger and added rest/stop |
| Behavioral → PM | Medium: include clinical digital alternative and 2026 evidence, without transferring efficacy | PM added attexis as a distinct digital-therapeutic alternative with trial limitations; no AI-efficacy inference |
| PM + root → Behavioral | Medium: two-minute example looked like default and restart cue could imply persistent memory. Low: neutral non-start/skip | Behavioral revised to no default timer, optional duration experiment, same-attempt vs retained cue and neutral unknown/non-start outcomes |
| Root → all reports/shared docs | Need a coherent minimal A without deleting B/C; stronger novelty or treatment language unsupported | Common candidate A above; explicit long-term horizons; no proven uniqueness or product efficacy; full validation remains open |

No unresolved blocker to delivering these research documents was identified. That is not release readiness. Disagreements left for evidence: whether default template is appealing enough, whether AI adds worthwhile adaptation, whether a return note is worth its burden and whether ongoing presence rather than next-action selection is the real bottleneck. We did not turn reviewer consensus into a claimed finding about users.

## Long-term vision retained

B retains AI body doubling, optional immediate rewards and personalized gamification. B/C retain professionally reviewed CBT/ACT skills, explicit emotion/energy adaptation and user-owned behavioral strategies. C retains AI daily planning, learning/work support, longer-term life management and cross-context personalization. See [roadmap](../../PLANS.md). Product breadth A/B/C is separate from delivery Phases 0–5. Each expansion requires evidence and explicit scope approval.

Useful innovation hypotheses include a step-size adjustment instead of an enormous checklist, a temporary future-self bookmark, an optional good-enough stopping boundary, explicit quiet-support preferences and a user-owned strategy card. None is claimed clinically validated, unique or approved for implementation.

## Next actions and Founder decisions

Recommend approving the first scenario and candidate A static comparison scope, including whether same-attempt recovery is a core concept or a separate variant. Then, if separately authorized, prepare a document-only scenario walkthrough/acceptance matrix using fictional tasks, including ambiguous, already-known, interrupted, missing-prerequisite, exhausted and unsafe situations. A walkthrough can improve specifications but cannot validate market demand.

Before any recruitment, approve study eligibility/consent/privacy/resources, country and appropriate professional review. Before model use or application code, approve the relevant evaluation/provider/data and later phase gates; neither is authorized now. Before setting prices, obtain actual repeated-value and cost evidence. No credible delivery budget or schedule is established.

Review decisions requested: (1) first task context and country, (2) candidate A scope/default path and recovery variant, (3) minimum worthwhile AI advantage and burden guardrails for a future protocol, (4) whether to authorize another document-only review or a separately prepared research protocol, (5) qualified review arrangements. Existing organization/workflow, adult ADHD/English-first direction, A-first validation and B/C retention are already approved and need not be reapproved.

## Repository and completion record

Official root `/Users/justinzhao/Projects/juststart`, branch `main`, expected origin verified. This round began with the prior Phase 0 files still untracked and an existing `.GOALS.md.swp`; those are not treated as newly created by this round. The swap file and original README were preserved. Only local Markdown research/governance/product documents were changed. No application, dependency installation, recruitment, real-user data collection, paid service, account connection, external issue/project, deployment, commit or push occurred.

Final checks passed across 19 project documents: all four new research artifacts and required UX sections are present; local file links resolve; Markdown code fences are balanced; repository prose is English; no trailing whitespace was found. Git status shows Markdown-only project changes alongside the pre-existing swap file; the original README is unchanged. Approval and cross-review status was checked for consistency. These checks do not constitute clinical review, usability testing or executable product tests. Stop after the Chinese Founder report; no automatic Phase 1 entry.
