# AI Use Note — Midterm App Submission
**Tool:** ChatGPT (AI assistance in prototyping, writing, code revision, and test documentation).
**Audience:** First-year college students.
**Purpose:** Practice detecting phishing warning signs using fictional messages.

## Prompt record
The original project discussion included the student requests:
- “Make another, impressive project.”
- “Build a good one that actually works.”
Later follow-up request:
- “Can you do it yourself?” (request to implement the tracked GitHub improvement directly).

These are representative conversation prompts, **not a certified verbatim complete initial prompt transcript**. The student should replace these with the exact original prompts if the instructor requires an exact verbatim initial/follow-up pair.

## What AI contributed
Drafted the self-contained HTML/CSS/JavaScript app, fictional examples, rules for the scanner, interactive quiz feedback, self-check code and supporting documentation. AI also updated the no-match explanation in PR #2.

## Student decisions and verification
The student chose cybersecurity education and tested the published app in Chrome. Screenshots showed suspicious-message feedback, two and three matched scanner warnings, no-match guidance, and 8/8 self-tests. The student reported reset working. Some course-specific tests remain unverified, and those are marked NOT RUN in TEST_LOG.md.

## Meaningful revision
Before: A short no-match warning with no next steps.
After: Explicit advice to verify senders through a trusted channel, inspect links independently, and avoid disclosing passwords and personal information.
Issue: https://github.com/Risawaj77/CyberQuest-AI101-Midterm/issues/1
PR: https://github.com/Risawaj77/CyberQuest-AI101-Midterm/pull/2/files

## Limits
This is not a live AI detector or an email security product. Keyword rules can produce false positives/negatives. No private data should be entered, and the example messages are entirely fictional.
