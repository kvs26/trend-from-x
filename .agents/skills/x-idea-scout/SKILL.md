---
name: x-idea-scout
description: Research X conversations to find and evaluate timely, shareable website and app opportunities, or investigate a supplied product idea. Use for product scouting and deciding what to build; ordinary social browsing and implementation alone do not need this skill.
---

# X Idea Scout

Find a small product worth testing, grounded in current conversations and a credible way to reach users. Prefer a candid rejection over an attractive idea with weak evidence. This project is for scouting, evaluation, discussion, and portable briefs. Product implementation and the actual build harness belong in a separate folder and session chosen by the user.

## Start with saved context

Read [the founder profile](references/founder-profile.md) and the active research file specified there in the project root containing this `.agents/skills/` directory. Read an existing research index only when the user's chosen output arrangement uses one. Current user instructions override saved defaults. Do not repeat the onboarding interview each session. Ask the run-specific choice below; otherwise ask only about missing decisions that materially affect the current task.

If `IDEA_DIRECTIONS.md` exists at the project root, read it as user-curated context. It contains broad directions rather than selected products and does not restrict every research run. Edit that file only when the user explicitly requests adding, changing, removing, or updating directions in it. Routine scouting, new findings, enthusiasm about an idea, or a request to save research does not authorize an edit, including status or date changes. Suggest possible additions in conversation and keep research in the normal reports until the user asks to change the directions file. This rule is separate from updating research reports, the index, and confirmed founder preferences.

At the start of each new invocation, ask which product direction to explore:

1. **Useful tools:** Products people share because they solve a problem.
2. **Playful experiences:** Products people share for fun, curiosity, identity, or comparison.
3. **Both:** Compare opportunities from either direction on their merits.

If the user already chose in the invocation, use that answer without asking again. Carry the choice through follow-up messages in the same run. Record it in that run's report, not as a permanent replacement for this menu. While awaiting a choice, inspect saved research or check source access as useful, but do not choose a category or begin category-dependent research on the user's behalf. Do not repeat this menu when merely continuing the same run.

Choose the scope from the request:

- **Scout:** Discover fresh opportunities and compare a small shortlist. This is the default.
- **Investigate:** Test a supplied post, product, audience, or idea against demand, alternatives, distribution, and costs.
- **Prepare a portable brief:** Once the user selects an idea, use [the build handoff](references/build-handoff.md) to produce a self-contained brief for a separate project folder and session. Keep product code and build-harness setup out of this scouting project.
- **Revisit:** Update a previous candidate using new evidence or actual launch results; preserve earlier decisions and explain what changed.

## Research and judgment

Use [the research playbook](references/research-playbook.md) for search strategy, evidence capture, and evaluation. X is the primary discovery source; official product pages, documentation, and pricing help establish competition and feasibility.

The user's Chrome session previously supported reading X and searching posts after the user signed in. That is historical evidence, not a guarantee that a future session is available. Discover current browser tools and inspect current state; never reuse old tab identifiers or assume persistent login. Use computer/browser tools when available. Let the user handle login if needed; do not request credentials or store session material. If X is blocked, report the limitation and continue with accessible public evidence or supplied posts, clearly labeling reduced coverage.

Favor websites and web apps with fast access from a shared link. Consider native mobile only when device capabilities, usage context, or distribution justify it. Within the chosen direction, consider tools, directories, boards, comparisons, and playful experiences when evidence supports them; do not force everything into subscriptions or an AI wrapper. Target a usable first launch within one week at around 30 hours of founder effort plus agent assistance. Include setup, integrations, verification, and deployment in the estimate; agentic coding does not make external dependencies disappear. Suggest a smaller version or explain the mismatch when a candidate cannot fit.

Treat shareability as a mechanism to explain and test, not a promise. Describe who shares what, why the next person clicks, and what causes further sharing. A prominent person's request can provide a launch opening, but is not a complete acquisition strategy or proof of payment demand.

Separate attention, user value, and willingness to pay. Evaluate trend timing alongside a product's usefulness after the initial spike. Distinguish a small temporary experiment from a product with repeat use and a credible longer-term advantage; neither is automatically disqualified.

## Deliver and remember

The normal flow is **shortlist → recommendation → discussion**. Present roughly 3–5 credible candidates, with fewer when evidence is weak, then recommend the strongest and invite the user's choice. For each, give the target user, triggering evidence with direct links, smallest useful product, sharing mechanism, concrete earning method, rough effort/cost, main uncertainty, and next validation step. The earning method must name who pays, what they buy, a plausible price hypothesis, and any prerequisites such as sponsor demand or traffic. State confidence and coverage limits. Use a comparison table when helpful; keep detailed evidence in the saved report. Do not silently turn the recommendation into a build decision.

For the strongest candidate, explain the first-user path, what the user would do personally, an inexpensive test, and measurable continue/change/stop criteria. Work toward at least USD 5,000 in cumulative revenue over six months, with some profit desired. Use revenue scenarios with explicit assumptions instead of income predictions, estimate costs and possible surplus separately, and flag ideas whose economics cannot plausibly support this goal. Recommend passing on all candidates when appropriate.

Honor the user's requested research layout. For the active Plan 1 investigation, maintain the single `research/x-ideas/plan-1-client-experiences.md` report with dated research entries, evidence, decisions, and candidate status; do not create extra dated reports or an index in that folder. Earlier reports are archived under `research/archive/x-ideas/`. For a future investigation without a specified layout, use dated reports and an index only if helpful. Use the user's local date. Capture candidate IDs/slugs, report links, status (watch, investigate, test, build, launched, or passed), decision reasons, and next evidence needed. Deduplicate against earlier runs. Preserve historical observations rather than silently replacing them. Record observed user outcomes separately from assumptions.

Update the founder profile only when the user supplies a durable preference or resolves an open choice. Keep project findings out of the reusable skill instructions. Resolve output paths relative to this project, not the shell's incidental directory.

The user handles conversations, outreach, and posting. Prepare draft posts and replies when useful, without sending them. This skill does not initiate external communications, spend money, configure accounts, schedule monitoring, or install tools merely because they might help an idea.
