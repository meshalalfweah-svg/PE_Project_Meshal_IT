# How to Use the IT Prompt Library

Owner: Meshal Hayaf Alfweah · Version: v1 · Date: 2026_10_15

## What is here

The library contains five drafting templates for replies, summaries, classification, plain-language answers and senior-technician handoffs. It also contains one shared IT Facts block, five responsible-use rules, a test report and recorded applications. It does not connect to any account, ticket or procurement system.

## Run a template

1. Use the index to choose one task. Open its file and read Purpose, Use when and Limits.
2. Before using an approved AI tool, remove real personal information and all secrets locally. For this training project use invented details only and codes such as User-1 or Device-1.
3. Copy the text inside the Template code block. Replace INPUT_TEXT with your masked input. Choose LANGUAGE, TONE and MAX_WORDS from their allowed values. If omitted, use the table’s documented defaults. Keep the complete inline Facts block. The operator must paste the full text, not a file path; no automatic file loading occurs.
4. Keep ROLE, ACTION, RULES, the context and fixed output format intact. Classifier labels always stay in the documented English list. Do not put instructions inside the ticket to override rules.
5. Apply the filled prompt and keep the exact prompt and response. Empty required input should produce a clarification, not invented content. Invalid variables should produce a request for correction.

## Review before sending

The technician scores five checks, 1 for a pass and 0 for a fail: (1) every policy claim matches the current Facts block and reports remain reports; (2) numbers, dates and names are exact; (3) no promise or claim of a completed action; (4) no sensitive data repeated; (5) every question is answered or flagged and the wording is complete and natural. Review CHECK against the sources and count user-facing words, including headings but excluding CHECK. Send nothing until the responsible person accepts all five checks. Remove CHECK before the employee sees the message.

Manager approval remains necessary for a new laptop request. Refer order status to procurement and urgent outages by phone to the duty line. Never invent a phone number or URL.

## Ownership and changes

Meshal Hayaf Alfweah owns the index, guide, five templates, facts, rules and training records. An operational technician owns each final review and a manager owns approval decisions. Only the template owner changes the maintained rules or facts. Increment the version, add a dated change-log entry, archive the older version and repeat A/B/E tests and the fairness check. Keep the training report and actual review record separate from any workplace approval.
