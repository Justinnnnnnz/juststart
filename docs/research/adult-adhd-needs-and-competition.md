# Adult ADHD needs and competitive opportunity

Research date: 2026-10-22 (America/Toronto) | Owner: Product Manager Subagent | Status: independent desk-research recommendations, not validated requirements

## Scope and method

This work package uses public research and official product pages to inform an English-first adult ADHD product, with future English/Chinese support. It owns this file only. No interviews, app subscriptions, authenticated product tests, recruitment, personal-post collection, application development or external changes were performed. Initial repository checks confirmed the expected root, `main` and origin. Existing untracked documentation and `.GOALS.md.swp` were preserved.

Evidence labels: **E** = source-supported finding within its stated scope; **V** = provider-described capability or claim, not independently verified performance; **I** = our inference; **H** = untested product hypothesis. This is a bounded desk review, not an exhaustive market census or systematic clinical review. Publication dates below are those available on the sources; access dates are 2026-10-22 throughout. Changing product details require refresh before a commercial decision.

## Product decision in brief

Recommend testing a narrow promise: **“Bring one thing you are avoiding; leave with a manageable next move, and an easy way back if interrupted.”** This is an H, not a market-validated promise. The initial research segment proposed here is adults who already know what they intend to do, often already use a list, and get stuck on low-risk work/study administration or household tasks. Segment selection still needs Founder approval.

Do not position basic AI decomposition or one-task-at-a-time timers as unique. Direct alternatives already offer both. The potential advantage is a more useful, faster transition into and back to real action, with less setup and less pressure. That advantage has not been demonstrated.

## What the evidence actually establishes

- **E, authoritative context:** NIMH describes adult ADHD difficulties including organization, procrastination, remembering tasks, time management, distraction, large tasks and preference for immediate over delayed rewards. This supports investigating several barriers rather than treating every stuck moment as insufficient planning. It does not establish prevalence for our chosen scenario, predict an individual's needs, or demonstrate that an app improves functioning. [S1]
- **E, historical primary survey abstract:** Desrochers, Tuson and Magee report dissatisfaction with digital time-management tools in a survey including adults with and without ADHD. Only the university repository abstract was appraised here; sample details and numerical effects were not verified. A 2019 finding cannot establish dissatisfaction with today's specific products. [S2]
- **E, exploratory primary HCI:** Chen, Meng and Nie's April 2026 preprint reports 22 interviews (16 clinically diagnosed and 6 strongly self-identifying adults) and a separate 20-person reaction study of speculative AI concepts. Participants described initiation difficulty despite knowing a task, aversion, unrealistic plans, shame and social support; reactions varied. This informs hypotheses, not prevalence, clinical efficacy, retention or willingness to pay. The authors report CSCW2026 acceptance. The manuscript retains template publication metadata and inconsistent descriptions of session duration/diagnosis; treat it as exploratory, avoid ranking features from its small preference table, and verify a final proceedings version before stronger claims. English-market transfer and cultural representativeness remain unestablished. [S3]

## Why having a to-do list may still leave a person stuck

The following is a **product model inferred from the evidence**, not a clinical taxonomy or diagnosis. Multiple barriers can coexist; the product must not infer the cause from behavior.

| Moment / possible barrier | What a list supplies | What may still be missing | Concrete design hypothesis | Falsifying observation |
| --- | --- | --- | --- | --- |
| “Write report” is visible but ambiguous | A remembered intention | A feasible first physical/digital action and stopping point | Suggest “Open the report and add one rough heading”; editable and rejectable | User already knows the step; suggestion adds work |
| Several urgent items compete | Inventory and priority labels | A bounded decision about this moment | Begin with one user-chosen task; optional help choosing later | Users primarily need prioritization across a whole day |
| Task feels unpleasant or threatening | A reminder of the demand | A smaller commitment or permission to leave | “Try one rough sentence, then decide”; no required emotional disclosure | Microsteps feel patronizing or do not change avoidance |
| Task is distant; another activity is compelling | Future deadline | A concrete, voluntary near-term attempt | Optional short attempt with visible exit; avoid fake urgency | Timer increases stress or is ignored |
| Person is interrupted | A still-open task | The last useful context and next move | User-controlled return note; resume, shrink or change | Maintaining the note costs more than recovering unaided |
| Materials, information or capacity are unavailable | A task assignment | A real dependency or rest/accommodation | “What is missing?” only when needed; allow stop/defer | Repeated replanning substitutes for obtaining help |

A list is not inherently ineffective. It can externalize memory and be entirely sufficient. A new tool can itself become another demand. Clinical care, accommodation, rest or human support may matter more than a different interface; JustStart must not label every non-start as a software problem.

## Candidate contexts and prioritization

All rankings below are **I/H**, not observed demand or market sizing.

| Candidate context | Proposed job | Why investigate | Constraints / countercase | Sequence |
| --- | --- | --- | --- | --- |
| Work/study task already chosen | Begin a draft, email or routine admin item | Clear action boundary; can compare first action with existing method | Confidential work content; some users need substantive subject expertise | First candidate, using synthetic examples now |
| Low-risk household action | Start a visible chore | Concrete action, little planning needed | Physical safety and differing abilities; a simple cue may suffice | Parallel scenario in document prototypes |
| Return after interruption | Recover without reconstructing the whole plan | Potential repeat-use value beyond novelty | Saved context may reveal sensitive content; users may forget the tool | Include in concept comparisons, not automatic MVP commitment |
| Whole-day overload | Decide and schedule everything | Important long-term vision | Integrations, competing obligations and data burden | C discovery track |
| Need another person present | Work alongside a supportive presence | Relevant B hypothesis | AI may not provide social commitment or human connection | B, separate comparison with timer and human alternatives |
| Significant distress / crisis / treatment need | Obtain appropriate human support | Essential boundary | Productivity prompts are not adequate care | Safety routing; not a target efficacy scenario |

Do not require proof of diagnosis in a future consumer flow by default. Any research eligibility definition, self-identification policy and collection of health information require a separately approved protocol. Future localization should consider tone, action examples and cultural expectations, not merely translate strings.

## Current competitors and meaningful substitutes

Capabilities are **V**, from official public pages. “Gap to investigate” is **I/H**, not an established defect, a hands-on audit or a claim of feature absence.

| Alternative | Verified public positioning/capability | Strong overlap / reason users might prefer it | Gap to investigate, without inventing a defect |
| --- | --- | --- | --- |
| Tiimo [S4] | Advertises visual schedules, AI breakdown/estimates, focus timer, widgets, cross-device use and mood check-ins | Already combines planning and execution support; existing users need not adopt another tool | Does an immediate no-replanning entry outperform its start flow for a specific scenario? |
| Goblin Tools / Taskmaster [S5–S7] | Magic ToDo breaks tasks down; Taskmaster presents items sequentially with estimate-based timers, next-task suggestions and breakdown when stuck | A direct substitute for a large portion of A, including help during execution; core website access is free, with some advanced Pro features | Does a contextual first-action/resume design improve action enough to justify switching or paying? |
| Finch [S8–S9] | Self-care pet; goals/self-care activities earn energy, with Rainbow Stones supporting customization | Already supplies emotionally appealing acknowledgment and reward; meaningful B overlap | Are users seeking a work-start utility rather than self-care framing? Does added gamification help outside the app? |
| Focusmate [S10] | Book a live human video coworking session, state goals, work and check in | Supplies real human presence and commitment that AI may fail to reproduce | Does booking/video introduce friction for a spontaneous small start? Conversely, does human commitment explain the benefit? |
| Structured [S11–S12] | Visual timeline, calendars and AI planning; Replan moves missed work | Replanning is already a supported competitive behavior; strong C overlap | Does restoring task context address a different problem from moving a task to another time? |
| Todoist [S13–S14] | Natural-language capture and task organization; configurable time/location reminders | Existing workflow and low switching cost; reminders may already solve a forgotten intention | Is the unmet need really action initiation after remembering, rather than better reminders? |
| attexis clinical digital support [S15] | A March 2026 RCT studied a self-guided CBT/mindfulness program plus usual care in 337 adults, with reported symptom/function benefits | Relevant clinical digital alternative when users seek structured psychological support; not a directly comparable one-action utility | Not an AI trial or a comparison with a manual template; self-report, lack of blinding, unequal attention and developer funding limit transfer. No JustStart efficacy inference |
| A paper prompt, timer or trusted person | Baseline alternatives to test; no comparative outcome claim | Low/no model cost; familiarity; private and fast | Could “What is the smallest useful next action?” match the proposed product? |
| General-purpose AI assistant | Candidate comparator, no specific current vendor feature audited here | Users can ask an existing assistant for a smaller next step | Does a dedicated interface reduce prompting, review and distraction enough to matter? |

No representative review mining, app-performance benchmark, accessibility audit, policy audit or willingness-to-pay study was conducted. No unsupported claims about competitor retention, broken notifications, exploitative design or poor clinical outcomes are made. Published testimonials and provider user counts were not treated as market validation. Precise local prices and platform entitlements were intentionally not used as a pricing strategy.

## Where AI might add value over a rule or template

These are **H**. A minimal manual path is a legitimate product outcome.

| Need | Rules/templates can do | Possible incremental AI value | Added cost / failure | Required comparison |
| --- | --- | --- | --- | --- |
| Familiar repetitive task | Offer a saved first step immediately | Little needed | Latency, inconsistency and cost without benefit | Manual/saved step vs generated step |
| Unfamiliar vague task | Ask “What can you physically do next?” | Turn messy language into one context-fitting action | Wrong assumptions, unsafe advice, excessive substeps | Same interface, template vs reviewed AI suggestion |
| Stated obstacle | Offer a small menu of neutral adjustments | Adapt an action to “I only have five minutes / missing a document” | Intrusive questioning or inferred psychology | Fixed adjustment vs contextual adjustment |
| Returning to a task | Redisplay the saved step | Condense a user-written note into a useful return cue | Loss of detail, stale summary, private-content exposure | Original note vs summary; verify usefulness and accuracy |
| Emotional difficulty | Neutral acknowledgment and stop/edit choices | Possibly rephrase respectfully | Therapy drift, false empathy, reliance | Reviewed fixed wording first; no open-ended counseling |

Keep generation out of the critical path when a user already has a next action. If AI does not produce meaningfully better useful-action outcomes after accounting for review effort, latency, cost and harm, ship/test a non-AI core or stop. No need to prove that every interaction uses AI.

## Concrete candidate MVP A

This is a proposed testable scope, not an approved PRD.

1. One short input: “What would you like to start?” with an example and a manual-next-step path. No full day, diagnosis form or mandatory account proposed for concept testing.
2. Show one editable next action with a visible bounded stopping point. “Make smaller” and “That doesn't fit” preserve control; avoid generating an entire project by default.
3. “Try this” means an attempt, not proof of real-world action. An optional short timer is a separate variant, never a required commitment or enforced deadline.
4. Finish with “I started / Still stuck / Pause / Skip” and optional neutral acknowledgment. Leaving without a report is permitted; the outcome remains unknown, not failed. Completion of the whole task is not required to obtain value; honest non-start reports are useful.
5. Evaluate a minimal return card: original intention, last user-approved action wording and optional user-written next cue; “Resume / Smaller step / Change task / Clear.” Approval of action wording does not confirm it was performed; neither a click nor timer implies execution. Persistent cross-session memory is a separate scope/privacy decision; a same-session prototype can test the concept first, without implying persistence across restarts or devices.
6. Manual fallback, delete/clear, accessible controls and reviewed safe boundaries are fundamental. No voice recording, calendar integration or background monitoring is required to test the core concept.

Example, using synthetic content: “Start my report” → “Open the report and type one rough heading; then you can stop.” If that is already done, let the user edit immediately. On return: “Last step: draft the heading. Is that still the right place?” Never assert an action happened because a timer ran.

## Innovations worth exploring without expanding A automatically

All are **H**, potentially reproducible by competitors; none is claimed novel in the research literature or patentable.

| Idea | Concrete interaction | Placement / dependency | Main reason to reject or postpone |
| --- | --- | --- | --- |
| Return breadcrumb | User leaves a few words for their future self; next entry offers that cue | A concept comparison; retention decision needed | Saving becomes another task; stale/sensitive context |
| Step-size dial | “Smaller” changes effort/commitment instead of producing ten subtasks | A variant | Trivial microsteps feel condescending or enable avoidance |
| Obstacle-specific pivot | User chooses “unclear / too big / missing something / rather pause”; one adaptation | A experiment only if basic flow fails | Extra questions slow users who already know what to do |
| User-owned strategy card | Explicitly save “rough first draft helps me”; edit/reset it anytime | B/C personalization after repeated evidence | Hidden profiling or unstable causal conclusions |
| Quiet AI coworker | Clearly labeled AI presence, silence default, user-chosen check-ins | B; isolate from timer/human presence | Distraction, simulated relationship dependence, no added benefit |
| Personal acknowledgment | Optional chosen feedback after a reported attempt; neutral acknowledgment also accepts honest non-start/skip; no losses or streak debt | B; compare neutral feedback first | Novelty fades; reward screen becomes the activity |
| Capacity-sensitive action | Explicit “smaller today” preference shapes a plan | B/C; no inferred mood or passive sensing | Misreads a need for rest as a need for productivity |

Preserve B/C directions: AI body doubling; immediate rewards and personal gamification; professionally reviewed CBT/ACT skill support; emotion/energy adaptation; AI daily planning; study/work assistance; long-term life management; user-controlled behavioral strategies. Advancement depends on evidence and separate approval, not on including them all in the first release. Practical planning is not equivalent to delivering CBT or ACT; detailed evidence and limits belong to the behavioral report.

## Proposed future validation and decision rules

**No studies in this section were performed or authorized to recruit.** First use synthetic scenario walkthroughs and internal expert critique. Before involving people, prepare a protocol with consent, compensation/resource envelope, task sanitization, retention, risk response and qualified review where appropriate.

For later Founder-approved testing, compare the participant's existing method, a manual smallest-step prompt, and an AI-assisted one-action flow. Counterbalance order, use comparable low-risk tasks, record model/version and task context, and include satisfied competitor users and negative cases. A later competitor walkthrough should explicitly include Goblin Taskmaster; otherwise we may test against an artificially weak baseline.

Measure real-world action started within the agreed attempt window, plus end-to-end time from opening/choosing the task to the first real-world action. Count disclosure reading, mode choices, editing, AI waiting and suggestion review in the latter so a short post-button interval cannot hide setup burden. Also record suggestion editing/rejection, perceived effort and pressure. Separate attempted starts from confirmed/reported actions, count abandonment/missing responses and report per-person as well as per-attempt outcomes. Repeated voluntary use after novelty and interruption recovery need a later longitudinal design, not extrapolation from a single demonstration. No numerical go/no-go threshold is evidence-backed today; set a minimum worthwhile advantage and guardrails before testing.

Reconsider A if a saved manual cue works as well; if users already solve the job comfortably with competitors; if step choice is not the bottleneck; if review effort exceeds benefit; or if the product increases pressure. Investigate B if a useful first action is accepted but sustaining effort is the recurring obstacle. Investigate C when multiple jobs are independently valuable and users need them connected. A negative outcome should narrow or stop a direction rather than trigger an automatic feature expansion.

## Source ledger

All accessed 2026-10-22. Undated means the consulted page did not expose a reliable publication date. Product sources establish public descriptions only.

| ID | Source / direct URL | Date / type | Appraised scope and limitation |
| --- | --- | --- | --- |
| S1 | [NIMH, ADHD in Adults: 4 Things to Know](https://www.nimh.nih.gov/health/publications/adhd-what-you-need-to-know) | Undated consulted web version; authoritative public health information | Adult difficulties/context, not app evidence |
| S2 | [Desrochers et al., Evaluation of Why Individuals with ADHD Struggle to Find Effective Digital Time Management Tools](https://commons.clarku.edu/faculty_computer_sciences/15/) | October 2019; primary survey paper repository abstract; DOI 10.1145/3308561.3354622 | Abstract only; no quantitative extraction |
| S3 | [Chen et al., Not Just Me and My To-Do List](https://arxiv.org/html/2603.17258v2) | Revised 2026-04-20; qualitative interviews and speculative-concept study | Full-text methods/findings/limits inspected; no efficacy inference; final publication metadata unverified |
| S4 | [Tiimo official site](https://www.tiimoapp.com/) | Undated; provider page | Current public feature descriptions; not hands-on verified |
| S5 | [Goblin Tools home](https://goblin.tools/) | Undated; provider page | Tool inventory |
| S6 | [Goblin Tools Taskmaster](https://goblin.tools/Taskmaster) | Undated; provider help/interface text | Sequential flow, estimates, suggestions and breakdown; not an authenticated test |
| S7 | [Goblin Tools About](https://goblin.tools/About) | Undated; provider page | Free core/advanced Pro distinction and general-purpose AI accuracy warning |
| S8 | [Finch official site](https://finchcare.com/) | Undated; provider page | Pet/self-care positioning |
| S9 | [Finch, Energy vs. Rainbow Stones](https://help.finchcare.com/hc/en-us/articles/37780134479757-Energy-vs-Rainbow-Stones) | Updated 2025-11-10; official help | Reward mechanics, not effectiveness |
| S10 | [Focusmate official site](https://www.focusmate.com/) | Undated; provider page | Booking, human video coworking, goal/check-in flow; no clinical effect claim used |
| S11 | [Structured official site](https://structured.app/) | Undated; provider page | Timeline/calendar framing |
| S12 | [Structured planning assistance](https://structured.app/planning-assistance) | Undated; provider page | AI planning and Replan descriptions |
| S13 | [Todoist task management](https://www.todoist.com/task-management) | Undated; provider page | Capture and organization capabilities |
| S14 | [Todoist introduction to reminders](https://www.todoist.com/help/todoist/features/introduction-to-reminders-9PezfU) | Undated consulted page; official help | Configurable reminder types; entitlements/platforms not fully audited |
| S15 | [D’Amelio et al., attexis randomized controlled trial](https://doi.org/10.1017/S0033291726103390) | Published 2026-03-11; primary adult clinical digital RCT | Abstract, limitations and funding inspected; clinical program, not AI or direct A comparison |

## Handoff and outstanding decisions

Independent PM desk research and cross-review are complete; recommendations remain pending Founder review. Founder decisions pending: initial scenario/segment and geography; whether to include a minimal return concept in A comparisons; AI-versus-template comparison criteria; any future participant protocol; data policy/resources/professional review; phase transition and eventual implementation scope. No implementation, recruitment, collection, spending, publication, commit or push is authorized by this report.


## Independent cross-review record

2026-10-22: PM independently read the UX report in full. No blocker to delivering the research package was identified. PM raised two medium issues: align the home wireframe and flow's extra mode/disclosure choices so the exact critical path is reviewable; distinguish static AI-labelled examples (concept/content acceptability) from real model/interaction evaluation (quality, latency, cost, incremental value). One low issue: link current competitor overlap rather than infer a market gap from historical usability findings. Findings sent to UX and coordinator; UX owns its changes.

UX independently reviewed this report and raised two medium issues and one low issue. Resolved in this file: explicitly include opening/choosing-task-to-action time; define retained step as user-approved wording rather than confirmed execution and separate session from persistent memory; add Skip/no-report and preserve unknown outcomes. Cross-review improves proposal clarity but provides no participant validation, clinical approval or implementation permission.

2026-10-22: PM independently read the complete Behavioral Science report and checked the attexis primary publication. No blocking evidence-transfer assertion was identified. Two medium recommendations sent to its owner/coordinator: keep a two-minute timer as an optional variant with “Try this step” as the default; explicitly distinguish current-session restart from separately approved cross-session/device retention. A low recommendation reiterated neutral treatment of non-start/skip. Behavioral reviewer requested that this report recognize clinical digital alternatives; attexis was added with no AI/A-efficacy transfer. Its low-priority acknowledgment concern was also resolved by explicitly including honest non-start/skip. UX reported resolving PM's three recommendations in its own file. Behavioral Science also confirmed resolving the timer-default, retention-scope and non-start/skip recommendations in its own report.
