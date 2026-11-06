# Portable handoff to a separate product project

Read this when the user selects an idea for a portable specification. This folder remains a scouting workspace. The user will take the brief to a new folder and session, where the product and actual build harness will be set up.

## Product brief

Use the existing research rather than interviewing the user again from scratch. Ask focused questions about unresolved product choices, not routine implementation details the agent can decide. Save the brief at `opportunities/<idea-slug>/brief.md`, linked from the active research report. For Plan 1, use `research/x-ideas/plan-1-client-experiences.md`; create or use an index only when the user's chosen research layout calls for one.

Make the brief understandable in a fresh session without access to this chat or scouting folder. Include the relevant founder constraints and direct evidence URLs; summarize essential findings rather than relying on local reference links. Identify the first task for the new session, including project-specific harness/tool setup where appropriate.

Capture the target user and promise, evidence links, why now, smallest user journey, features excluded from the first release, sharing behavior, concrete earning method, first-user plan, effort and cost assumptions, major dependencies, acceptance criteria, and the validation/stop plan. Scope the first usable launch to one week, accounting for setup, verification, and deployment. State what would prevent that schedule and how scope could shrink. Mark assumptions explicitly. Include draft launch content when requested or useful; the user publishes it.

## Optional implementation resources

Sources reviewed on 2026-11-05; check current upstream instructions and locally available tools before use. They are optional resources, not installed dependencies of this skill.

- [REA](https://github.com/morluto/rea) offers app and website inspection. Use it when an identified behavior needs deeper investigation; prefer ordinary browser inspection when enough. Inspection does not guarantee recovery of hidden server code, product data, or an entire business. Keep findings separate from inference. It is not needed merely to generate a similar feature.
- [Matt Pocock's skills](https://github.com/mattpocock/skills) provide discussion, specification, ticketing, and implementation workflows. Check which skills are actually available and honor their invocation rules. Choose only the parts useful for the selected project. If absent, continue with a focused brief and small verified implementation steps without claiming to have invoked them.

Do not install implementation tools or configure a build harness in this scouting folder. Carry suggested resources and their intended roles into the portable brief. Inspect current official setup instructions in the separate product project when its user requests setup. Do not copy a whole external skills collection into this skill.

## Guidance to carry into the new session

In the portable brief, recommend that the implementation session choose a stack and hosting route appropriate to the selected product and its actual constraints. Avoid prescribing a universal stack during scouting. Build a small complete path, verify the important behavior with suitable checks, and inspect the result in a browser. Keep the sharing and revenue hypotheses visible so implementation does not grow into unrelated features. Follow the user's current authorization and applicable project/skill instructions for deployment and external actions.
