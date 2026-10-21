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
