# AI Use Note

**Tool:** ChatGPT (AI-assisted coding and documentation). **Purpose:** Help brainstorm, build, revise, and verify a self-contained phishing-awareness teaching prototype for first-year college students.

## Representative prompts
- “Make another, impressive project.”
- “Build a good one that actually works.”
- “Can you do it yourself?” (requesting an update to the existing GitHub project)

## AI contribution and student decisions
AI helped draft the HTML/CSS/JavaScript prototype, six fictional examples with explanations, simple scanner rules, built-in self-checks, and documentation. The student selected a cybersecurity awareness topic, used the published site, performed browser interactions and submitted screenshots of results. The student remains responsible for understanding and explaining the final code and findings.

## Tracked improvement
Issue #1: https://github.com/Risawaj77/CyberQuest-AI101-Midterm/issues/1

Pull Request #2: https://github.com/Risawaj77/CyberQuest-AI101-Midterm/pull/2

The student requested AI help implementing the improvement. The scanner's original no-match warning was expanded to advise checking the sender via a trusted channel, verifying links independently, and not sharing passwords or personal details. The PR includes a source-diff review comment and was merged into `main`. This does not claim independent human code approval.

## Verification actually completed (November 2, 2026)
The student tested the deployed website in a browser and supplied screenshots of: Case 1 suspicious decision and explanation (PASS); suspicious input with warning-sign output (PASS); neutral text showing the revised no-match safety guidance (PASS); and all eight automated self-checks displaying 8/8 PASS. The student also reported that Reset training restored the counters to zero (PASS, confirmation without a screenshot). Results and evidence descriptions are recorded in `Test_Log.csv`. These checks do not constitute a security audit. The blank input, Next case, and safe-case browser tests have not yet been recorded as completed.

## Limitations and disclosure
This site does not use a live AI API. The scanner is based on simple keyword patterns, so it can miss suspicious messages or flag harmless messages. A rule match proves neither fraud nor safety. All examples are fictional; do not enter real credentials or private messages. Screenshots of the before/after code difference and the remaining manual test evidence may still be needed for submission.
