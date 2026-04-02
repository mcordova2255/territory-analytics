# territory-analytics

**Sales Operations Analyst (Territory Planning) — UK & Ireland**

This repository documents the analytical methodology, research frameworks and workflow design I have built and deployed in my role managing territory coverage, account alignment and TAM decisions across the FRIS vertical and Ireland.

---

## Repository structure

```
territory-analytics/
│
├── README.md
│
├── research-methodology/
│   ├── methodology-overview.md        ← How the framework works and why
│   ├── sample-output-aviva.md         ← Full A–H output: Aviva plc (FRIS vertical)
│
├── operational-workflow/
│   └── session-brief-template.md      ← AI-assisted workflow architecture
│
└── operating-model/
    └── FRIS-Coverage-Operating-Model-Redacted.pdf  ← Process design & business case
```

---

## 1. UK + Ireland Company Filings Research Methodology

A structured framework for researching company group hierarchies using [Companies House](https://find-and-update.company-information.service.gov.uk/), the [Irish Companies Registration Office (CRO)](https://cro.ie/), annual reports, and official filings.

Produces consistent, evidence-cited outputs for territory ownership, employee estimation, and procurement control decisions in a Sales Operations context.

### The eight-section output

| Section | What it covers |
|---|---|
| A — Analyst Snapshot | 10-bullet executive summary: entity confirmation, parent structure, employee counts, procurement model |
| B — Parents & Control | Immediate parent, ultimate parent, controlling shareholders — explicitly separated |
| C — Employees | Global / UK / Ireland / Combined with `[FACT]` `[DERIVED]` `[ESTIMATE]` labelling and explicit >500 or <500 conclusion |
| D — UK & IE Subsidiaries | Verified table of key entities — each CH/CRO profile page opened to confirm status, SIC, and registered office |
| E — Trading Names | Brand-to-legal-entity mapping to prevent CRM duplicates and incorrect ST alignment |
| F — Procurement Control | Centralised / decentralised/hybrid classification with contract-signing entity named |
| G — Evidence List | Every source cited specifically with links |
| H — Gap Log | Honest record of what could not be confirmed and why |

→ **[Read the methodology](research-methodology/methodology-overview.md)**
→ **[See a full output: Aviva plc](research-methodology/sample-output-aviva.md)**

---

## 2. AI-Assisted Operational Workflow

A structured session brief architecture that encodes domain logic, stakeholder dependencies, case workflow rules, and communication standards into a reusable operational context.

Developed to address a specific fragmentation problem: seven tools with zero automated handoffs between them, requiring manual verification at every stage of the case lifecycle.

### What the workflow encodes
- MDM case workflow: intake → BA dashboard → approval → implementation → system verification
- System logic: winner/loser ST, MDCP alignment, user assignment vs ORG move distinction
- MDM freeze calendar: release dates (1 May / 1 November), exception period windows, Market Approver bypass route
- Stakeholder map with named owners at each process step
- Communication standards calibrated by stakeholder type
- Research framework trigger and standards

→ **[See the session brief template](operational-workflow/session-brief-template.md)**

---

## 3. FRIS Coverage Operating Model

A documented operating model designed to close the gap between CRM case approval and system implementation — built in response to a broken coverage workflow with no closed-loop verification, no escalation path, and no single source of record.

### Delivered across the FRIS vertical
| Metric | Result |
|---|---|
| Territories analysed | 300+ |
| ORGs reviewed | 7,000+ |
| Optimised patches | 100+ (50% complexity reduction) |
| Data correction cases raised | 1,900+ |
| Operating model | Designed, documented, and proven |

Client and system-specific data have been removed. The process design, gap analysis, and business case are intact.

→ **[View the operating model PDF](operating-model/FRIS-Coverage-Operating-Model-Redacted.pdf)**

---

## Skills demonstrated

**Research & analysis**
Companies House and CRO filings research · Employee estimation methodology · Procurement model analysis · Group hierarchy mapping · TAM validation

**Process design**
Operating model design · Gap analysis · Escalation framework · Stakeholder mapping · Case workflow documentation

**AI workflow design**
Prompt architecture · Session context engineering · Research agent design · Structured output frameworks

**Sales operations**
Territory planning · Coverage governance · MDM case management · CRM alignment · Quota system integration

**Tools**
Microsoft Dynamics · HPD · SQL · Excel (openpyxl) · Python (reportlab) · Companies House · CRO · GitHub

---

## Also on Kaggle

A synthetic territory coverage dataset demonstrating the TAM validation methodology used across the FRIS vertical portfolio.

→ [View on Kaggle](https://www.kaggle.com/code/mariacordova/territory-coverage-analysis)

---

## Contact

**Maria Cordova**
Sales Operations Analyst (Territory Planning) UKI
[LinkedIn](https://www.linkedin.com/in/maria-gabriella-cordova-986142142/) · [Kaggle](https://www.kaggle.com/mariacordova)
maria.cordova@hp.com
