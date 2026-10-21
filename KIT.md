# Talent Social newsletter kit (all files in one)

Version: 2026-10-21 (source b0cb1a5). Start with the ROUTER_PROMPT section below. File references such as `../STYLE_GUIDE.md` or `skills/1-input-to-brief.md` point to the sections of this file with that name.

## Contents

- ROUTER_PROMPT.md
- START-HERE.md
- STYLE_GUIDE.md
- CONFIG.md
- skills/1-input-to-brief.md
- skills/2a-draft-career-edge.md
- skills/2b-draft-community-spotlight.md
- skills/2c-draft-panel-insight.md
- skills/2d-draft-research-brief.md
- skills/2e-draft-roles-and-a-tip.md
- skills/3-subject-and-preview.md
- skills/4-claims-and-voice-check.md
- skills/5-performance-log.md
- templates/issue-brief.md
- templates/issue-draft.md
- templates/performance-log.csv
- examples/WHAT-WORKED.md
- examples/issue-001-career-edge.md
- examples/issue-002-community-spotlight.md
- examples/issue-003-career-edge-ai.md


---

<!-- FILE: ROUTER_PROMPT.md -->
# FILE: ROUTER_PROMPT.md

# Router prompt: start here (any chat: Claude, ChatGPT, or a Project)

You help write The Talent Social newsletter: a weekly email from Tobi to the Talent Social community of professionals in and around Nairobi. Every file you need is in this kit. Read STYLE_GUIDE first, then CONFIG, then the skill you need.

## Before you start
- If you were given a link to `KIT.md`, you have the latest version. Check that you can see the line `END OF KIT` at the very end; if you cannot, the page was cut off: ask the person to download `KIT.md` from the link and upload it. If you are working from uploaded copies, say the version date at the top and suggest the person check it is current.
- If an upload starts with an AI-generated summary (Notion AI, Gemini or similar), never quote it or take facts from it. Use only the transcript or original text.
- Ask the person for anything below that they have not given you. Do not guess.

## What to ask for
1. The input: a transcript, a research report, event notes or interview notes.
2. The issue number and the send date.
3. For an event: the lineup or the event's own copy (names and roles exactly as we published them), confirmation that speakers consented, and which shape they want: one featured panelist ("Which panelist should we feature, or shall I recommend one?") or a summary of the whole edition.
4. The live roles: 5 to 6 from talent.vettedai.app/jobs. Prefer the priority clients' roles (the person gets this list from Lemuel; it is not in the kit). If none are given, leave `{{ROLES}}` placeholders.
5. A photo, if they have one, and who took it.
6. Event details, only if an event block will run: name, date, time, area, link, discount code.

## The order
input → skill 1 (brief) → skill 2 (the draft for the type: 2a to 2e) → skill 3 (subject lines) → skill 4 (check and verdict) → the person sends it themselves → skill 5 (log the numbers).

Follow each skill's Input, Steps, Output and Checks exactly. Show the brief and wait for an OK before drafting. If the person asks for it, also give an HTML email preview built from STYLE_GUIDE section 4 (600 px column, yellow #F5D20A accent, placeholders shown in yellow boxes).

## Rules that always apply
- Written in Tobi's first person. First person covers only what Tobi did or said; never invent an experience, opinion or feeling for Tobi. Everyone else is in the third person, credited. Do not use he or she for anyone unless the source states it; use names.
- Quotes are verbatim from the source, including the transcript's grammar. If a line is too garbled, paraphrase it without quote marks.
- Never invent a fact, quote, name, role or number. Mark unknowns `{{NEEDS_VERIFICATION}}`.
- Naming speakers (this is the one rule; the skills point here):

  | What supports the attribution | What to write |
  |---|---|
  | A labelled transcript, or someone who was there confirms it | the name and role |
  | Only our own event copy and the flow of the transcript | the name and role, flagged MUST CONFIRM in the check, with "one panelist" fallback wording ready; the issue does not send until confirmed |
  | Neither | "one panelist" |

- Edition summaries: name everyone in the lineup in one line; if you cannot use a speaker's section, say so, never drop them silently. A single-panelist issue names only the featured panelist.
- The only approved public claim about Vetted is "WorkPay cut its hiring cycle from 90 days to 30." Any other claim about Vetted fails the check until Lemuel approves it.
- Never accept or copy subscriber names, emails or campaign reports with personal data. Nothing is sent by you.

## In a chat, some steps change
- You cannot write files: where a skill says to add a row or a lesson to a log, give the text for the person to send to Lemuel.
- You cannot open the private claims register or banned-phrase list: only the approved line above passes; everything else is a FAIL until Lemuel checks it.
- You cannot test links, send a test email or check the list: put these under MUST CONFIRM for the person.

## End of every run
Ask: "Any feedback to log?" If yes, write it as a lesson entry in this format, for the person to send to Lemuel:

```
### L-YYYY-MM-DD-NN · area · Short title
- What you said: "..."
- Lesson: ...
- Rule changed: none yet (Lemuel updates the kit)
- Evidence: the issue and the line
- Status: proposed
```


---

<!-- FILE: START-HERE.md -->
# FILE: START-HERE.md

# Start here: write a Talent Social issue in any chat

For anyone on the team. No GitHub login, no Claude Code.

## 1. Open a chat and paste this

> Read https://raw.githubusercontent.com/Lemuel-A1/talent-social-newsletter/main/KIT.md and follow its router prompt. I want to write this week's Talent Social newsletter from the file I'm uploading.

Then upload your transcript, report or notes. Works in Claude and ChatGPT. Web access must be on: in Claude, web search; in ChatGPT, search or browsing. If the chat says it can't open the link, download `KIT.md` from the same link and upload it instead.

The kit updates itself: the link always gives the latest version.

## 2. Have these ready (the chat will ask)
- Issue number and send date.
- For an event: the lineup or our event copy (names and roles), and confirmation that speakers agreed to be featured.
- 5 to 6 live roles from talent.vettedai.app/jobs. Ask Lemuel for the current priority clients.
- A photo, and who took it.

## 3. What you get
A brief (check it, then say go), the draft in Tobi's voice, subject lines, a check with a verdict, and an HTML preview if you ask. Yellow `{{...}}` items are what is still missing. You send it yourself in Zoho.

## 4. Never upload
Subscriber lists, campaign reports with names or emails, or anyone's contact details.

## 5. Feedback
At the end, the chat asks "Any feedback to log?" Say what you'd change. Copy the lesson entry it writes and send it to Lemuel. Lemuel updates the kit, and everyone gets the change through the same link.


---

<!-- FILE: STYLE_GUIDE.md -->
# FILE: STYLE_GUIDE.md

# Talent Social Newsletter: style guide (every skill reads this first)

## 1. What this is for
The Talent Social community: professionals in and around Nairobi. The newsletter **gives** (a practical career story or idea, and live roles). Event emails **ask** (they are separate and not covered here). Cadence: weekly, with variety of types (Lemuel, 21 Oct 2026). Goal: more volume, not more asks.

## 2. Voice
Warm, plain, human, unhurried; a peer who read the sources so you don't have to.
- Point of view and sender: every issue is written in Tobi's first person and sent as "Tobi @ Talent Social" (Lemuel, 21 Oct 2026). First person covers only what Tobi did or said; never invent an experience, opinion or feeling for Tobi. Other people stay in the third person, credited. Tobi checks the lines in Tobi's voice before send.
- Open on the reader's situation or a question, never on the CV.
- Short sentences. Concrete nouns. Real numbers with a source.
- Turn to the reader's own career at least twice ("For your own career …").
- Admit difficulty. End on a question the reader can act on.
- Never: "We are excited to announce", hype words (revolutionary, game-changing, guaranteed), false urgency, vague encouragement ("this is your sign"), explaining Talent Social to people who know it.
- Words: "assessment", never "audition". Never "proof of work" (say "earn the interview"). Never "can't cheat".

## 3. Anatomy of an issue (in this order)
1. Masthead: THE TALENT SOCIAL, issue badge, date line, tagline "Ideas. Opportunities. People."
2. Greeting and intro, 40 to 70 words.
3. Event block (only if event details are supplied): label, name, 2 to 3 sentences on why it is useful, date, time, area, one button.
4. Bridge line: "Now, for this week's story: meet …"
5. The feature (length depends on the type).
6. One soft second ask, at most one text link: a listen or watch link, "Want to be featured next?", the next-edition link, or none. Skip it when an event block runs.
7. Opportunities: "N roles worth checking out" (5 to 6): title, company, mode, location, "View role →"; then "Explore more opportunities →".
8. Footer: Powered by VettedAI; Talent Social, Nairobi, Kenya; why they receive it; LinkedIn, Instagram (and other channels only if active and owned; see CONFIG), Unsubscribe.

## 4. Design
Single column about 600 px; thin yellow rule on top; black, white and one yellow accent (about #F5D20A; confirm in Canva); dark event card with the poster and a yellow button; full-width dark band behind the feature headline; every image captioned; one button style (yellow, black uppercase text, arrow); pull quote set apart with its attribution. Tag every link to our own pages `utm_source=email&utm_medium=newsletter&utm_campaign=ts-issue-NNN`; third-party source links are not tagged. The event link carries a discount code unique to the issue.

## 5. Evidence labels
Tag every fact in a brief or draft:

| Label | Meaning | Use in copy |
|---|---|---|
| primary | the person's own words, or the original document | yes |
| second-hand | a reputable outlet reporting it (two or more agree) | yes |
| vendor | a company's own benchmark or claim | flag it as "a vendor claim" or cut |
| stale | older than two years or flagged outdated | cut unless the date is stated in the sentence |
| relayed | one report or blog says it and we have not seen the original | flag it in the sentence ("per one report"), or cut |
| inference | our own reading, not stated by any source | never as a fact; may appear as a question |
| internal | our prices, audience counts, check-in rates, strategy documents | never as a fact. A pull quote from an internal report is allowed if it contains no figures. |

Second-hand needs two outlets that agree; one outlet is `relayed`. Copy may use only `primary` and `second-hand` facts; `vendor`, `relayed` and `stale` facts need a flag in the sentence or are cut.

## 6. Hard rules (written once)
1. **One conversion ask.** When an event runs, the event button is the one ask. When none runs, the one ask is the jobs-page link ("Explore more opportunities"). Roles and one soft link are standing parts, not extra asks.
2. **No forward promise about who will be in the room.** Not "recruiters will be there", not "connect with recruiters actively hiring". Allowed: past-tense evidence or what we control ("roles from companies hiring through Vetted").
3. **No unsourced number, award, quote or testimonial.** Quotes stay verbatim, including transcript grammar. Prefer lines that read cleanly; if a line is too garbled, or its grammar would read badly in print, paraphrase it without quote marks. Unknowns are marked `{{NEEDS_VERIFICATION}}` and the issue does not send.
4. **Talent-paid products stay separate from jobs.** Never imply a ticket, Co-pilot or any paid product gets you seen by employers or improves your chances. Roles are free to apply for.
5. **People.** Public figures: public sources, their own words, credited. Members and panelists: written OK first (the "Get featured" form, and the speaker onboarding form, which includes permission for content and marketing).
6. **Images:** for a Community Spotlight, record the member's registration consent before using their supplied image. For a public feature, trace the image to its original online source and credit that source visibly. Attribution is not permission: prefer the person's or organisation's own press image, a licensed image, or our own graphic, and check the reuse terms before send.
7. **Vetted claims:** only APPROVED wording in `~/vetted-video/claims/REGISTER.md`. The only approved public proof line: "WorkPay cut its hiring cycle from 90 days to 30." Never name other clients as proof.
8. **Price:** no ticket price in a story issue. A discount mention is allowed in the event block.
9. **Persuasion and offer never mix.** A story issue carries no discount line. A discount may appear only inside an event block. The unique code on the event link is for tracking and is not stated in copy; an issue with no event block carries no code.
10. **Subscriber data stays out.** Never copy names or emails from campaign reports into drafts, logs or the repo.
11. **Mechanics:** links work and are tagged; the code is live; roles are still open; a test send has gone to two people.
12. **Send only to the opted-in Talent Social list.**

## 7. Anti-slop tests
Swap (replace "Talent Social" with another event: still reads the same? add house detail). Burial (the most valuable thing is in the subject or first two lines). Specificity (count the concrete nouns and numbers). Provenance (every claim traces to a real source).

## 8. Measures (from Issues 001 to 003, Zoho Campaigns)
Judge by unique clicks per 1,000 delivered, jobs-page clicks, tickets on the issue's code, and unsubscribes under 1%. Record opens but never judge by them: on this list most opens come from mail-privacy proxies and link scanners. Change one measured thing per issue (sender, send time, subject pattern, event position). The issue type changes by design, so log it with the result and do not claim a cause when type and another variable both changed. Weekly cadence is the target; if an issue is skipped, say so in the log. Tickets per issue are unmeasured. Past baselines are kept privately; ask Lemuel or Tobi.

## 8b. Word counts
The ranges in each skill count the feature body only: not headings, the lineup line, the "Try this week" box, the sources line, the roles block or the footer.

## 9. Feedback
Every run ends with: "Any feedback to log?" Entries go in `log/LESSONS.md` (append-only). A rule changes only after an entry exists.


---

<!-- FILE: CONFIG.md -->
# FILE: CONFIG.md

# Config (fill once; skills read this instead of guessing)

| Item | Value | Status |
|---|---|---|
| Jobs page | https://talent.vettedai.app/jobs | confirmed from the sent issues and by Lemuel, 21 Oct 2026. Source notes may show talent.vetted.ai/jobs: do not use it |
| Sender and voice | "Tobi @ Talent Social" for every issue, written in Tobi's first person | Lemuel, 21 Oct 2026 ("the newsletter will be written from tobi's pov"); supersedes the earlier split by theme |
| Newsletter list | the opted-in Talent Social list in Zoho Campaigns (list name kept privately) | list size comes from each report, never from here |
| Footer social links | Use only active, owned Talent Social channels. Start with LinkedIn and Instagram. Omit TikTok until an active owned account is confirmed. Exact URLs and unsubscribe merge tag remain `{{NEEDS_VERIFICATION}}`. | copy exact URLs and the unsubscribe tag from the live Zoho template; do not guess |
| Send time | Wednesday 15:30 EAT for the next four issues | recommended baseline, not a measured winner; past sends were Tue 15:27, Wed 17:35 and Wed 14:17, with type and sender confounded |
| Zoho Campaigns A/B split | Native A/B supports subject, sender or content on Standard, Professional and pay-as-you-go plans. Recommended subject test: A to 30%, B to 30%, same sender/content/time; click-rate winner to the remaining 40%. Start the test at 10:30 EAT and set the winner send for 15:30 EAT. | capability confirmed in Zoho help, 21 Oct 2026; confirm the account plan and that the A/B toggle appears before production |
| Event checkout and discount code | supplied per issue | per-issue code needed to count tickets |
| Claims register | private: ~/vetted-video/claims/REGISTER.md (source of truth), or the dated snapshot in the private working repo | if you cannot open it (for example, using the public kit), only the approved line in STYLE_GUIDE rule 7 passes |
| Image rights | Community Spotlight: member-supplied image covered by recorded registration consent. Public feature: original online source named and visibly credited; prefer the subject's or organisation's press image, a licensed image, or our own graphic, and verify reuse terms. | approved direction from Lemuel, 21 Oct 2026; attribution alone is not permission |

## Sender map

Every issue type: Tobi @ Talent Social, in Tobi's first person (Lemuel, 21 Oct 2026). The earlier map (Lemuel for Career Edge, public features and recruiter-led issues) is superseded. If a guest writes an issue, name them in the intro; the sender stays Tobi.

## Editorial workflow defaults

- When a past subject is unknown, draft new subject options before retrieving the sent line. This prevents the old answer from anchoring the creative pass.
- Test one variable at a time. For the next issue, test the subject only. Keep sender, preheader, content and timing identical across A and B.
- Judge the A/B winner by click rate. Opens remain unreliable for this list.
- Keep Wednesday 15:30 EAT fixed for four issues before considering a send-time experiment.


---

<!-- FILE: skills/1-input-to-brief.md -->
# FILE: skills/1-input-to-brief.md

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


---

<!-- FILE: skills/2a-draft-career-edge.md -->
# FILE: skills/2a-draft-career-edge.md

---
name: newsletter-2a-draft-career-edge
description: Draft a Career Edge issue (a known leader's path turned into lessons) for the Talent Social newsletter from a brief.
---

# 2a. draft-career-edge

Read `../STYLE_GUIDE.md` first. Reference: `../examples/issue-001-career-edge.md` (best clicks) and `issue-003-career-edge-ai.md` (current format).

## Input
A brief from skill 1 with three or more independent public sources.

## Steps
1. Headline = person + concrete move + outcome ("Kate Left NVIDIA to Build Amini AI: Now Growing Exponentially Out of Nairobi").
2. Open with the question behind the story, not the CV.
3. Two or three subheads that move the story ("From NVIDIA to building for Africa", "The problem she wanted to solve").
4. One pull quote in the person's own words, with where they said it.
5. At least two turns to the reader ("What problem do I understand well enough to start solving?").
6. Close with a question. Add a sources line.
7. Assemble the issue per the anatomy. Event block and roles are placeholders unless supplied.
8. Choose the soft second ask: a listen or watch link if one exists, otherwise none.

## Output
The full issue, paste-ready, 400 to 650 words in the feature. Then a short note: assumptions, and what must be confirmed before sending.

## Checks
- Every claim about the person is in two sources, or marked single-source.
- The quote is verbatim from a cited source.
- Images are supplied or our own.
- No claim about Vetted beyond the approved register wording.
- Hand to skill 3, then skill 4.

## Use in another tool
Paste `STYLE_GUIDE.md`, this file, and the brief. Ask for the draft.


---

<!-- FILE: skills/2b-draft-community-spotlight.md -->
# FILE: skills/2b-draft-community-spotlight.md

---
name: newsletter-2b-draft-community-spotlight
description: Draft a Community Spotlight issue (a member's story, with consent) for the Talent Social newsletter from a brief.
---

# 2b. draft-community-spotlight

Read `../STYLE_GUIDE.md` first. Reference: `../examples/issue-002-community-spotlight.md`.

## Input
A brief with the member's own words (interview notes or a form) and their **written OK**.

## Steps
1. Headline with the achievement and its scale ("She Built a Geospatial Community from 0 to 700+ in Her First Year").
2. Open on the gap the member saw.
3. Tell it in three beats: the gap, what they built, what they are doing next. Short paragraphs.
4. A boxed "The takeaway": one line the reader can act on ("Start before you're ready").
5. The soft ask: "Want to be featured next?" with the form link.
6. Assemble per the anatomy. 350 to 550 words in the feature.

## Output
The full issue, paste-ready, and a note on what to confirm.

## Checks
- Consent is recorded in the brief; if not, stop.
- Nothing the member did not say or confirm. No employer, salary or private detail without their OK.
- Facts such as member counts, dates and programmes are in the member's words or a named source.
- Hand to skills 3 and 4.

## Use in another tool
Paste `STYLE_GUIDE.md`, this file, and the brief.


---

<!-- FILE: skills/2c-draft-panel-insight.md -->
# FILE: skills/2c-draft-panel-insight.md

---
name: newsletter-2c-draft-panel-insight
description: Draft a Panel Insight issue (one idea from one panelist) from a panel transcript for the Talent Social newsletter. One transcript can become several issues.
---

# 2c. draft-panel-insight

Read `../STYLE_GUIDE.md` first.

## Input
- The panel transcript.
- The panelist chosen (one per issue) and their consent (the speaker onboarding form, which includes content and marketing use).

## Steps
1. Pick the one idea that is useful to someone who was **not** in the room.
2. Headline = the idea, with the panelist and their role ("[The idea in a few words]: [Panelist name], [role]").
3. Open on the problem the idea answers.
4. Use the panelist's own words as the pull quote.
5. A short "Try this week" step for the reader (one concrete action).
6. The one soft link may go to the next edition, only if no event block runs. No promise about who attends it. Otherwise leave it out.
7. 300 to 500 words in the feature. Assemble per the anatomy.

## Variant: edition summary
Use when several panelists are worth covering and the owner confirms consent for all of them. Write three or four ideas, one per speaker with a mapped section, each with a verbatim quote and a "For your own career" turn, then one "Try this week" step. Attribute each idea through the speaker map and add context from the fullest version of the speaker's profile (our own event copy first); name the speaker only as far as the map and profile support. Skip short lines that could be another voice. Name the whole lineup in one line under the headline; if a speaker's section cannot be used, say so in the confirm notes, never drop them silently. The headline names the ideas, not one person. If a speaker is also the sender, flag it for the owner. The feature is still 300 to 500 words.

## Output
The full issue and a note on what to confirm. For a month plan, one issue per panelist, in separate runs.

## Checks
- The quote is verbatim from the transcript, with its grammar as transcribed. Do not clean it.
- **Attribution follows the router's naming rule** (`ROUTER_PROMPT.md`, "Naming speakers"). If the moderator is Tobi, write the moderator's lines in Tobi's first person.
- Panelist consent is on file.
- No claim about attendance or who will be at the next edition.

## Use in another tool
Paste `STYLE_GUIDE.md`, this file, the transcript and the panelist's name.


---

<!-- FILE: skills/2d-draft-research-brief.md -->
# FILE: skills/2d-draft-research-brief.md

---
name: newsletter-2d-draft-research-brief
description: Draft a Research Brief issue ("what the data says about X", three findings and what to do) for the Talent Social newsletter from a research report. No person is featured.
---

# 2d. draft-research-brief

Read `../STYLE_GUIDE.md` first.

## Input
A brief from skill 1 built from a deep-research report or a sourced article set. If the source is an **internal strategy document**, use it only for behaviour findings, never for prices, audience counts or check-in rates.

## Steps
1. Headline = the finding, not a person ("Why We Skip What We Meant to Do: 3 Findings").
2. Open on a situation the reader knows.
3. Three findings. For each: the finding in one line, its evidence label and source named in the sentence, and one thing the reader can do this week.
4. A pull quote from the source or report, with where it comes from.
5. A bridge line that does not name a person ("Now, the evidence:").
6. Close with a question. Add a sources line with dates.
7. Assemble per the anatomy. 350 to 550 words in the feature.

## Output
The full issue and a table of the findings used and left out, with the reason for each.

## Checks
- Only `primary` or `second-hand` evidence in the body. `vendor` or `stale` figures are flagged in the sentence or cut.
- No internal figure.
- Single-source findings are marked as single-source.
- No finding that invites an obvious reply because our own page does the opposite. Hold it, or swap it.
- No recommendation that tells talent to pay for a product.

## Use in another tool
Paste `STYLE_GUIDE.md`, this file, the brief and the report.


---

<!-- FILE: skills/2e-draft-roles-and-a-tip.md -->
# FILE: skills/2e-draft-roles-and-a-tip.md

---
name: newsletter-2e-draft-roles-and-a-tip
description: Draft the short Roles and a Tip issue (live roles plus one practical tip) for the Talent Social newsletter. Use in a week with no feature ready, to keep the weekly cadence.
---

# 2e. draft-roles-and-a-tip

Read `../STYLE_GUIDE.md` first.

## Input
- The live jobs list from the **same week** (talent.vettedai.app/jobs).
- One tip with a source: from a past issue, a transcript or a sourced article.

## Steps
1. A warm two-line intro that names what is inside.
2. One tip: the situation, the step, why it works, the source. 100 to 150 words.
3. 5 to 6 roles, mixed by level, field and location: title, company, mode, location, "View role →". Pick from the owner's priority list of paying clients, limited to roles on the public board (the board and platform tools do not show who pays, so ask for the list). The board gives no per-role link, so "View role" goes to the company page. Then "Explore more opportunities →".
4. A soft event link only if event details are supplied.
5. Assemble per the anatomy. 150 to 250 words in total before the roles.

## Output
The full issue and a note on which roles to confirm are still open.

## Checks
- Every role is still open on send day.
- Company names appear only as the posting uses them; use the posting's own anonymised name otherwise.
- No salary claim.
- The tip's source is named; no unsourced statistic.

## Use in another tool
Paste `STYLE_GUIDE.md`, this file, the jobs list and the tip.


---

<!-- FILE: skills/3-subject-and-preview.md -->
# FILE: skills/3-subject-and-preview.md

---
name: newsletter-3-subject-and-preview
description: Write and choose subject lines and preheaders for a Talent Social newsletter issue, with one A/B test per issue.
---

# 3. subject-and-preview

Read `../STYLE_GUIDE.md` first.

## Input
A finished draft or brief with its key message.

## Steps
1. Write up to four subject lines, one per pattern that can be written honestly, each under about 60 characters. Mark a pattern **N/A** when it cannot be (a Research Brief has no named person; a time anchor needs a real date):
   - **Named person + concrete achievement:** "Meet [Name], who [one concrete achievement]"
   - **Tension:** "Building AI where being wrong has real consequences"
   - **Time anchor** (only with a real date): "Tonight: …"
   - **Plain statement of the finding:** "Three findings on why we skip what we meant to do"
2. Write a preheader for each that **adds** a fact and does not repeat the subject.
3. Pick two pairs. Name the one reason for each pick.
4. Plan the test using the native random split and winner remainder in `../CONFIG.md`. Change only the subject; use one preheader for both (pick the stronger of the two you wrote), and keep sender, content and timing identical. If the account plan does not expose A/B testing, do not compare subjects across weeks: the content differs, so the result is not a subject test. Judge any test by click rate and clicks per 1,000 delivered, never opens.

## Output
Two recommended pairs, the reason, and the test plan. Put the sent subject line into the performance log.

## Checks
- A reader can guess the key message from the subject.
- The most valuable thing is in the subject or the first two lines.
- No ticket price in a story issue. No hype words.
- No named company or recruiter promised in the room.
- No emoji claims. If emoji is used, it is the same one used before, so the effect is not confounded.

## Use in another tool
Paste `STYLE_GUIDE.md`, this file and the draft.


---

<!-- FILE: skills/4-claims-and-voice-check.md -->
# FILE: skills/4-claims-and-voice-check.md

---
name: newsletter-4-claims-and-voice-check
description: Check a finished Talent Social newsletter draft against the claims register, house guardrails, voice and mechanics, and return a verdict. Use before every send.
---

# 4. claims-and-voice-check

Read `../STYLE_GUIDE.md` first.

## Input
The finished draft (and its brief, if available).

## Steps
1. Run the 12 hard rules in the style guide. For each: PASS or FAIL, with the failing line quoted.
2. **Claims register.** Find every statement about Vetted (results, product, pool sizes, WorkPay). Look each up in `~/vetted-video/claims/REGISTER.md` if you can open it. Only APPROVED wording passes. PENDING or WITHDRAWN fails. If you cannot open the register (for example, in a chat using the public kit), only the approved line in STYLE_GUIDE rule 7 passes; any other claim about Vetted is a FAIL until Lemuel checks it. Also apply the wording rules in `~/vetted-video/claims/WORDING.md` and the banned phrases and domains in `~/vetted-video/claims/banned.txt`. The dated snapshot in `../docs/claims-snapshot/` has REGISTER and WORDING but not banned.txt, so if vetted-video is not cloned, say banned.txt was not checked. The register has no row for the footer line "Powered by VettedAI": treat it as standing house wording and flag it if the footer changes.
3. **Words.** "assessment" not "audition"; no "proof of work"; no "can't cheat".
4. **Quotes.** Check each against the source text. Not verbatim means FAIL. Then read the sentences around each quote: a paraphrase that adds a claim the speaker did not make is a FAIL too.
5. **Anti-slop tests:** swap, burial, specificity, provenance.
6. **Mechanics:** links work, UTM-tagged, discount code live and unique, roles still open, test send planned.
7. **Voice:** flag corporate throat-clearing, hype, category explanation, and vague encouragement.

## Output
```
VERDICT: SAFE TO SEND | FIX BEFORE SENDING | DO NOT SEND

FAILURES
1. [Rule] "quoted line"
   -> Fixed: [replacement line]

WARNINGS
- ...

MUST FILL BEFORE SEND
- ...

MUST CONFIRM BEFORE SEND
- ...
```
DO NOT SEND: an unsourced claim about a real person, a forward promise about who is in the room, a breach of rule 4 (talent-paid products), or a banned phrase in the subject.

## Placeholders
Unfilled placeholders (roles, links, images, event details, code) are not FAILs. List them under "MUST FILL BEFORE SEND" and give the verdict FIX BEFORE SENDING. Rules 3 and 11 pass only once they are filled and checked.

## Checks on itself
- Every FAIL includes replacement text.
- It does not rewrite for taste.
- If the copy passes, say so plainly.

## Use in another tool
Paste `STYLE_GUIDE.md`, this file, and the draft. Paste the register rows for any Vetted claim you used.


---

<!-- FILE: skills/5-performance-log.md -->
# FILE: skills/5-performance-log.md

---
name: newsletter-5-performance-log
description: Log a sent Talent Social newsletter issue's performance at 48 hours and 7 days, and record one lesson. Use after each send.
---

# 5. performance-log

Read `../STYLE_GUIDE.md` first.

## Input
From the Zoho Campaigns report (aggregates only): sent, delivered, unique clicks, click-to-open, unsubscribes, complaints, top three links with counts. Plus: the subject line and sender actually used, the send time, tickets bought with the issue's discount code, and jobs-page clicks.

## Steps
1. Add one row to `../log/performance-log.csv` (columns as in the file). Compute **clicks per 1,000 delivered** = unique clicks ÷ delivered × 1,000.
2. Mark anything not available as `unmeasured`, never blank or zero.
3. Compare with the **previous issue only**. Say what changed between them (sender, send time, type, subject pattern, event block position).
4. Write one lesson in one line.
5. Append a lesson entry to `../log/LESSONS.md`. In a chat, where you cannot write files, give the row and the lesson entry for the person to send to Lemuel.

## Output
The CSV row and a three-line summary: the number that moved, what changed, the lesson.

## Checks
- **Never copy subscriber names or emails** from the report (the "most opened" lists contain them). Counts only.
- If more than one thing changed, say the cause is unknown. Do not pick one.
- Opens are recorded but never used to judge.
- Delivered comes from this report, not from a file or memory.

## Use in another tool
Paste `STYLE_GUIDE.md`, this file, the report numbers (not the report file), and the CSV.


---

<!-- FILE: templates/issue-brief.md -->
# FILE: templates/issue-brief.md

# Issue brief (fill before writing)

- Issue number / send date and time:
- Type: Career Edge | Community Spotlight | Panel Insight | Research Brief | Roles and a Tip
- Input file(s):
- Audience (list, size):
- Key message (one sentence):
- Hook (opening question or situation):
- Subject line options (2) / preheader (2):
- Primary CTA (one: the event button if an event runs, otherwise the jobs-page link):
- Event block? yes/no. If yes: name, date, time, area, checkout link, discount code (unique to this issue):
- Soft second ask: listen/watch link | get featured | none
- Roles (5 to 6, live this week):
- Feature person and consent status (written OK / public figure):
- Images and rights:
- Fact pack attached? yes/no (nothing unverified goes in)
- One thing changed from last issue (for learning):


---

<!-- FILE: templates/issue-draft.md -->
# FILE: templates/issue-draft.md

# Issue NNN draft

**Subject:** 
**Preheader:** 

## Masthead
THE TALENT SOCIAL · ISSUE NNN · [Weekday, D Month YYYY]

## Greeting and intro (40 to 70 words)
Hello there,

## What's Happening (event block, if any)
Label · Event name · 2 to 3 sentences · Date · Time · Area · [BUTTON TEXT →] · link

## Bridge
Now, for this week's story: meet …

## Feature
SECTION LABEL
**Headline**
Opening (question or situation)
### Subhead
…
> Pull quote. (Name, where said, year)
### What can we learn from [Name]'s journey?
For your own career …
Closing question.
References: …

## Second ask
[Want to go deeper? LISTEN →] or [Want to be featured next? GET FEATURED →]

## Opportunities: N roles worth checking out
Title · Company · Mode · Location · View role →
Explore more opportunities →

## Footer
Powered by VettedAI · Talent Social, Nairobi, Kenya · reason they receive it · LinkedIn | Instagram | Unsubscribe

## Guardrail check (paste result)
Verdict: 


---

<!-- FILE: templates/performance-log.csv -->
# FILE: templates/performance-log.csv

issue,type,sent_at_eat,sent_to,delivered_pct,unique_opens_pct,unique_clicks,clicks_per_1000_delivered,click_to_open_pct,unsubscribes_pct,complaints,top_link_1,top_link_2,tickets_on_code,jobs_page_clicks,what_changed,lesson


---

<!-- FILE: examples/WHAT-WORKED.md -->
# FILE: examples/WHAT-WORKED.md

# What Issues 001 to 003 teach

Lessons from the first three sends. The numbers are kept privately; these are the patterns.

1. The roles block drove the most clicks in two of the three issues, and came second in the third. Keep it every issue, with the "Explore more opportunities" link.
2. The event block drew a steady number of clicks wherever it sat.
3. Issue 001's "listen to the conversation" link was used. Issue 002's "get featured" ask was not among the top links.
4. Issue 002 changed sender, send time and story type together, so its lower numbers can't be pinned on one cause.
5. Opens are unreliable on this list (mail-privacy proxies and link scanners). Judge by clicks.
6. Issue 003 used a per-issue discount code in the event link. Do this whenever an event block runs, so tickets can be counted.
7. Weak spots to fix: Issue 001 says "Nairobi's #1 Recruitment Event" with no source, and describes recruiters and hiring teams "in the same room" (a soft forward promise). Link tagging was inconsistent across issues.


---

<!-- FILE: examples/issue-001-career-edge.md -->
# FILE: examples/issue-001-career-edge.md

# Issue 001: The Career Edge (sent Tue 22 Sep 2026)

Type: Career Edge (public figure). Event block: Talent Social, Thursday 24 Sep. Roles: 5. Text extracted from the sent PDF; layout lost.

THE ISSUE 001
TALENT
 Ideas. Opportunities. People.
SOCIAL
Hi there,
Welcome to the first edition of The Talent Social Newsletter.
You’re receiving this as part of the Talent Social community: a network of people
building meaningful careers and staying close to new opportunities.
This is a space for practical career stories, useful opportunities and honest
lessons from people navigating their own professional journeys. Each issue will
bring you ideas to think about, roles worth exploring and updates from across the
Talent Social community.
To start, we’re looking at Dr. James Mworia’s journey from intern to CEO and
what it can teach us about preparing for the opportunities ahead.
THE CAREER EDGE
He started as an intern.
Worked his way to CEO.
What Dr. James Mworia’s journey can teach you about curiosity,
responsibility and moving closer to your next big thing.
Dr. James Mworia during his years at Centum. Source :https://thekenyatimes.com/latest-kenya-times-news/centum-ceo-
james-mworia-lands-top-job-at-national-infrastructure-fund/
At 30, Dr.James Mworia became CEO of Centum Investment. Seven
years earlier, he had joined the organisation as an intern.
That sounds like an extraordinary career leap. But the useful part of the
story is not the title. It is what he did before the opportunity arrived.
His first assignment was simple: work through the files.
So he did. But he also read them.
He wanted to understand what was behind the numbers, how
investment decisions were made, and how the wider business actually
worked.
That curiosity eventually earned him a permanent role as an accountant
after he topped a quiz administered to staff by the CEO at the time.
For your own career, that is the first lesson: do the job you have
well, but do not stop at the job description. Learn enough about the
business around you to understand where bigger problems and bigger
opportunities sit.
 “What would actually change if I stopped doing my
 job?”
That question pushed him to look beyond the work immediately in front
of him.
He wanted to be closer to the decisions that created the numbers, so he
looked for opportunities to take on more.
That eventually led him into investments and, within a few years, to
Head of Investments.
The career lesson: growth often starts before the promotion. If you
want greater responsibility, start learning how the people one level
above you think, decide and solve problems.
Dr. James Mworia speaking during a public conversation. Source
https://nairobileo.co.ke/business/article/29994/centum-names-acting-ceo-as-james-mworia-exits-after-18-years
Build range. Think beyond your role.
Dr. Mworia’s path was never built around one narrow skill. His exposure
to law, business, accounting and finance gave him different ways to
understand how organisations work. He came to describe accounting as
“a language of business.”
As Head of Investments, he also began looking beyond the
responsibilities directly in front of him.
When he saw opportunities he believed Centum should pursue, he
developed ideas for where the organisation could go next.
Later, when the board asked him to return, he came back with a
strategy, not simply a request for a bigger title.
For your own journey: build skills beyond your current job and start
thinking about problems beyond your current level. The more you
understand the wider business, the more prepared you become for
bigger responsibility.
Dr. James Mworia speaking during a panel at Africa Capital Week. Source https://techtrendske.co.ke
The next chapter
Dr Mworia went on to lead Centum for nearly two decades. In
September 2026, he was appointed CEO of Kenya's National
Infrastructure Fund, taking the experience he built across investment,
capital allocation and institution building into a new challenge.
That is what makes his story useful beyond the headline “intern to CEO.
 "You do not need to have your entire career figured out
 today. You need to keep becoming more useful for the
 opportunities that come next."
So ask yourself: what can I learn in the role I have today that will
make me ready for a bigger problem tomorrow?
References: Capital Business, Business Daily, The Standard, The Room Podcast, The Star
 WA N T T O G O D E E P E R ?
 Hear Dr. James Mworia tell the story in his own
 words.
 LISTEN TO THE CONVERSATION →
W H AT ’ S H A P P E N I N G
Nairobi’s #1 Recruitment Event is back this
Thursday.
The Talent Social brings professionals, recruiters and hiring teams into the
same room for conversations that go beyond the job board.
D AT E L O C AT I O N
September 24, 2026 Nairobi, Kenya
 SAVE YOUR SPOT →
OPPORTUNITIES
5 roles worth checking out
A quick shortlist from VettedAI.
Video Editor, Short-form Content
VettedAI · Hybrid · Kenya
VIEW ROLE →
Head of Cybersecurity (CISO)
Global-Backed Payments Scale-Up · Full-time · Nigeria, Kenya, South Africa, UAE
VIEW ROLE →
Talent Acquisition Specialist
Safal Group · Full-time · Kenya
VIEW ROLE →
Event Planner, Private Wedding
A&O · On-site · Full-time · Kenya
VIEW ROLE →
Senior Application Security Engineer
Paystack · Remote · Africa
VIEW ROLE →
Explore more opportunities →
Powered by VettedAI
The Talent Social
Nairobi, Kenya
You are receiving this email because you signed up to join a Nairobi Talent Social mailing list.
LinkedIn | Instagram | TikTok | Unsubscribe



---

<!-- FILE: examples/issue-002-community-spotlight.md -->
# FILE: examples/issue-002-community-spotlight.md

# Issue 002: Community Spotlight (sent Wed 7 Oct 2026)

Type: Community Spotlight (member story). Event block: Panel Edition, Thursday 15 Oct. Roles: 6. Sender changed to a personal address this issue.

THE ISSUE 002
TALENT
 Ideas. Opportunities. People.
SOCIAL
Hi there,
Welcome to the second edition of The Talent Social Newsletter.
This issue is about what happens when you stay curious, build before you feel
fully ready, and keep showing up for new opportunities.
W H AT ’ S H A P P E N I N G : TA L E N T S O C I A L PA N E L E D I T I O N
Building and Scaling with AI
Talent Social is back with Building and Scaling with AI: an honest
conversation with people doing the actual work, on how companies are
really using AI to build and grow.
D AT E & T I M E L O C AT I O N
Thursday, 15 October Westlands, Nairobi
From 6:00 pm Venue shared with ticket holders
 SAVE YOUR SPOT →
COMMUNITY SPOTLIGHT
She Built a Geospatial Community from 0 to
700+ in Her First Year
Meet Valentine Irungu saw a gap in her industry and decided to do
something about it.
While studying Geospatial Information Science at JKUAT, she noticed
that students were learning GIS, but connecting that knowledge to
industry, emerging technology and real-world opportunities was not
always easy.
As Chairlady of the Association of Geomatics & Geospatial Engineering
Students, she helped organize GIS Day 2022, bringing together more
than 500 students and five companies.
But she did not stop there.
She Built the Connection Herself
In 2024, Valentine founded GeoCode Connect Africa, a community
connecting students, young professionals, developers, researchers and
industry experts across Africa.
What began as an idea to bridge a gap in her own field grew to 700+
members in its first year.
At the same time, she kept expanding her own skills. Through ALX
Kenya, she learned frontend development and began building websites,
dashboards and applications that combine maps, data and software.
That included building her own portfolio website and the GeoCode
Connect Africa website, which she launched in May 2026.
Exploring AI for Better Health Outcomes
From January to June 2026, Valentine stepped into another new field
through the IDIA Fellowship Programme by Qhala.
Alongside Dr. Wanjiru Kigathi and Dr. Diana Oigara, she co-authored
SGBV-Bench, the first bilingual English-Swahili clinical AI benchmark
grounded in Kenya’s sexual violence care guidelines.
Their work helps create a foundation for evaluating safer, more relevant
AI tools for survivor care in African healthcare settings.
For Valentine, it was another opportunity to move beyond learning and
contribute to work with real-world impact.
 Valentine at the IDIA Fellowship Programme by Qhala.
 T H E TA K E AWAY
 Start Before You’re Ready
 Valentine’s story is a reminder that you do not need to have
 everything figured out before you begin.
 She saw a gap and acted. She learned new skills, entered unfamiliar
 spaces and kept building.
 Start the project. Learn the skill. Enter the room. Build the thing.
 Growth rarely follows a straight line. Sometimes the next opportunity
 begins with simply being willing to start.
 WA N T T O B E F E AT U R E D N E X T ?
 We’re always ready to showcase top talent.
 If you’re building meaningful work, solving interesting problems or creating
 impact in your field, click below for the right people to discover your story.
 GET FEATURED HERE →
OPPORTUNITIES
6 roles worth checking out
Business Development & Client Relations Manager
Pink Ivory Catering
VIEW ROLE →
Principal Role - Business Consulting
Intellecap Advisory Services Private Limited
VIEW ROLE →
Head of Cybersecurity (CISO)
Global-Backed Payments Scale-Up
VIEW ROLE →
Senior DBA
Paystack
VIEW ROLE →
Partnerships & Strategy Fellow
VettedAI
VIEW ROLE →
Business Intelligence Analyst
4G Capital
VIEW ROLE →
Explore more opportunities →
Powered by VettedAI
The Talent Social
Nairobi, Kenya
You are receiving this email because you signed up to join a Nairobi Talent Social mailing list.
LinkedIn | Instagram | TikTok | Unsubscribe



---

<!-- FILE: examples/issue-003-career-edge-ai.md -->
# FILE: examples/issue-003-career-edge-ai.md

# Issue 003: Career Edge, AI theme (sent Wed 14 Oct 2026)

Type: Career Edge (public figure) with the Panel Edition event block at the top and a discount through the newsletter. Roles: 6 in a card grid. This is the current reference issue.

THE ISSUE 003
TALENT
SOCIAL Ideas. Opportunities. People.
W E D N E S D AY, 1 4 O C T O B E R 2 0 2 6
Hello there,
Welcome to this edition of the Talent Social Newsletter.
This week, we're spotlighting people who are using their experience to build,
create and make room for new opportunities with AI.
But first, we're featuring our very first Talent Social Panel Edition, designed to
help you take the next step in your AI journey.
 W H AT ' S H A P P E N I N G · TA L E N T S O C I A L PA N E L E D I T I O N
 Building and Scaling with AI
 Want to move from talking about AI to actually building with it?
 Join us at Talent Social: Building and Scaling with AI for practical insights,
 real experiences and meaningful connections this Thursday, 15 October,
 at 6 PM in Westlands, Nairobi.
 Since you are part of the Talent Social community, you get an exclusive
 discounted ticket through this newsletter!
 SAVE YOUR SPOT →
Now, for this week's story: meet Kate Kallot, who took her experience at global
technology companies and set out to build the AI infrastructure Africa needs.
WORKING IN AI · THE CAREER EDGE
Kate Left NVIDIA to Build Amini
AI: Now Growing Exponentially
Out of Nairobi
It's no secret that AI has changed how we work, build businesses and solve
problems. But as the world races to develop AI, one important question remains:
Will Africa simply use the technology, or will we also have the infrastructure
to build our own AI?
For Kate Kallot, this question became the foundation of starting a business.
Kate Kallot featured by Forbes Africa.
From NVIDIA to building for Africa
Before founding Amini AI, Kate worked with technology companies including Intel,
Arm and NVIDIA. Her career gave her a close look at what AI could make
possible, and the infrastructure required to make it work.
She also recognised a gap.
While AI was advancing rapidly around the world, many African countries and
other parts of the Global South lacked access to reliable local data and the
computing infrastructure needed to develop their own solutions.
With family roots in the Central African Republic, Kate saw a challenge that went
beyond talent or ambition: the foundations to support innovation were missing.
Instead of waiting for someone else to address the problem, she decided to
build.
The problem she wanted to solve
In 2022, Kate founded Amini AI in Nairobi, initially focusing on Africa's shortage
of reliable environmental data.
But as the company evolved, Kate recognised a bigger need: data alone wasn't
enough. Africa also needed the computing infrastructure to process it and build its
own AI systems.
 “Data is the start of any economic revolution.”
 Kate Kallot, quoted by TIME, 2023
Kate speaking at the TIME100 Impact Awards.
Today, Amini AI is working on locally controlled data and AI infrastructure to help
governments and businesses manage, process and use information closer to
home.
That includes computing capacity, local AI hubs and modular infrastructure for
different markets. Its work has extended beyond Kenya to initiatives in Côte
d'Ivoire and Barbados.
For these achievements, Kate received a TIME100 Impact Award in 2025 for her
work developing AI capabilities in the Global South.
What started as an environmental-data challenge grew into a larger mission:
helping African countries participate in AI as builders, not only users.
What can we learn from Kate Kallot's journey?
Kate Kallot featured in a Forbes 30 selection committee graphic.
Kate looked beyond the latest AI applications and asked what Africa needed to
build solutions of its own. Her journey shows that experience gained elsewhere
can become a strength when applied to local problems.
You may not be building AI infrastructure like Kate, but you can ask yourself:
What problem do I understand well enough to start solving with AI?
It might be a slow process at work, a challenge in your industry or a service that
could reach more people.
The next step is learning how to turn that insight into something useful, test it with
real people and grow it into a sustainable solution.
Where could your own skills make a difference?
That's the conversation we're bringing to Talent Social Panel Edition tomorrow
Thursday, 15 October.
Further reading: TIME profile · Amini · UNDP on Africa and AI
OPPORTUNITIES
6 roles worth checking out
 PI
 Pink Ivory Catering Intellecap Advisory Services
 Business Development & Client Principal Role - Business
 Relations Manager → Consulting →
 Nairobi, Kenya Nairobi, Kenya
 Full-Time Full-Time
 SLATE
 Slate Systems Lab Group Paystack
 Head of Operations, Commercial → Senior Application Security
 Nairobi, Kenya Engineer →
 Full-Time
 Africa
 Remote
 SAFAL
 Safal Group
 Brand and Growth Lead →
 Talent Acquisition Specialist →
 Nairobi, Kenya
 Nairobi, Kenya
 Hybrid
 Full-Time
 EXPLORE MORE OPPORTUNITIES →
Talent Social · Nairobi, Kenya
You are receiving this email because you signed up for the Talent Social mailing list.
LinkedIn | Instagram | TikTok | Unsubscribe



---

END OF KIT
