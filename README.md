# territory-analytics

**Sales Operations Analyst (Territory Planning) — UK & Ireland**

This repository documents the analytical methodology, research frameworks and workflow design I have built and deployed in my role managing territory coverage, account alignment and TAM decisions across the FRIS vertical and Ireland for HP UK&I.

---

## What this repository covers

### 1. UK + Ireland Company Filings Research Methodology

A structured framework for researching company group hierarchies using Companies House, the Irish Companies Registration Office (CRO), annual reports and official filings — producing consistent, evidence-cited outputs for territory ownership, employee estimation and procurement control decisions.

The framework produces eight structured outputs:

| Section | What it covers |
|---|---|
| A — Analyst Snapshot | 10-bullet summary including entity confirmation, parent structure, employee counts, procurement model |
| B — Parents & Control | Immediate parent, ultimate parent, controlling shareholders — clearly separated |
| C — Employees | Global / UK / Ireland / Combined with explicit >500 or <500 conclusion |
| D — UK & IE Subsidiaries | Table of key entities verified against CH/CRO profile pages |
| E — Trading Names | Brand-to-legal-entity mapping to prevent CRM duplicates |
| F — Procurement Control | Centralised / decentralised / hybrid with contract-signing entity identified |
| G — Evidence List | All sources used, cited specifically |
| H — Gap Log | Honest record of what could not be confirmed |

All employee figures are labelled [FACT], [DERIVED] or [ESTIMATE] with the methodology shown. Nothing is assumed or hallucinated.

**Sample output:** See [`research-methodology/sample-output-rolls-royce.md`](research-methodology/sample-output-rolls-royce.md)

---

### 2. AI-Assisted Operational Workflow

A structured session brief architecture that encodes domain logic, stakeholder dependencies, case workflow rules and communication standards into a reusable operational context — enabling consistent, high-quality analytical outputs across concurrent cases.

This workflow was developed to address a fragmentation problem: seven tools (Dynamics, HPD, ODS, Reltio, MDM Dashboard, BA Dashboard, QDF) with zero automated handoffs between them, requiring manual verification at every stage.

**What the workflow encodes:**
- MDM case workflow: intake → BA dashboard → approval → implementation → HPD verification
- HPD system logic: winner/loser ST, MDCP alignment, STUA vs ORG move distinction
- MDM freeze calendar: release dates, exception period windows, Market Approver bypass route
- Stakeholder map with named owners at each process step
- Research framework trigger and standards
- Communication standards calibrated by stakeholder

See [`operational-workflow/session-brief-template.md`](operational-workflow/session-brief-template.md)

---

### 3. FRIS Coverage Operating Model

A documented operating model designed to close the gap between Dynamics case approval and HPD implementation — built in response to a broken coverage workflow that had no closed-loop verification, no escalation path and no single source of record.

**Delivered across the FRIS vertical:**
- 300+ territories analysed
- 7,000+ ORGs reviewed
- 100+ optimised patches (50% complexity reduction)
- 1,900+ data correction cases raised

See [`operating-model/`](operating-model/) for the redacted PDF.

---

## Skills demonstrated

- **Prompt architecture** — structured context design for AI-assisted analytical workflows
- **Company filings research** — Companies House, CRO, annual reports, PSC registers
- **Territory and TAM analysis** — UK+Ireland group hierarchy, employee estimation, procurement modelling
- **Process documentation** — operating model design, gap analysis, stakeholder mapping
- **Data governance** — evidence labelling standards, gap logging, source citation
- **Stakeholder communications** — multi-party case management across MDM, BA and sales teams

---

## Tools and sources

Companies House · Companies Registration Office (CRO) · Annual reports and investor pages · LinkedIn (employee estimation only) · Microsoft Dynamics · HPD · SQL · Excel · Python (reportlab, openpyxl)

---

## Contact

Maria Cordova
Sales Operations Analyst (Territory Planning) UKI
[LinkedIn](https://www.linkedin.com/in/mariacordova)
maria.cordova@hp.com
