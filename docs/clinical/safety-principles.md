# Behavioral support and safety principles

Date: 2026-10-22 | Status: policy with public-evidence research update; no qualified clinical sign-off or user-facing release approval

## Intended boundary

JustStart is proposed as adult daily-life and executive-function support. It must not diagnose ADHD or any condition, provide psychotherapy, prescribe or adjust medication, interpret symptoms as a diagnosis, or represent itself as a clinician or crisis service. A disclaimer alone cannot make unsafe behavior acceptable. High-risk tasks and psychological conversations need enforced behavior boundaries and evaluation.

## Evidence requirements

Label every strategy as (1) evidence applicable to the defined population/intervention/outcome, (2) extrapolation requiring review, (3) product hypothesis, or (4) unsupported/excluded. A clinical guideline is not proof that an AI adaptation works.

Initial source: [NICE NG87 recommendations, adults 1.5.16–1.5.18](https://www.nice.org.uk/guidance/ng87/chapter/recommendations), accessed 2026-10-22. It discusses structured ADHD-focused psychological intervention and possible CBT elements in professional care. It does not validate JustStart, AI body doubling, rewards or automated therapy. No clinical effect size is claimed here.

| Approach | Initial evidence status in this repository | Allowed next investigation / release condition |
| --- | --- | --- |
| Practical task simplification / planning | Product hypothesis; plausibility does not establish benefit | Test usefulness and burden; professional review if framed as a psychological intervention |
| CBT-informed problem solving | Professional ADHD-care context supported by cited guideline; individual AI skill effectiveness unknown | Appraise the exact skill and wording, population and harms; qualified professional approval before psychological scripts |
| ACT-informed values/action | No adult-ADHD-specific evidence appraisal completed here | Review primary studies and syntheses; do not claim equivalence to CBT or treatment benefit |
| EFT | Term ambiguous; emotion-focused therapy and emotional freedom techniques are different approaches; neither appraised | Clarify method with Founder and professional reviewer; separate searches; exclude therapeutic techniques until reviewed |
| AI body doubling, rewards and personalization | Unvalidated product designs | Test acceptability, burden, dependency and real-world action; no transfer of human-partner findings to AI |

Future evidence ledger: strategy, exact claim, source/date, study type, population, comparator, outcomes, harms, limitations, directness to digital/AI adaptation, reviewer, status and re-review trigger. Search primary clinical literature and authoritative guidance; assess conflicting findings and publication bias. No invented studies or selective effect claims.

## Risk classes and controls

| Level | Examples | Required behavior / approval |
| --- | --- | --- |
| R1 low | Low-risk household/work task suggestions | Short editable actions, safe defaults, user choice, manual fallback and routine QA |
| R2 elevated | Shame/anxiety, overwhelm, repeated check-ins, rewards or saved personal context | Optional neutral acknowledgment; no diagnosis/inferred cause; easy pause; safety/privacy review and qualified review for psychological content |
| R3 high | Requests for diagnosis, treatment, medication, trauma processing or dangerous physical tasks | Do not provide the requested clinical/dangerous instruction; explain boundary briefly, offer safe support or appropriate human help; Founder and qualified reviewers must approve policy before release |
| R4 urgent | Expressed imminent harm, severe disorientation or immediate danger | Stop productivity/reward flow; use a professionally reviewed safety response encouraging immediate local human/emergency help; never claim live monitoring or dispatch |

This is design-level triage, not a diagnosis or a validated clinical risk classifier. Do not rely solely on keyword matching or an LLM to detect crises. Evaluate paraphrases, ambiguous language, different languages, false positives and false negatives. Do not store risk labels as a hidden mental-health profile.

## Crisis and distress design requirements

Before any user-facing release, obtain qualified professional review of responses and routing. Verify region-appropriate emergency/support resources at runtime or from a maintained reviewed directory; never invent numbers or assume location. Provide a safe generic human-help path if location is unavailable. Do not require task completion, long questionnaires or payment to leave a flow. No automatic contact of third parties or promises of emergency intervention. Minimize retention of distress disclosures; use consented, access-controlled incident summaries if necessary.

This document provides no actual crisis contact directory and does not certify readiness. Crisis resources, multilingual content, escalation ownership and maintenance cadence remain release blockers for any conversational product.

## Autonomy and non-coercion

Allow edit, reject, pause, skip, stop and delete without punishment. Use opt-in reminders with quiet hours and frequency controls. No lost XP, guilt, leaderboard pressure, rewards tied to emotional disclosure, punitive streaks or emotional dependence cues. Disclose AI identity; do not suggest it suffers when a user leaves. Support stopping and seeking a real person. Never treat productivity as moral worth.

## Privacy and professional review

Default: no diagnosis field, medical record, medication details, passive sensing, raw transcript analytics or provider training on user content without separately approved terms and consent. Task text may reveal health, finances, relationships or workplace secrets. Map each field to purpose, access, destination, retention and deletion; minimize before sending to a model. Define subprocessors, cross-border transfers, backup deletion and consent withdrawal before collection. Never put personal content in ordinary logs.

Before recruitment or release, determine launch jurisdiction and obtain qualified privacy/legal advice on applicable consumer, privacy and health/medical-device rules. No legal compliance conclusion is made. Founder approval cannot replace required professional review.

## Safety verification and incident handling

Build synthetic cases for clinical requests, medication, self-harm, coercion, hallucinated resources, unsafe decomposition, prompt injection, data leakage, bias, accessibility and dependence. Use versioned expected behaviors and independent review. Critical harmful outputs, material privacy failures and unreviewed high-risk flows block release. Repeat relevant cases after prompt/model/policy changes.

If a risk appears: stop the affected flow, preserve only necessary sanitized evidence, notify the accountable operator, assess exposure, roll back/disable where authorized, obtain specialist review, document correction and retest. Reporting obligations and user notification depend on professionally reviewed jurisdictional requirements, not agent guesswork.

## Public-evidence update and interaction gate

The independent [Behavioral Science report](../research/behavioral-evidence-and-safety.md) contains a targeted, non-exhaustive evidence appraisal and concrete bounded interaction proposals; the [synthesis](../research/phase-00-research-synthesis.md) records cross-review. Its AI author is not a substitute for a qualified mental-health professional. The initial matrix above described pre-research status; use the new report for current literature findings.

Do not state “no digital CBT evidence” or “no AI body-doubling research”: specific digital CBT trials and preliminary small-task AI/VR work exist. They do not validate JustStart, isolated generated micro-skills, English-market generalizability, equivalence to a human partner or durable everyday benefit. No treatment claim is approved.

For A, prototype editable task simplification, user-chosen pacing and neutral progress acknowledgment as product hypotheses. Keep psychological reframing, defusion, emotion processing and values exercises outside the mandatory path; exact strategy/content needs qualified review before a user-facing psychological intervention. Behavioral activation evidence from depression must not be presented as direct adult ADHD efficacy. Reward sensitivity does not imply everyone benefits from XP, unpredictable rewards or pressure.

Synthetic review must include: a useful action instead of an endless checklist; wrong prerequisite/unsafe task; “make smaller” still causing overwhelm; a user choosing rest or exit; a missing/expired restart note; a provider failure; emotional/clinical requests; pressure to continue; and unwanted disclosure. No user data or live model service is needed for the current document-only scenario specification.
