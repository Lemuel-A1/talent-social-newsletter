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
5. Append a lesson entry to `../log/LESSONS.md`.

## Output
The CSV row and a three-line summary: the number that moved, what changed, the lesson.

## Checks
- **Never copy subscriber names or emails** from the report (the "most opened" lists contain them). Counts only.
- If more than one thing changed, say the cause is unknown. Do not pick one.
- Opens are recorded but never used to judge.
- Delivered comes from this report, not from a file or memory.

## Use in another tool
Paste `STYLE_GUIDE.md`, this file, the report numbers (not the report file), and the CSV.
