# Session Brief Template — AI-Assisted Operational Workflow

## Overview

This template is a structured session brief designed to be pasted at the start of any AI-assisted working session. It encodes domain logic, stakeholder workflow rules, communication standards and live case context — eliminating the need to re-explain background each session.

This is the architecture behind the AI-assisted workflow documented in this repository. The template itself is shared here as a demonstration of the prompt engineering approach. Client-specific data, system IDs and stakeholder names have been redacted.

---

## What this template encodes

| Section | Purpose |
|---|---|
| Role & context | Who the analyst is, what vertical they own, what's under review |
| MDM freeze calendar | Release dates, exception period windows, Market Approver bypass route |
| Key stakeholders | Named owners at each process step with escalation logic |
| System logic | Core rules governing how the account system works |
| Case workflow | Standard and freeze-exception routes from intake to verification |
| Territory references | Key ST IDs and their roles (winner/loser/retirement target) |
| Writing voice | Communication standards calibrated by stakeholder type |
| Research framework | Trigger and standards for the A-H filings research methodology |
| Standing open items | Live case status updated each session |
| Today's tasks | Session-specific work items |

---

## The Template

```
=== SESSION BRIEF ===

ROLE & CONTEXT
Title: Sales Operations Analyst (Territory Planning) [VERTICAL] [REGION]
Vertical: [PRIMARY VERTICAL + SECONDARY VERTICAL/COUNTRY]
Role formalisation: [STATUS]

MDM FREEZE
Status: [ACTIVE EXCEPTION PERIOD / OPEN]
Cases release: 1 May ([HALF]) — subject to Sales Comp extension
Exception period: Feb–April (2H) | Aug–Oct (1H)
During freeze: [MARKET APPROVER NAME] logs and approves directly — bypasses MDM
Source: MDM Readiness Lead, GTM Data & Insights

KEY STAKEHOLDERS
[MDM CONTACT] — MDM implementation, EMEA
[BA CONTACT] — Country BA, Market Approver (primary)
[BACKUP APPROVER] — Market Approver (backup)
[TECHNICAL CONTACT] — CRM/System technical validation
[SALES MANAGER] — Senior stakeholder, escalation path
[SUPERVISOR] — Line manager, internal advocate
[CONTRACTING MANAGER] — Contracting organisation manager
[DISTRICT MANAGER] — Territory owner, key requestor
[END USER] — Account manager impacted by coverage gaps
[MDM READINESS LEAD] — MDM freeze calendar owner

SYSTEM LOGIC
- Winner/Loser ST — winner retains ORGs, loser merges into generic territory to retire
- MDCP alignment — required for quota tool visibility and guided selling
- User assignment ≠ ORG move — user-level assignment does not move ORG in system
- ST merge → [GENERIC TERRITORY ID] to retire loser ST
- MDCP alignment must be confirmed after every ST change
- Cases close ≠ implementation confirmed — always verify independently in system

CASE WORKFLOW
Normal: Analyst raises CRM case → MDM adds to BA dashboard →
BA/Approver approves → MDM implements → Analyst verifies in system
Freeze exception: Market Approver logs and approves directly
Always verify in system independently — do not rely on case closure notifications

TERRITORY REFERENCES
Generic territory (retirement target): [ST ID]
[KEY ACCOUNT] winner ST: [ST ID]
[KEY ACCOUNT] loser ST (pending retirement): [ST ID]
[Add further key STs as portfolio develops]

WRITING VOICE
Direct, precise, non-repetitive. Data analyst tone — facts, IDs, dates, actions.
Short paragraphs. Never restate thread context.
Tone calibrates to person and context:
- Technical contacts (MDM, system): factual, action-oriented
- Management (sales manager, supervisor): concise, evidence-led
- Senior stakeholders: professional but not stiff
- Warm openers used selectively, not as a default
Tag each stakeholder at their specific action step.
Case descriptions: MOVE/CREATE/RENAME/MERGE/RETIRE + entity ID + territory ID always.

RESEARCH FRAMEWORK
Company research = run A-H framework (see research-methodology/ folder):
A) Analyst Snapshot (10 bullets)
B) Parents & Control
C) Employees (FACT/DERIVED/ESTIMATE, explicit >500 or <500)
D) UK & IE Subsidiaries table (CH/CRO verified)
E) Trading Names to Legal Entities table
F) Procurement model
G) Evidence List
H) Gap Log
Sources: Companies House → annual report → LinkedIn for employees only
Never hallucinate. UK+Ireland scope only.

STANDING OPEN ITEMS (update each session)
- [ACCOUNT]: [CASE REF] — [STATUS] — [NEXT ACTION OWNER]
- [ACCOUNT]: [CASE REF] — [STATUS] — [NEXT ACTION OWNER]
- [REQUEST]: On hold until [DATE] freeze lift
- [PROPOSAL/REVIEW]: Follow up [DATE] if no response

ACTIVE CASES & TRACKER
[PASTE LATEST TRACKER DATA HERE OR UPLOAD EXCEL]

TODAY'S TASKS
1.
2.
3.
===
```

---

## Why this approach works

Most AI-assisted workflows treat each session as independent — requiring the analyst to re-explain context every time. This template solves that by pre-loading:

**Domain logic** — the system rules (user assignment vs ORG move, freeze calendar, winner/loser ST logic) that would take hours to explain are encoded once and applied automatically across all sessions.

**Stakeholder map** — rather than describing each person's role mid-task, the brief encodes who owns each step of the process so email drafts, case descriptions and escalation decisions are calibrated correctly from the first output.

**Research standards** — the A-H framework trigger means any account research request automatically produces a consistent, evidence-cited output without additional instruction.

**Live state** — the standing open items section means the assistant always knows where cases stand without the analyst having to re-summarise a complex case history.

The result is an AI session that starts at full operational speed — producing draft emails, case descriptions, research packs and tracker updates that require minimal editing rather than significant rework.

---

## Related files

- [`../research-methodology/methodology-overview.md`](../research-methodology/methodology-overview.md) — the A-H research framework this template triggers
- [`../research-methodology/sample-output-aviva.md`](../research-methodology/sample-output-aviva.md) — a full A-H output produced using this workflow
- [`../operating-model/FRIS-Coverage-Operating-Model-Redacted.pdf`](../operating-model/FRIS-Coverage-Operating-Model-Redacted.pdf) — the operating model this workflow supports
