# Task 3: The Knowledge Analyst (RAG Concepts)

## Tool Used: Claude AI / Claude Projects

## Scenario
A law firm has 500-page contracts that take hours to read.
Built an AI tool that instantly summarizes key clauses and 
answers specific questions without hallucinating.

## What is RAG?
RAG = Retrieval-Augmented Generation
The AI does NOT answer from memory — it only reads YOUR 
document and finds answers from there. This prevents 
making up fake facts (hallucination).

## Document Used
GlobalTech Services Agreement v3.2 — 500 pages

## RAG Q&A System (with Citations)

### Q1: What is the liability cap for data breaches?
Answer: $2,000,000 USD per incident, maximum $5,000,000 
per year. Does not apply to gross negligence.
Citation: Section 14.3 Page 187, Section 14.7 Page 191

### Q2: When does the contract renew and how to cancel?
Answer: Auto-renews March 31, 2026. Must send written 
notice 90 days before renewal via registered mail.
Citation: Section 3.2 Page 22, Schedule A Page 498

### Q3: Can we share client data with third parties?
Answer: No. Strictly prohibited without written consent.
Only approved sub-processors in Annex 3 are allowed.
Citation: Section 9.1 Page 104, Annex 3 Page 467

### Q4: What are the payment terms?
Answer: Net 30 days. Late payment = 1.5% interest per month.
Disputes must be raised within 15 business days.
Citation: Section 6.4 Page 71, Section 6.8 Page 74

## Risk Dashboard (Auto-Extracted)

| Risk | Level | Location |
| Unlimited IP ownership transfer | HIGH | Section 17.2, Page 214 |
| One-sided SLA penalties | HIGH | Section 11.5, Page 143 |
| Unfavourable jurisdiction (Delaware) | MEDIUM | Section 22.1, Page 301 |
| 90-day cancellation window too short | MEDIUM | Section 3.2, Page 22 |
| Sub-processor list outdated | LOW | Annex 3, Page 467 |

## Key Dates Extracted

| Date | Event | Source |
| April 1, 2024 | Contract start | Section 2
