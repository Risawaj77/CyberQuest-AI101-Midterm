# CYBERQUEST — Midterm App Evidence
**Student:** Rimas Awaji
**Course:** AI 101
**Audience:** First-year college students
**Purpose:** Teach phishing awareness safely with fictional messages.

## Two working features
1. Inbox practice cases: choose safe/suspicious, receive a rationale, and track progress.
2. Signal Scanner: enter fictional text to identify rule-based warning phrases and receive safety guidance.

Additional behavior: reset training and eight built-in automated self-checks.

## Prompts and revision
See AI_USE.md for representative prompt history and the caveat about exact transcript wording.

**Problem:** No-match guidance was too brief to guide safe verification.
**Improvement:** Expanded the scanner response to remind students that no match does not guarantee safety and recommend verifying senders and links independently.
**Before/after code evidence:** https://github.com/Risawaj77/CyberQuest-AI101-Midterm/pull/2/files

### Actual screenshot evidence
Screenshots of the live app's quiz explanation, scanner warning matches, neutral-message retest, and 8/8 checks were provided in the classwork conversation. Separate before/after *UI screenshots* have not been verified as uploaded into this repository. The PR Files changed page is source-level before/after evidence, but it is not a substitute for a required screenshot pair.

## Test outcomes
See TEST_LOG.md. Three mandatory categories (empty/invalid, keyboard accessibility, narrow screen) still need live verification before claiming this lab's entire testing checklist is complete.

## Live project
https://risawaj77.github.io/CyberQuest-AI101-Midterm/
