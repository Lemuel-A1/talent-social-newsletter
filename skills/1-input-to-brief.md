---
name: newsletter-1-input-to-brief
description: Turn a transcript, deep-research report, event notes or interview notes into one or more Talent Social newsletter briefs with a fact pack. Use first, before any draft.
---

# 1. input-to-brief

Read `../STYLE_GUIDE.md` first.

## Input
- The input file (transcript, research report, event notes, interview notes).
- How many issues to plan (default 1; "a month" means 4 across at least 3 types).
- Event details if an event block runs: name, date, time, area, checkout link, discount code.

## Steps
1. **Triage the input.** What is it, who wrote it, how reliable, what date. List anything `internal` (prices, audience counts, check-in rates, strategy): it is never used. If the input has no speaker labels or timestamps, say so here and apply the naming rule in the router (`ROUTER_PROMPT.md`, "Naming speakers"): ask who said what, and mark each attribution by what supports it. If the upload starts with an AI-generated summary, ignore it as a source.
2. **Tag every candidate fact** with an evidence label from STYLE_GUIDE section 5 (primary, second-hand, relayed, vendor, stale, inference, internal).
3. **Find up to 5 stories or findings, and stop at the number the input supports.** If only 3 are viable, plan 3; do not pad. Check that each footnote in a report matches its works-cited entry; a mismatch makes the fact `relayed` or cut. For each: the person or source, the one-line arc, the moment that turns into a lesson for a professional in Nairobi, 2 to 3 verbatim quotes with where they appear, and what is missing.
4. **Choose a type for each** (Career Edge, Community Spotlight, Panel Insight, Research Brief, Roles and a Tip). For a month, vary the types and put the cheapest last. If the input supports fewer than three types, plan only those, mark each other slot "needs a different input" with what it needs (for example, a member with written OK), and do not draft it from this input.
5. **Fill the dissection row** per issue: audience, key message (one sentence; if it takes two, split the issue), hook, subject idea, one CTA, one image and its rights.
6. **List what is needed before writing:** written OK, image rights, event link and code, live roles.

## Output
One brief per issue using `../templates/issue-brief.md`, each with a fact pack (fact, source, label) and the "needed before writing" list. Say which brief to draft first and why.

## Checks
- No `internal` figure in any fact pack.
- Every quote is verbatim and located in the input.
- Unsourced items are `{{NEEDS_VERIFICATION}}`.
- Every named attribution follows the router's naming rule and says what supports it.
- A finding that would invite an obvious reply (for example, "ask for the full cost first" while our own page hides the price) is held or swapped.

## Use in another tool
Paste `STYLE_GUIDE.md`, then this file, then your input. Ask for the briefs. Nothing else is needed.
