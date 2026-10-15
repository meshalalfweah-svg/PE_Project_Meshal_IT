# IT Prompt Library Index

Owner: Meshal Hayaf Alfweah · Version: v1 · Date: 2026_10_15

Scenario: Path B, B2 - Internal IT Help Desk for Employees.

## Templates

| Template | Task | Variables | Version | Status |
|---|---|---|---|---|
| [IT-Reply-Ticket-v1_2026_10_15](templates/IT-Reply-Ticket-v1_2026_10_15.md) | 1: Reply to a support ticket | INPUT_TEXT, LANGUAGE, TONE, MAX_WORDS, FACTS | v1 | Needs work - 5/5, 6/6, 4/5; screenshot and native review pending |
| [IT-Summarize-Thread-v1_2026_10_15](templates/IT-Summarize-Thread-v1_2026_10_15.md) | 2: Summarize a ticket thread | INPUT_TEXT, LANGUAGE, TONE, MAX_WORDS, FACTS | v1 | Needs work - 5/5, 6/6, 4/5; screenshot and native review pending |
| [IT-Classify-Ticket-v1_2026_10_15](templates/IT-Classify-Ticket-v1_2026_10_15.md) | 3: Classify a ticket | INPUT_TEXT, LANGUAGE, TONE, MAX_WORDS, FACTS, CATEGORIES | v1 | Needs work - 5/5, 6/6, 4/5; screenshot and native review pending |
| [IT-Simplify-Answer-v1_2026_10_15](templates/IT-Simplify-Answer-v1_2026_10_15.md) | 4: Explain an answer simply | INPUT_TEXT, LANGUAGE, TONE, MAX_WORDS, FACTS | v1 | Needs work - 5/5, 6/6, 4/5; screenshot and native review pending |
| [IT-Draft-Handoff-v1_2026_10_15](templates/IT-Draft-Handoff-v1_2026_10_15.md) | 10: Draft a senior technician handoff | INPUT_TEXT, LANGUAGE, TONE, MAX_WORDS, FACTS | v1 | Needs work - 5/5, 6/6, 4/5; screenshot and native review pending |

## Shared files

- [IT-Facts v1](blocks/IT-Facts-v1_2026_10_15.md): the seven authoritative invented service facts.
- [IT-Rules v1](rules/IT-Rules-v1_2026_10_15.md): data, verification, fairness, tool policy and human decisions.
- [Test Results Report](Test_Results_Report.pdf): summary plus one page per template.
- [Run records](evidence/runs/): complete A/B/E prompts, outputs and CHECK notes.
- [Evidence provenance](evidence/PROVENANCE.md): how the visual records were made.
- [Fairness comparison](evidence/Fairness_Check.md): equivalent formal and informal questions.

## LANGUAGE - same five values in every template

| Value | Meaning |
|---|---|
| Arabic | Arabic only |
| English | English only |
| Automated (default) | Main language of the input; English if the input is empty |
| Bilingual | Separate Arabic version followed by English |
| Mixed | One coherent response combining Arabic and English |

The recorded task tests use English, as requested for the project. The five modes are supported by prompt rules; no unrecorded language-mode tests are claimed.

## Change log

v1 · 2026_10_15 · Created five IT templates, copied the guided facts, adapted the Day 4 rules and recorded the fifteen in-session applications. No older released version exists in _archive.
