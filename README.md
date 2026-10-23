# RuleCrew

**Business rules agents for IBM ODM.** Describe a rule change in plain English. A crew of AI specialists
analyses it, designs it, builds it, tests it on your own engine and reviews it - and nothing is written until a
person approves the exact change.

▶ **[Watch the product tour (7 min)](RuleCrew_tour.mp4)**

[![RuleCrew product tour](RuleCrew_thumbnail.png)](RuleCrew_tour.mp4)

## What you will see
- **A real request, end to end** - "refuse the loan when the amount is more than ten times the borrower's yearly
  income" on a working branch of a loan-validation decision service.
- **The crew at work, live** - orchestrator, business analyst, architect, developer, tester, reviewer, independent
  critic and release manager, several of them working in parallel.
- **A safety net** - the independent critic stopped a condition nobody asked for, and the crew asked a person
  before going on.
- **Your approval** - the exact change, every warning and a Definition of Done: compiled with your ODM build,
  test suites passed, existing decisions replayed before and after, reviewed twice.
- **Before and after**, **every agent traced**, and the audit trail.

## Why a crew
Rule-writing assistants generate new rules from a prompt and leave the checking to you. Changing a *live*
application needs more - the requirements, the existing rules and their dependencies, regression, review and
approval. On a complex rule application, with many projects, rule flows, decision tables and dependencies, each
specialist checks a different risk.

## Works with
| IBM ODM | Status | Verified on IBM's ODM for Developers images |
|---|---|---|
| 9.6 | supported | rule language, rule writing and testing on the engine, the full crew end to end |
| 9.5, 9.0 | supported | rule language, rule writing, draft rulesets run on the engine |
| 8.12, 8.11 | experimental | rule writing; 8.12 rule language and engine runs too (8.11 needs the rules' Java model deployed once) |

- Decision Center, Rule Execution Server (or an embedded engine), or a local Rule Designer workspace folder
- IDE assistants through the Model Context Protocol

## Your data
RuleCrew, its settings, its knowledge and its audit trail stay on your machine; passwords and keys are encrypted
for your Windows user. What leaves it: the requests to the language model **you** choose (your own key, your
company's endpoint, or - for demo data only - free providers), and the calls to your own ODM servers. With real
client rules, free providers are never used. Nothing is sent to us; no telemetry.

## Status
A working prototype, shown on IBM's sample loan application. We would love your feedback - open an issue in this
repository.

---
*IBM, ODM, Decision Center and Rule Execution Server are trademarks of International Business Machines
Corporation. RuleCrew is an independent project, not affiliated with or endorsed by IBM.*
