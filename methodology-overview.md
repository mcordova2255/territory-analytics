# UK + Ireland Company Filings Research Methodology

## Overview

This document describes the structured research framework I developed for territory planning and TAM (Total Addressable Market) decisions across the FRIS vertical and Ireland for HP UK&I.

The problem this solves: account research for territory coverage decisions requires consistent, auditable outputs that distinguish between legal entity structure, employee footprint and procurement control. Generic web searches produce inconsistent results that cannot be relied upon for formal case submissions. This framework standardises the research process using primary official sources.

---

## The Problem It Solves

When managing territory coverage across 300+ accounts, I needed to answer three questions consistently for every account:

1. **Who is the correct legal entity** to align in the CRM — the parent holding company, the trading subsidiary, or both?
2. **Where are the employees** — specifically UK and Ireland headcount to determine TAM and whether an account qualifies as >500 employees for tier classification?
3. **Who controls procurement** — which entity signs the contracts that matter for HP?

Without a structured approach, answers to these questions varied between analysts, leading to duplicate STs, misaligned ORGs and incorrect TAM estimates.

---

## The Framework — Eight Sections

The framework produces eight structured outputs for every account researched:

### A — Analyst Snapshot
A 10-bullet executive summary covering entity confirmation, parent structure, employee counts with labelling, and procurement model in a single phrase. Designed to be readable without opening the full pack.

### B — Parents & Control
Separate treatment of:
- Immediate parent undertaking (legal, from filings)
- Ultimate parent undertaking (top legal parent)
- Controlling shareholders (shareholder control — explicitly distinguished from operating control)

This distinction matters because a PE firm owning 80% of a group is shareholder control, not an operating parent — and the ST/ORG alignment decision should follow the operating structure, not the ownership chain.

### C — Employees
Three-level analysis: Global → UK → Ireland → Combined, with an explicit conclusion: **"UK+IE employees clearly >500"** or **"<500"**.

All figures are labelled:
- **[FACT]** — directly disclosed in a filing or official document
- **[DERIVED]** — calculated from disclosed data (e.g. applying a % split to a global figure), with the calculation shown
- **[ESTIMATE]** — inferred from indirect signals (e.g. site counts, LinkedIn ranges), with the method shown

No figure is ever presented without its label and evidence.

### D — UK & IE Subsidiaries Table
A structured table of 8–12 entities that drive UK/Ireland employment and procurement. For each entity, the Companies House or CRO profile page is opened to confirm:
- Status (Active / Dissolved / Dormant)
- SIC code
- Registered office

This prevents errors from relying on outdated or aggregated data.

### E — Trading Names → Legal Entities
Maps customer-facing brands to real legal entities. This is critical for preventing CRM duplicates where a brand name has been given its own ST when contracts actually sit with a different legal entity.

Example: "Rolls-Royce Motor Cars" is owned by BMW, not Rolls-Royce Holdings plc — an account aligned to the brand rather than the correct legal entity would create a misaligned ST.

### F — Procurement Control
Classifies the account as centralised, decentralised or hybrid — and names the specific UK/IE legal entity most likely to sign major contracts. This drives ST design: a centralised procurement model supports a single ST; a decentralised model may require multiple.

### G — Evidence List
Every source used is listed specifically — not just "Companies House" but "Companies House overview page — [entity name] ([number])". This makes the research auditable and reproducible.

### H — Gap Log
An honest record of what could not be confirmed — PDFs that wouldn't open, employee figures that weren't disclosed, entities that couldn't be verified. This prevents false confidence in incomplete data.

---

## Source Hierarchy

Sources are used in this order:

1. **Companies House overview/profile pages** — for UK entity status, SIC, registered office, incorporation date
2. **Companies House filings** (accounts, confirmation statements, PSC) — for parent structure, employee notes, subsidiary lists
3. **Company annual report / investor pages** — for global employees, group structure, procurement model
4. **LinkedIn / business directories** — for employee estimates only, when no filing data is available
5. **CRO (Irish Companies Registration Office)** — for Ireland entities, same hierarchy as above

If a source is inaccessible (e.g. a PDF that won't open), the gap is logged and the research proceeds with what is available. The framework never stalls on an inaccessible source.

---

## Sample Output

A full A–H research pack for **Rolls-Royce Holdings plc** is available at [`sample-output-rolls-royce.md`](sample-output-rolls-royce.md).

This demonstrates the framework applied to a publicly known UK group with a complex subsidiary structure, multiple trading brands and a UK-heavy employee footprint.

---

## Why This Matters for Territory Decisions

Every CAS (case) submitted to the MDM team for territory alignment requires a business justification. The output of this framework becomes that justification — it provides:

- The correct legal entity name and Companies House number
- Evidence of UK/Ireland employee footprint (>500 or <500 determines tier classification)
- Parent structure to confirm winner/loser ST logic in consolidations
- Procurement model to determine whether a single ST or multiple STs are appropriate

Consistent, sourced research reduces the risk of cases being rejected, misimplemented or requiring re-submission.

---

## Tools Used

- Companies House — find-and-update.company-information.service.gov.uk
- Companies Registration Office Ireland — cro.ie
- Company annual reports and investor relations pages
- LinkedIn (employee estimation only)
- AI-assisted research workflow (see [`../operational-workflow/`](../operational-workflow/))
