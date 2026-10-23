# Product discovery plan

Date: 2026-10-22 | Status: three-agent public-source research and local static-design work authorized; participant studies, real-user data and implementation remain unapproved

## Questions and research sequence

1. Desk research: competitor capabilities, existing workarounds, relevant behavioral evidence and privacy constraints. Product/UX and Safety own separate evidence ledgers.
2. Problem interviews, after Founder approval of recruitment, consent and data protocol: proposed 8–12 adults with varied work/study/household contexts, self-identified difficulties, current tool use and accessibility needs. Do not request diagnostic proof, medical records or medication history. Sample size supports qualitative discovery, not population estimates.
3. Synthesize recurring moments, negative cases and unmet jobs; compare diagnosed/self-identified experiences only if ethical, necessary and separately approved. Default avoid diagnosis labels in records.
4. After synthesis approval, test low-fidelity manual prototypes with 5–8 adults using fictional or sanitized, low-risk tasks. No application build or external publishing required. Keep facilitator assistance visible in results.
5. If justified and separately approved, a 7–14-day voluntary follow-up can examine repeat usefulness; retention and pricing remain uncertain without longer evidence.
6. Produce evidence synthesis, prioritized hypotheses, MVP recommendation, risks and a go / revise / stop recommendation for Founder review. No automatic Phase 1 entry.

All sample sizes and durations are resource proposals, not scheduled commitments. Recruitment/outreach, incentives, recordings, real-user data and external tools are not authorized in this run.

## Interview guide (future protocol)

Ask about the most recent moment they intended to act but could not; what happened before/after; task size and available context; what they tried; what helped or made things worse; interruption recovery; tools abandoned; reminders/rewards they dislike; what would make support feel intrusive. Ask for concrete experiences before showing concepts. Explore successful days and people who do not want AI. Do not diagnose, request trauma narratives or fabricate responses.

## Prototype tasks

Use a fictional low-risk task such as organizing a desk. Compare the participant's usual approach with a one-action flow and a simple non-AI template. Counterbalance order where practical. Observe comprehension, editing, actual first action when observable, pauses and ease of exit. Simulate an interruption only with consent. Label AI or facilitator-generated outputs honestly. Explain that stopping is valid and does not reduce compensation.

## Proposed metric dictionary

| Metric | Operational definition | Limitations |
| --- | --- | --- |
| Start rate within 5 minutes | Attempts with observed or self-reported real-world first action within 5 minutes / all eligible attempts started | Begin clock when user explicitly elects an attempt; report observation vs self-report separately |
| Time to first action | Elapsed time from attempt start to first meaningful action | Report median/range for starts plus non-start count; do not silently discard failures |
| Useful next step | Participant accepts/edits proposal and rates it useful / attempts with a proposal | Acceptance alone is not execution |
| Recovery rate | Interrupted attempts resumed within 5 minutes of electing to resume / attempts electing resume | Also report interruptions with no resume election to expose selection bias |
| Progress / completion | Optional report of progress on the chosen step; parent-task completion reported separately | Completing a tiny step is not finishing the whole task |
| Repeat usefulness | Participants voluntarily use the flow on at least 3 distinct days / all follow-up enrollees | Report missing follow-ups; reminders must not manufacture engagement |
| Burden | Optional effort rating, unwanted pressure, stop/skip and accessibility feedback | Skipping is not failure; missing responses remain visible |
| Cost per helped attempt | Estimated model + infrastructure + support cost / attempts reporting useful action | Planning estimate until actual approved operation |

Future minimal events: attempt_started, next_step_shown, action_reported, pause_selected, resume_selected, session_closed. Use random attempt IDs and necessary timestamps only; no task text, diagnosis, journal, inferred mood or transcript in analytics. Event list is a proposal and requires privacy/Founder approval. Do not interpret session_closed as failure. Report missing outcomes and deduplicate retries.

## Proposed decision rules

Pre-register final rules before testing. For a small moderated study, directional signal: at least 4 of 6 participants can use the core flow without facilitator rescue and find its next action useful; inspect every non-start and negative case. Do not treat this as statistical proof.

For a later approved follow-up: look for lower median start time and no worse burden relative to participants' usual method, with denominators and raw counts. No numeric treatment-effect target is justified yet. Pause or revise if several users prefer the manual template, setup adds friction, pressure increases or benefits vanish after novelty. A critical unsafe response or material privacy failure blocks advancement until corrected and re-evaluated, even if average metrics improve.

## Data and ethics proposal

Plain-language consent, optional questions, no recordings by default, sanitized summaries with participant IDs. Proposed deletion: contact details within 14 days of follow-up, sanitized raw research notes within 30 days of synthesis; retain only approved de-identified aggregates. Final storage, retention, access and withdrawal windows require approval before collection. Stop on distress; never act as a therapist. Qualified review is required for psychological scripts and risk handling.

## Deliverable status

Prepared: plan, hypotheses, preliminary public-source inventory and safety requirements. Not done: recruitment, interviews, usability sessions, market validation, clinical appraisal, pricing validation or MVP approval. Owners are role assignments, not claims that people have been hired.

## Current public-research round

Founder-confirmed audience: adult ADHD users; English market first, preserve future English/Chinese capability. The approved operating model uses three independent PM/UX/Behavioral Science Subagents, each owning one report, followed by cross-review and root synthesis. See [synthesis](../research/phase-00-research-synthesis.md), [needs/competition](../research/adult-adhd-needs-and-competition.md), [UX prototype](../research/adhd-ux-and-initial-prototype.md) and [behavioral evidence](../research/behavioral-evidence-and-safety.md). External study participants belong to cited research, not a JustStart participant cohort.

### Candidate next comparison, not yet authorized

Use the same fictional low-risk task and presentation for (1) a user-written next action, (2) a fixed small-step rule/template, (3) a labeled context-sensitive AI suggestion. Include a matched Goblin Tools Taskmaster journey comparison because it already offers substantial overlapping behavior. Keep moderator assistance and AI labeling consistent; account for order effects. Compare time/effort to a useful action, excessive edits, wrong assumptions, burden and interruption recovery. A better-sounding suggestion or willingness-to-try response is not proof of behavior change.

Root recommendation: start the primary clock at explicit attempt election, before input/generation, and also report total entry-to-action time and pre-attempt abandonment so setup friction cannot disappear from the denominator. Separate intention, button clicks, observed action, self-reported action and missing outcomes. Do not penalize a deliberate stop. AI should survive the comparison only if contextual adaptation offsets generation delay, reading effort, errors, privacy and cost. No causal or retention conclusion follows from this desk research.

Before any user session, return for protocol/consent/data approval. Before any code, return for the later product/architecture gates. The current next deliverable can remain a document-only walkthrough and safety-case specification if separately authorized.
