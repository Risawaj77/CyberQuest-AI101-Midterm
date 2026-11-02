# AI 101 Midterm App — Live Site Test Log
Live URL: https://risawaj77.github.io/CyberQuest-AI101-Midterm/
Date: November 2, 2026

| Test | Steps | Expected | Actual observed | Result |
|---|---|---|---|---|
| Normal: suspicious message | Enter “URGENT! Enter your password immediately or your account will be suspended.” and select Scan | Detect urgency and credentials | Two warning signs displayed with appropriate caution | PASS — screenshot supplied |
| Repeated use | Scan the above, then use Insert example and Scan again | Updates findings for new content | Example found three signs (urgency, credentials, unfamiliar link) | PASS — screenshot supplied |
| Neutral / no-match edge case | Scan “Meet at the library tomorrow.” | No warning phrases; no assertion of safety | Expanded verification guidance displayed | PASS — screenshot supplied |
| Case feedback | Flag Case 1 as suspicious | Explanation displayed | Correct explanation and disabled answer buttons | PASS — screenshot supplied |
| Reset | Answer cases then click Reset training | Counters return to 0/6 | Student confirmed counters reset | PASS — user report (no screenshot) |
| Eight automated checks | Self Tests → Run 8 tests | 8/8 checks pass | 8/8 checks passed in live-site screenshot | PASS — screenshot supplied |
| Empty / invalid input | Clear textbox and click Scan | Prompt to enter a fictional message | Not yet observed after clicking Scan with an empty box | NOT RUN |
| Keyboard access | Use Tab, Enter/Space on buttons without mouse | All interactive controls accessible | No documented keyboard session | NOT RUN |
| Narrow screen | Open live site on phone or narrow browser viewport, interact with both features | Readable and operable without horizontal scrolling | No documented narrow-screen check | NOT RUN |

## Fix and retest
Problem (Issue #1): The scanner's no-match response did not sufficiently explain what to do when it found no keyword matches.
Fix (merged PR #2): Added advice to check senders through a trusted channel and independently check links, plus a warning that no match does not guarantee safety.
Retest: The student entered “Meet at the library tomorrow.” on the live site. The revised no-match explanation displayed as intended. PASS.
Code diff: https://github.com/Risawaj77/CyberQuest-AI101-Midterm/pull/2/files

**Important:** The course specifically requires five categories of tests: normal, empty/invalid, repeated use, keyboard access, and narrow screen. The last three unverified items above must be tested by the student to claim full compliance; other passing tests do not replace these categories.
