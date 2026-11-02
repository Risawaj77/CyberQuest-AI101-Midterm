# CYBERQUEST — AI 101 Midterm App

**Live site:** https://risawaj77.github.io/CyberQuest-AI101-Midterm/

## Audience and purpose
First-year college students who want a safe way to practice recognizing phishing red flags without handling malicious emails or exposing personal data.

## Features
1. **Interactive simulated inbox:** six fictional messages, safe/suspicious choices, feedback and progress tracking.
2. **Signal Scanner:** enter fictional practice messages to find simple warning phrases and read educational safety guidance.
3. **Self Tests:** eight built-in checks for sample data and scanner rules.

## How to run and use
Open the live URL above in Chrome, Edge or another modern browser. Select a case and choose suspicious or safe to reveal an explanation; use Reset training to try again. Scroll to Signal Scanner and enter fictional practice text, then select Scan for warning signs. Under Self Tests, click Run 8 tests.

To run locally, download the repository and open index.html directly in a browser. No server, API key or subscription is necessary.

## Sources and credits
The educational examples and explanations are fictional, created with ChatGPT assistance and reviewed through browser tests. No real phishing messages, real student records, or external datasets were used. This is a demonstration of common social-engineering patterns, not a validated cybersecurity guidance service.

## Known limitations
- The scanner uses JavaScript keyword-matching rules, not a live AI API or authoritative detector.
- It may miss sophisticated scams and may flag harmless messages.
- “No warning phrases” never means “safe.” Verify senders independently.
- No external source verification, real email integration, persistent account or security certification.
- See TEST_LOG.md for observed tests and remaining unverified keyboard/narrow-screen/empty-input checks.

## Assignment evidence
- [Five-plus recorded test observations and mandatory-category gaps](TEST_LOG.md)
- [AI Use Note and prompt record](AI_USE.md)
- [Evidence and revision](EVIDENCE.md)
- [Original issue](https://github.com/Risawaj77/CyberQuest-AI101-Midterm/issues/1)
- [Merged pull request / before-after code diff](https://github.com/Risawaj77/CyberQuest-AI101-Midterm/pull/2/files)
