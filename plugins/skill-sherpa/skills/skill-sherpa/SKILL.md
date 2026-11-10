---
name: skill-sherpa
description: Use when the user asks which skill to use, whether a skill exists for a task, or wants to be pointed to the right skill (installed or to add) for their request.
---

# Skill Sherpa

Goal: from a request written in plain language, guide the user to the best-fitting skill — first among the ones they already have, otherwise among the ones they could add — then offer to run it.

Always reply in the user's language, briefly and candidly. Assume the user may not be technical: describe what a skill produces, not how it works.

## Steps

### 1. Understand the need
- Restate the request in one sentence: what outcome do they expect (a document, an analysis, a decision, code, an action)?
- If the request is too vague to choose, ask ONE short question. Otherwise, carry on without asking.

### 2. Search the skills already available
- Review every skill available in the session, including the ones that come from installed plugins.
- A skill-listing tool may return only part of them (for example, it can leave out plugin skills). Combine it with the session's own skill list; never treat either one alone as complete.
- Match the need against each skill's description, not just its name.
- Keep at most 3 genuinely relevant candidates. Do not keep a loosely related skill just to fill the list.

### 3. If nothing really fits, look further
- Search the catalog of skills and plugins the user can add (skill and plugin search/suggestion tools, when available), using keywords drawn from the need.
- Catalog searches return loosely related results. Discard anything that does not clearly answer the need.
- The catalog often describes a plugin as a whole, not each skill inside it. In that case recommend the plugin, and describe only what its description states.
- If a result matches, show the suggestion card so they can add it in one click.

### 4. Give the recommendation
Short answer format:

- **My pick: `skill-name`** — one sentence on why it fits the need.
- **Alternatives** (only if they truly exist, 2 at most): for each, one advantage and one drawback versus the first pick, expressed as outcomes for the user (speed, level of detail, format obtained), not jargon.
- State for each skill whether it is **already available** or **to add**.

### 5. Be honest when no skill fits
- Say it plainly: "No skill really matches."
- Then offer the best option: do the task directly without a skill, or create a dedicated skill if the task is likely to recur.
- Never invent a skill, and never describe capabilities a description does not mention.

### 6. Offer the next step
- End with a proposed action: "Shall I run it on your request?"
- If the user had already stated a precise task and one skill clearly stands out, announce the choice in one sentence and go straight into that skill.

## Rules
- One skill recommended first; no long lists.
- No jargon: explain what the skill delivers, not how it works.
- If several skills must be combined (e.g. research then writing), give the order in one line.
