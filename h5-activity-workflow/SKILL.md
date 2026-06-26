---
name: h5-activity-workflow
description: Use when planning, documenting, prototyping, reviewing, or iterating H5 campaign activities or 活动工作流, especially when the user wants activity mechanics, readiness checks, one-page activity briefs, lightweight/full workflow modes, competitor analysis, product-plan interrogation, activity marketing copy, tracking plans, regression-based effect validation, post-activity reviews, Figma prototypes, local web demos, or annotation feedback.
---

# 活动工作流

## Overview

Use this skill to run a repeatable H5 activity workflow from planning through Figma prototype, local web demo iteration, tracking validation, and post-activity review.

Core principle: confirm each stage before moving to the next. Keep the workflow lightweight, local, and specific to the current activity.

## Standard Flow

1. Absorb existing materials.
2. Run a readiness check, choose fast, standard, or full mode, and draft the one-page activity brief.
3. Analyze competitor activity materials when provided and required by the selected mode.
4. Clarify the activity plan.
5. Interrogate the product plan from multiple stakeholder roles according to the selected mode.
6. Define tracking, data retrieval, and success validation according to the selected mode.
7. Generate and review activity copy when needed.
8. Produce planning documents.
9. Create or update the Figma prototype.
10. Incorporate Figma comments and marked-up feedback.
11. Build the local web demo from the approved prototype.
12. Use local web annotations to collect demo feedback.
13. Revise the demo until approved.
14. Package final documents, Figma reference, and web demo.
15. When post-activity data is provided, generate the activity review report.

## Stage 0: Existing Materials

When the user has prior planning material, read it before asking detailed planning questions.

Collect:

- Notion planning docs
- Existing H5 links
- Pixso or Figma links
- Competitor activity screenshots or links
- Gift images, screenshots, rule images, and other visual assets
- Prior campaign rules or reference campaigns

Output a short source index that marks each item as rule, visual, interaction, numeric logic, copywriting, or engineering reference.

## Stage 0.1: Readiness, Mode, and One-Page Brief

Before running the full workflow, decide how much process the activity needs. Do not force every small activity through every heavy stage.

Readiness check:

- Goal clarity: what business or user behavior the activity should change.
- Decision maker: who can approve mode, scope, and final tradeoffs.
- Activity size: small copy/resource update, medium campaign, or high-exposure/high-risk activity.
- Complexity: number of roles, pages, entries, rewards, rankings, time states, and backend dependencies.
- Risk: user confusion, reward cost, settlement risk, fraud risk, executive visibility, or engineering uncertainty.
- Materials: whether prior docs, competitor references, visual assets, gift specs, or data baselines exist.
- Deadline and output need: document only, Figma prototype, web demo, presentation package, or post-activity review.

Choose one mode and record the reason:

- Fast mode: small or low-risk activity. Produce a one-page brief, minimal mechanism notes, key page/state list, and only the prototype/demo pieces needed for discussion. Competitor analysis, product interrogation, tracking, and copywriting can be lightweight, but major unknowns must still be recorded.
- Standard mode: default. Use the normal workflow with focused depth. Run competitor analysis, interrogation, tracking, copy, Figma, web demo, and annotation steps when relevant.
- Full mode: high-exposure, high-cost, multi-role, ranking/reward-heavy, or politically sensitive activity. Run the full workflow, including competitor analysis, product interrogation, statistical validation planning, copy review, design quality gates, and review package.

Mode scope table:

- Fast mode required: source index, readiness result, one-page brief, minimal activity plan, key page/state list, key risks, and open issues. Competitor analysis, product interrogation, tracking, and copywriting may be lightweight but cannot be skipped when they affect core mechanics, rewards, role visibility, time states, or data conclusions. Figma, web demo, web annotations, presentation package, and post-activity review are optional unless the user asks for them or they are needed for discussion.
- Standard mode required: source index, readiness result, one-page brief, activity plan, relevant competitor analysis, product interrogation, tracking plan, copy review when user-visible copy exists, Figma prototype when screens are needed, web demo when UI/technical discussion needs an interactive artifact, annotation loop when demo feedback is expected, and post-activity review when data is provided.
- Full mode required: all major stages, including competitor analysis when reference material exists, full product interrogation, tracking and statistical validation plan, copy review, Figma prototype, local web demo, annotation loop, design quality review, presentation package for stakeholder review, and post-activity review when data is provided.
- When the selected mode changes, update the one-page brief, list what is added or removed from scope, and ask the user to confirm before continuing.

One-page activity brief:

- Activity name and selected mode.
- Current problem and objective.
- Target audience and roles.
- Core user behavior to drive.
- Core mechanism and reward.
- Main entry/resource placements.
- Required pages, states, and role visibility.
- Biggest risks and open questions.
- Success metric and validation method.
- Required output: doc, Figma, web demo, presentation package, or review report.
- Decision maker and next confirmation gate.

Stop for user confirmation when the mode or one-page brief would materially change scope.

Confirmation gate format:

- Gate name.
- Current decision requested.
- Options: approve, revise, defer, or change mode.
- Scope impact if approved.
- Open issues that remain.
- Next stage after approval.

Do not treat silence as approval unless the user has explicitly asked to auto-continue. If the user defers a decision, record it as an open issue with owner, risk, and the stage where it must be resolved.

Notion output rules:

- When Notion access is available and the user asks for Notion output, create or update a page titled `[Activity Name] - [Document Type] - [Date]`.
- If updating an existing Notion planning page, append a dated section instead of overwriting earlier decisions unless the user explicitly asks for a rewrite.
- Include source links, Figma links, local file paths, demo URLs, and artifact links when available.
- If Notion is unavailable, save or output a Markdown version that can be pasted into Notion and clearly say that Notion was not updated.

Notion hygiene for competitor analysis:

- If rewriting or upgrading an existing competitor analysis page, merge the old and new material into one clean document instead of stacking a new analysis above the old one.
- Merge overlapping sections: page structure/page function with layout and art analysis; user click path with user path; conversion mechanism with mechanism breakdown.
- Delete screenshot-evidence sections when no real image can be embedded. Do not leave empty image blocks, empty Markdown image syntax, or placeholder screenshots.
- Local `file://` images and data-URI images may render empty in Notion. If the connector cannot upload local images reliably, use a Notion-accessible image URL, ask the user to upload manually, or include the local thumbnail path as evidence instead of inserting a broken image.
- For batches of 10 or more Notion pages, run an internal page-count and structure check: expected child count, preserved categories, no duplicated analysis blocks, no empty image blocks, and no missing required analysis sections. Do this check yourself; do not add a separate quality-gate section to the end of the user-facing document.
- For long-running competitor batches, keep a progress checklist by category and activity. If the user asks for a recurring review or resume-after-quota workflow, use the available automation or subtask tools to re-check unfinished pages, quota-blocked steps, missing thumbnails, and Notion formatting issues. On resume, continue from the incomplete items instead of rewriting pages that already passed the internal check.

## Stage 0.5: Competitor Activity Analysis

When the user provides competitor activity screenshots, analyze them before locking the activity plan. If the selected mode is fast, keep the analysis lightweight unless the competitor reference is central to the activity. If the plan already exists, use competitor analysis to challenge and improve the plan rather than replacing it automatically.

First organize the screenshots:

- Create or use `D:\竞品`.
- Copy or move screenshots into folders by platform, activity name, and category when that information is available.
- Use categories such as entry, main page, rules, task, ranking, reward, popup, result, share, exception state, and visual asset.
- Keep original images intact. Use readable filenames that preserve platform, page type, and order when renaming is needed.
- Maintain an image index that records source, inferred page role, visible rules, visible numbers, and uncertainty.
- Preserve the user's existing categories and activity boundaries. Each competitor report should represent one single activity unless the user explicitly asks for a cross-activity summary.
- For multi-screenshot activities, create one stitched contact-sheet overview per activity, such as `Codex_缩略图总览.jpg`, and place it back into that activity's source folder. Prefer one overview thumbnail in the report over many full-size images so the document stays readable.

Analyze the competitor activity across:

- Activity positioning, target user, and likely business goal.
- User path from entry to completion.
- Mechanics: tasks, lottery, ranking, invite, points, redemption, progress, unlock, or hybrid design.
- Numeric logic: thresholds, points, attempts, cycles, reward tiers, ranking criteria, inventory, caps, reset, and settlement.
- Content and copywriting: rule clarity, page hierarchy, call-to-action wording, reward explanation, and friction points.
- Visual design: theme fit, information density, hierarchy, reward salience, trust cues, and visual fatigue.
- Interaction design: feedback, transitions, popups, state visibility, recoverability, and edge states.
- Operational implications: data needs, backend complexity, anti-cheat risk, settlement burden, customer-service risk, and implementation uncertainty.
- Strengths, weaknesses, reusable ideas, non-transferable ideas, and why each point matters.

Separate observed facts from inference. Do not invent hidden probabilities, inventory, settlement rules, or backend logic unless the screenshot or linked source supports them. Mark unknowns clearly.

Competitor activity logic analysis must explain the activity design logic, not just describe the pages. For every single activity, include these user-facing sections:

1. `页面表层信息`: entry, page structure, main visual, core copy, reward display, and screenshot/source notes.
2. `活动目标推断`: the most likely business goal, such as acquisition, activation, payment, retention, host activity, gifting, relationship building, or competition, with evidence from page elements and rewards.
3. `用户行为路径`: the full path from entry to action completion, including what the user sees first, what they tap, what feedback they receive, and where they are pushed next.
4. `核心机制拆解`: tasks, ranking, progress, lottery, unlock, levels, cumulative spend, limited-time sprint, invite, relationship value, redemption, or hybrid mechanics.
5. `规则逻辑反推`: inferred calculation, ranking, eligibility, threshold, tie-breaker, time cycle, settlement, and reward-claim rules. Mark each uncertain item as `推断` or `无法确定`.
6. `激励与反馈设计`: how the activity creates urgency, comparison, low entry barrier, repeat return, payment intent, interaction intent, host activity, or continued participation.
7. `可借鉴点`: mechanisms worth borrowing and why they are useful for the user's business.
8. `不可直接照搬的风险`: cost, fraud, settlement disputes, user resentment, UX friction, development complexity, and operating burden.
9. `对我们方案的启发`: how to adapt the idea into a concrete activity mechanism for the user's own product, not just a generic lesson.

For each important mechanism, answer:

- Why is this mechanism, number, threshold, ranking, reward, or interaction likely designed this way?
- What exact behavior does it ask the user, host, or payer to perform?
- Why would the user be willing to perform that behavior?
- What platform effect should this produce?
- What is unreasonable, risky, confusing, or not worth copying directly?

Use related marketing skills when useful:

- `competitive-ads-extractor` for creative hooks, CTA patterns, reward framing, and visible conversion pressure.
- `competitor-profiling` for separating observed facts, inference, competitor positioning, and operating assumptions.
- `ads` and `copywriting` for CTA intent, persuasion, copy hierarchy, and friction.
- `product-marketing` for target user, behavior goal, business objective, positioning, and adoption logic.

Before treating the competitor analysis as complete, check the document yourself. It passes only if it contains user path, mechanism logic, rule/reward logic, feedback design, operating intent, borrowable conclusions, and risks. It fails if it only says the page is simple, rewards are rich, visuals are strong, or atmosphere is good without explaining the mechanism and intended behavior. If screenshots do not show enough information, explicitly write `无法确定`, explain what is missing, and avoid inventing unsupported rules. Do not add this internal check as a separate ending section in the final document.

Output a competitor analysis report in the user's Notion when Notion access is available. If Notion is unavailable, output a Markdown report that can be pasted into Notion. The report should use the nine user-facing sections above. Add screenshot index, category summary, thumbnail path or image URL, source uncertainty, and follow-up questions inside the relevant sections instead of creating duplicate sections.

## Stage 1: Activity Plan

Before writing prototype or demo code, confirm:

- Current problem diagnosis: what the old activity, draft, or current plan fails to solve.
- Activity goal: acquisition, activation, conversion, brand display, booking, lottery, quiz, game, or other.
- Business goal split: whether different modules serve different goals such as revenue, mid-tier support, newcomer activation, retention, or content supply.
- Audience and usage context.
- Tracks or lanes: whether the activity should be split into separate competitions, tabs, roles, or modules instead of one combined rule.
- Page map: entry, rules, interaction, result, share, exception states.
- User path from entry to completion.
- Interaction mechanics: lottery, quiz, task, invite, points, ranking, redemption, or custom rules.
- Numeric logic: attempts, probability, reward pool, inventory, points, limits, reset rules.
- Metric rationale: why each metric supports the intended business goal.
- Success metrics: what data will prove the activity reached or missed its goal.
- Cycle consistency: whether statistics, display, settlement, reset, and reward delivery use compatible time windows.
- Ranking model: primary metric, eligibility threshold, display grouping, tie-breakers, and final fallback order.
- Role and entry differences: user side, host side, hall entry, live-room entry, poster entry, rule-page entry, share return.
- Edge states: not logged in, no attempts left, out of stock, duplicate participation, not started, ended, network failure.
- Demo fidelity: what must be realistic for UI and technical discussion.

Output planning documents:

- Activity plan
- Problem diagnosis
- Business goal and track split
- Module breakdown table
- Role and entry matrix
- Interaction mechanism notes
- Numeric and reward ledger
- Metric and ranking rationale
- Cycle consistency check
- Page flow notes
- Front-facing rule-page copy
- Activity copy inventory
- Change log that separates discarded, modified, and current rules
- Design rationale that explains why the final plan beat earlier options

Run the product-plan interrogation before moving to Figma unless the selected mode is fast and the one-page brief shows the activity is low-risk. In fast mode, still ask the questions that affect role visibility, time states, click paths, resources, and reward logic.

## Stage 1.5: Product Plan Interrogation

Before Figma, stress-test the product plan through role-based questioning. The goal is to make the activity buildable, testable, drawable, operable, and explainable.

Create an interrogation matrix with columns for role, question, answer or decision, affected page/state, affected rule or number, resource or interface dependency, test point, status, and owner when known.

Ask from these roles:

- Development: how each function is implemented, what data is needed, what interfaces are required, what is simulated in the demo, what depends on backend settlement, and where anti-cheat or race conditions may appear.
- QA/testing: what cases must be tested, what edge states exist, what time windows matter, how rankings settle, how rewards are issued, what happens when data is empty, late, duplicated, or inconsistent.
- UI/design: where buttons live, what each click opens, what page or popup appears next, what the user sees after every action, what visual assets are needed, and what cannot be solved by copy alone.
- User: what the user wants to do, what they can see, when they can see it, what is hidden, what is confusing, what feedback appears after tapping, and what happens if they fail or are not eligible.
- Host or role-specific participant: what the host or special role can see, when they can see it, whether they have separate entries, rankings, rewards, tasks, or notices.
- Leader/business: what business goal the feature serves, why this mechanism is worth doing, what success metric proves it worked, what can be cut if time is short, and what risk is acceptable.
- Operations: what resource placements are needed, such as live-room entry, hall banner, opening screen, flying screen, push, poster, rule entry, share card, or message notice.
- Assets and rewards: whether gifts are needed, how many gift sets are needed, whether there are dynamic or static assets, reward images, badge images, ranking medals, empty-state images, and rule illustrations.

Always challenge:

- What function is this trying to achieve?
- Where is the button, and what happens after clicking it?
- What page, popup, tab, or external entry does the user reach next?
- Which roles can see this, and which roles cannot?
- At what time can each role see it?
- What is shown before start, during activity, after end, after settlement, and after reward claim?
- How precise are rankings, scores, points, and displayed numbers?
- What are the ranking, eligibility, tie-breaker, reset, settlement, and reward rules?
- What resource placements, gifts, images, copy, and configuration are required?
- What can be cut without breaking the core goal?

Do not proceed to Figma while major unknowns remain around role visibility, time states, ranking precision, reward logic, required resources, or click paths. In fast mode, unresolved low-risk questions may be deferred only if they are listed as open issues. If the user chooses to defer an unknown, record it as an explicit open issue.

Output:

- Product interrogation matrix
- Open issue list
- Resource placement checklist
- Asset and gift requirement list
- Development and testing notes
- Decisions that changed the activity plan

Stop for user confirmation before moving to Figma.

## Stage 1.6: Tracking and Effect Validation

Before Figma or implementation handoff, define how the activity will be measured. The tracking plan must explain where to track, what to verify, what data development must provide after the activity, how each metric will be used in the review, and what statistical standard will be used to judge whether the activity worked.

Create a tracking matrix with columns for event or data point, page or entry, trigger action, role, activity phase, required parameters, validation question, expected signal, developer confirmation, post-activity data source, statistical method, pass standard, and review usage.

Cover at least:

- Resource exposure and clicks: opening screen, banner, live-room entry, flying screen, push, poster, share card, rule entry, and other placements.
- Page funnel: activity page exposure, rules view, tab switch, task view, ranking view, reward view, share view, result view, and exit points.
- Key actions: join, click CTA, complete task, send gift, invite, share, draw, claim reward, view ranking, switch role, or other core interactions.
- Mechanism effectiveness: task completion rate, conversion rate by entry, reward claim rate, ranking participation, share return, gift or payment contribution, retention or repeat participation when relevant.
- Edge and failure states: not logged in, no eligibility, no attempts, activity not started, ended, no data, reward unavailable, request failure, duplicate action, or anti-cheat interception.
- Role and time dimensions: user versus host, new versus returning, entry source, activity day, phase, settlement status, and before/during/after activity states.

Confirm with development:

- Which events can be tracked.
- Which parameters are available.
- Which backend tables or exports are needed after the activity.
- The time granularity, user dimensions, role dimensions, and entry-source dimensions available for review.
- The deadline and format for post-activity data retrieval.
- Any data that cannot be collected or would be unreliable.

Do not collect unnecessary personal information. Keep the tracking plan focused on validating the activity goal, diagnosing drop-off, and improving the next version.

Statistical validation requirements:

- For every core activity goal, define a hypothesis before launch: if the activity mechanism works, independent variable `X` should have a positive relationship with outcome variable `Y`.
- Define `X`, `Y`, control variables, population, time window, and minimum practical effect before implementation. Do not add success metrics after seeing the result.
- Use correlation only as exploratory evidence. Positive correlation is not enough to claim the activity caused the result.
- Prefer control or baseline comparison when available. Use A/B, holdout group, historical baseline, or difference-in-differences when the product and data conditions allow it.
- For core conclusions, use a regression model when data volume and structure allow it.

Default formulas:

- Descriptive correlation: `r = cov(X,Y) / (sigma_X * sigma_Y)`. Directional expectation: `r > 0`.
- Linear outcome: `Y_i = beta_0 + beta_1 X_i + beta_2 Controls_i + epsilon_i`.
- Binary conversion outcome: `logit(P(Y_i = 1)) = beta_0 + beta_1 X_i + beta_2 Controls_i`.
- Difference-in-differences when there is a treatment and comparison group: `Y_it = beta_0 + beta_1 Treat_i + beta_2 Post_t + beta_3 Treat_i * Post_t + beta_4 Controls_it + epsilon_it`.

Default pass standard:

- Direction: `beta_1 > 0` for direct exposure or participation effects, or `beta_3 > 0` for difference-in-differences.
- Statistical confidence: use `p < 0.05` or a 95% confidence interval whose lower bound is greater than 0.
- Practical effect: the effect size must meet the pre-agreed minimum lift, such as conversion lift, revenue lift, participation lift, retention lift, or share-return lift.
- Data quality: sample size, missing data, duplicate data, tracking loss, abnormal traffic, and entry-source mix must be checked before interpreting the result.
- If there is no control group, insufficient data, unreliable tracking, or severe confounding, label the conclusion as directional observation instead of proven effect.

Output:

- Tracking matrix
- Success metric definition
- Statistical validation plan
- Post-activity data request list for development
- Review question list
- Known data gaps or unreliable metrics

Stop for user confirmation before moving to Figma. In fast mode, a lightweight tracking note is acceptable only when the activity has no meaningful measurement risk; still record how success will be checked.

## Stage 1.7: Activity Copywriting

When the activity needs user-facing copy, use the appropriate skills from Corey Haines' `marketingskills` package. This applies to public screen messages, platform private messages, poster copy, push messages, banner copy, flying-screen copy, share card copy, popup copy, CTA copy, rule copy, and any other copy that affects user behavior.

Choose the closest marketing skill by channel and purpose:

- Use `copywriting` for new activity page copy, rule-page copy, CTA copy, poster copy, banner copy, share-card copy, and one-off persuasive messages.
- Use `copy-editing` to polish or shorten existing copy, or after drafting copy that will be shown in the prototype or demo.
- Use `emails` when the copy is a sequence, lifecycle message, platform private-message flow, or repeated notification cadence.
- Use `sms` when the message is short, direct, notification-like, or has SMS-style length and compliance constraints.
- Use `popups` for modal, popup, confirmation, reward, failure, or eligibility messages.
- Use `ad-creative` for short promotional variants such as push, banner, poster, opening screen, or flying-screen slogans when the main task is variant generation.
- Use `social` when the copy is for sharing, social distribution, or user-generated share text.
- Use `ab-testing` when copy variants need a test hypothesis, metric, or experiment setup.

If the best sub-skill is unclear, choose the closest two by intent or produce multiple options. Do not provide more than 5 candidate copy options for one copy slot unless the user explicitly asks for more. Ask the user to confirm the final version before treating it as approved.

For every copy item, record:

- Copy slot: page, popup, push, banner, poster, public screen, private message, rule section, share card, or other.
- Audience and role: user, host, newcomer, returning user, winner, ineligible participant, or other.
- Trigger and timing: before start, during activity, after completion, after settlement, before claim, after failure, or scheduled push.
- Goal: explain, convert, remind, reassure, create urgency, reduce confusion, or drive a specific action.
- Destination or next action after click.
- Length or display constraint.
- Selected marketingskills sub-skill.
- Candidate copy, rationale, and final user-approved version.

Keep copy consistent with confirmed mechanics, eligibility, timing, rewards, and statistical claims. Do not invent proof, numbers, urgency, scarcity, rewards, or guarantees that the activity plan does not support.

## Stage 2: Figma Prototype

Use Figma for prototypes. If the environment exposes Figma tools, follow the relevant Figma skill prerequisites before calling Figma tools.

The prototype should cover:

- Main page layouts
- Navigation and page relationships
- Key buttons and interaction states
- Popups, hints, result states, and exception states
- State screen inventory: default, not started, ended, not logged in, no eligibility, progress unmet, progress met, reward claimed, empty rankings, rankings with self, rankings without self.
- Information architecture split: what belongs on the active play/ranking page versus what belongs on rules, rewards, or explanation pages.
- Low-fidelity or high-fidelity constraints when the user wants structural validation instead of visual polish.
- Areas that need UI or engineering attention

Iteration loop:

1. Ask the user to review in Figma.
2. Read or receive Figma comments, circles, and annotations.
3. Modify only the annotated or agreed areas.
4. Repeat until the user confirms the prototype.

Figma feedback record:

- Accept Figma comments, marked screenshots, user text notes, or exported images as feedback sources.
- For each item, record page or node, issue, requested change, decision, status, and resolution note.
- If feedback conflicts with confirmed mechanics, reward rules, tracking rules, or role visibility, stop and ask for a decision before changing the prototype.
- Keep each revision traceable to a feedback item. Do not use the feedback pass for unrelated redesign.

Stop for user confirmation before building the web demo.

## Stage 3: Local Web Demo

Build the web demo only after the Figma prototype is approved.

Design quality gate:

- Use `frontend-design` before building or restyling the web demo to define the web visual direction, layout density, typography, color, motion, responsive behavior, and interaction polish.
- If the Figma prototype is low-fidelity, preserve its information architecture and mechanics, then use `frontend-design` to decide the appropriate demo fidelity instead of blindly copying wireframe styling.
- After the first working demo is available and before final handoff, use `design-is` as a design review pass. Fix high-impact clarity, hierarchy, usability, and visual-quality issues before entering or completing the annotation loop.
- Keep the design pass scoped to the approved activity and prototype. Do not use it as permission for unrelated redesign.

Implement the smallest useful demo:

- Visual structure and content rhythm.
- Key clicks, popups, transitions, and state changes.
- Simulated core mechanics such as draw attempts, points, answer results, or reward outcomes.
- A local-only scenario panel when the activity has multiple roles, entries, phases, rankings, or progress states.
- Scenario controls for ranking/eligibility edge cases when ranking order differs from reward eligibility or display grouping.
- Enough behavior for UI and engineering discussion.

Do not add by default:

- Backend services
- Login systems
- Multi-user collaboration
- Real payment, real inventory, or real reward delivery
- Admin configuration systems

Demo acceptance check:

- The demo opens locally and the user can access it through a URL or local file path.
- Key flow, buttons, popups, and state changes are clickable enough for UI and engineering discussion.
- Scenario controls work when the activity has multiple roles, entries, time phases, eligibility states, ranking states, or progress states.
- Mobile viewport remains readable and does not hide required controls or content.
- The demo clearly avoids real backend, payment, inventory, reward delivery, or account behavior.
- Annotation mode, if included, does not block the core activity operation.
- Known limitations are listed before handoff.

## Optional Presentation Package

When the user needs to present the activity to leadership, UI, engineering, or operations, create a lightweight presentation package. This is optional and should not be required for every activity.

Choose the presentation layer by audience and purpose:

- Deck: use when the user needs to explain the activity in a meeting, especially to leadership, UI, engineering, operations, or cross-functional reviewers.
- HTML showcase: use when the user needs an interactive browser-based walkthrough that can sit next to the local demo and show flow, states, annotations, and decisions.
- PDF: use when the user needs a fixed, easy-to-share archive of the plan, flow, screenshots, and decisions.
- PPTX: use when the user needs an editable meeting deck that other stakeholders may revise or present.

Include only what helps the discussion:

- One-page activity brief.
- Figma link or key screenshots.
- Local web demo URL or file path.
- Main user flow and role/state summary.
- Key mechanism, reward, resource, and tracking decisions.
- Open issues and decisions needed.
- Optional deck, PDF, or HTML overview when the user needs a shareable artifact.

Deck structure:

- Title and one-sentence objective.
- Why this activity exists: current problem, target audience, and business goal.
- Core mechanism and reward structure.
- Main user flow with role and time-state notes.
- Key screens from Figma or the web demo.
- Resource placements and copy touchpoints.
- Tracking and success validation summary.
- Risks, open issues, and decisions needed.
- Next steps and owner list.

HTML showcase structure:

- First screen: activity name, selected workflow mode, objective, and links to Figma/demo.
- Flow section: entry points, page sequence, role visibility, and time states.
- Screens section: key screenshots or embedded local demo states.
- Mechanism section: rules, rewards, ranking, eligibility, and edge states.
- Decision section: confirmed decisions, open issues, and annotation status.
- Data section: tracking plan, success metrics, and post-activity data request.

PDF/PPTX export rules:

- Export PDF when the user needs a stable record or shareable read-only document.
- Export PPTX when the user needs editable slides for meetings.
- Keep PDF/PPTX concise by default: one slide/page per major topic, avoid copying the full PRD into the deck.
- Use screenshots, diagrams, and tables from the approved plan and prototype rather than inventing new visuals.

Do not create a presentation package until the one-page brief and core mechanism are confirmed. If the prototype or demo is not final, mark the package as draft.

## Stage 4: Web Annotation Feedback

The web demo is local-only for the user. Do not add accounts, permissions, or multi-person collaboration unless explicitly requested.

Minimum annotation mode:

- Toggle annotation mode.
- Select or draw around a page area.
- Enter a comment.
- Record page name, role, entry source, activity phase, demo state, and viewport size with each annotation when available.
- Show an annotation list.
- Delete annotations.
- Export annotations or save them in a locally readable form.

Annotation export schema:

- Export JSON by default when building annotation mode.
- Each annotation should include `id`, `timestamp`, `pageName`, `viewport`, `role`, `entrySource`, `activityPhase`, `demoState`, `targetType`, `rect` or drawing path, `screenshotRef` when available, `comment`, `status`, and `resolutionNote`.
- A Markdown summary may be generated for easier review, but the JSON is the source of truth for revisions.
- When screenshots are used instead of JSON export, create a manual annotation table with the same fields as far as possible.

Revision loop:

1. User annotates the local web demo.
2. Read the exported annotations, saved local data, or screenshots.
3. Modify the demo according to the feedback.
4. Keep changes surgical and traceable to comments.
5. Ask for confirmation after each revision pass.

## Stage 5: Post-Activity Data Review

When the user provides activity-end data, continue the workflow and produce a review report. Compare actual data against the tracking plan, expected signals, and original activity goals.

Review:

- Whether the activity reached the expected goal.
- Where the funnel dropped off by entry, role, page, phase, or action.
- Which resource placements worked and which did not.
- Whether the mechanism, reward design, ranking rules, and copywriting drove the expected behavior.
- Whether users or hosts had visibility, timing, eligibility, or understanding problems.
- Whether data quality issues, tracking gaps, implementation changes, or operational incidents affected the conclusion.
- Which assumptions were proven, disproven, or still unknown.
- Whether correlation, regression, baseline comparison, or difference-in-differences supports the expected positive relationship.

Output the review report in Notion when available. If Notion is unavailable, output a Markdown report that can be pasted into Notion.

The report should include:

- Activity goal and original success metrics.
- Data source and reliability notes.
- Statistical method, formula, coefficient direction, confidence standard, and practical effect threshold.
- Executive conclusion: reached, partially reached, or missed expectation.
- Funnel and entry-source analysis.
- Mechanism and reward effectiveness analysis.
- Role, timing, and state analysis.
- Problem diagnosis.
- Reusable learnings.
- Next-version improvement points.
- Follow-up data questions.

## Final Package

At completion, provide:

- Mode-adjusted final package: in fast mode, include only the required fast-mode items plus a short "not included because of fast mode" list; in standard and full modes, include all relevant items below according to the selected scope.

- Readiness result and selected workflow mode
- One-page activity brief
- Final activity plan
- Source index
- Competitor analysis report when competitor materials were provided
- Problem diagnosis
- Business goal and track split
- Module breakdown table
- Role and entry matrix
- Product interrogation matrix
- Resource placement checklist
- Asset and gift requirement list
- Tracking matrix
- Success metric definition
- Statistical validation plan
- Post-activity data request list
- Interaction mechanism notes
- Numeric and reward ledger
- Metric and ranking rationale
- Cycle consistency check
- Front-facing rule-page copy
- Activity copy inventory and approved copy
- Change log
- Design rationale
- Figma prototype reference
- Web demo design direction
- Web demo design review summary
- Local web demo
- Deck, HTML showcase, PDF, or PPTX when requested
- Annotation resolution summary
- Presentation package when requested
- Post-activity review report when activity data was provided
- Notes for UI and engineering discussion

## Iterating This Skill

When the user reports that this workflow caused friction, update this skill.

Update rules:

- Change only the part of the workflow that failed or slowed the user down.
- Prefer adding a clear confirmation gate or checklist item over adding a heavy system.
- Do not add speculative roles, tools, or automation.
- Keep the skill concise enough to load quickly.
- After editing, validate that `SKILL.md` still has valid frontmatter with `name` and `description`.

Useful user prompts:

- "Update the H5 activity workflow skill to require..."
- "This H5 workflow was too heavy at the demo stage; simplify it."
- "Add this recurring H5 activity edge case to the planning checklist."
- "From now on, make web annotation export mandatory in this workflow."

## Common Mistakes

- Starting Figma before activity mechanics are clear.
- Running the full heavy workflow for a small low-risk activity without first choosing the appropriate mode.
- Skipping the one-page activity brief, causing later docs, prototypes, and demos to drift.
- Creating Deck, HTML, PDF, or PPTX presentation artifacts before the one-page brief and core mechanism are confirmed.
- Starting the web demo before the Figma prototype is approved.
- Treating the local web annotation layer as a full collaboration system.
- Adding real backend behavior when a simulated demo state is enough.
- Making broad redesigns instead of addressing specific annotations.
- Building the web demo without a `frontend-design` pass.
- Skipping the `design-is` review before final web demo handoff.
- Mixing observed competitor facts with inferred assumptions.
- Copying competitor mechanics without checking whether the goal, audience, and operating constraints match.
- Treating an activity idea as ready for Figma before role visibility, time states, click paths, resources, ranking precision, and reward logic have been interrogated.
- Designing an activity without defining what data will prove success or failure.
- Asking for post-activity data without first agreeing on events, dimensions, data source, deadline, and review questions with development.
- Treating positive-looking metrics as proof without predefining hypotheses, variables, formulas, confidence standards, and practical effect thresholds.
- Writing activity copy without using the appropriate Corey Haines marketingskills sub-skill when user-facing copy is needed.
- Generating too many copy options instead of giving no more than 5 focused candidates for user confirmation.
