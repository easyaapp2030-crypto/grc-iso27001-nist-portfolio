# Building a GRC Program for a DoD Contractor

### 10-Day Hands-On Cybersecurity Governance, Risk & Compliance Portfolio

**Project:** Sentinel Defense Solutions (SDS)  
**Scenario:** Fictional, 100-person U.S. Department of Defense contractor handling **simulated** Controlled Unclassified Information (CUI)  
**Focus:** Risk Management Framework (RMF), GRC, NIST, CMMC, ISO/IEC 27001, cloud security, and identity & access management (IAM)

## Project overview

This portfolio documents a practical, ten-day exercise in designing a cybersecurity governance, risk, and compliance program for a fictional DoD contractor. Each day produces artifacts that a security analyst, ISSO, GRC practitioner, or security leader might use to support risk-informed decisions and mission assurance.

The objective is to demonstrate a **traceable workflow**: establish the environment and system boundary, identify assets and CUI, assess risks, select controls, plan evidence, and communicate findings to stakeholders.

> **Simulation notice:** SDS, its systems, risks, and records are fictional. This repository does not contain real CUI, demonstrate an assessed control implementation, or claim CMMC certification or regulatory compliance.

## Frameworks and references

| Framework | Role in this project |
| --- | --- |
| **NIST SP 800-30** | Risk assessment methodology and risk analysis |
| **NIST SP 800-53 Rev. 5** | Security and privacy control catalog; RMF-aligned control references |
| **NIST SP 800-171** | Protecting CUI in nonfederal systems; applicability must be checked against contracts |
| **CMMC Level 2** | DoD contractor cybersecurity assessment context |
| **ISO/IEC 27001:2022** | Information security management system (ISMS) structure and Annex A references |
| **NIST CSF 2.0** | Governance and cybersecurity outcome organization |

**Version note:** Day 4 uses NIST SP 800-171 **Rev. 2** identifiers for illustrative CMMC Level 2 cross-references. Rev. 3 has different numbering; do not assume one-to-one equivalence or current contractual applicability without verification.

## 10-day project roadmap

| Day | Topic | Deliverable | Progress |
| --- | --- | --- | --- |
| **01** | Organization & GRC Program Foundation | Organization profile, ISMS scope, system boundary, RACI, assumptions | Completed |
| **02** | Asset Inventory & CUI Classification | Asset inventory, CUI identification and data-flow context | Completed |
| **03** | Risk Assessment & Risk Register | 5×5 risk methodology, 12-scenario register, prioritization and treatment | Completed |
| **04** | Security Control Selection & Mapping | Risk-to-control matrix, selection methodology, implementation/evidence tracker | Prepared for upload |
| **05** | Security Policies & Procedures | Draft policy and procedure artifacts | Planned |
| **06** | Control Implementation & Evidence | Evidence collection and implementation tracking | Planned |
| **07** | Security Assessment & Gap Analysis | Control assessment and gap register | Planned |
| **08** | POA&M & Remediation Planning | Corrective-action tracker and remediation priorities | Planned |
| **09** | Continuous Monitoring & Metrics | Monitoring strategy, metrics, reporting | Planned |
| **10** | Executive Risk Brief & Portfolio Wrap-Up | Leadership briefing and consolidated project findings | Planned |

*Days 5–10 are a proposed roadmap and may be refined as the project develops.*

## Repository navigation

- **Day 01:** Organization profile, ISMS scope, system boundary, and stakeholder governance.
- **Day 02:** Asset inventory and CUI classification.
- **Day 03:** Risk assessment, risk register, and risk treatment.
- **Day 04:** [`day-04-security-control-mapping/`](day-04-security-control-mapping/) — control-selection methodology, mapping matrix, and implementation tracker.

> Folder names for Days 1–3 should match the folders already in this repository; update these navigation entries when their exact names are confirmed.

## Day 4: Security Control Selection & Mapping

Day 4 converts Day 3's identified risks into proposed safeguards and evidence expectations.

**Artifacts** (inside `day-04-security-control-mapping/`):

1. [`README.md`](day-04-security-control-mapping/README.md) — Day 4 scope, workflow, and limitations.
2. [`control_selection_methodology.md`](day-04-security-control-mapping/control_selection_methodology.md) — criteria and decision process.
3. [`day4_control_mapping_matrix.csv`](day-04-security-control-mapping/day4_control_mapping_matrix.csv) — 12 illustrative risk-to-control mappings.
4. [`implementation_tracker.csv`](day-04-security-control-mapping/implementation_tracker.csv) — owners, status, and planned evidence.

**Important:** Day 4 risk IDs and scenarios must be reconciled with the actual Day 3 register. Control mappings are proposed references, not proof of implementation or equivalence between standards. Implementation status is **Not assessed** until validated.

## Practical GRC workflow

`Business & system context → Asset/CUI inventory → Risk assessment → Control selection → Evidence → Assessment → Remediation → Continuous monitoring → Leadership reporting`

## Skills demonstrated

- Risk-based security governance and stakeholder communication
- DoD contractor CUI scoping and compliance awareness
- NIST/RMF-aligned security control selection
- Cross-framework mapping and traceability
- Risk ownership, evidence planning, and remediation tracking
- Executive-ready cybersecurity risk communication

## About the author

**Abe Fakoya, MSc**  
Cybersecurity Professional  
**People | Process | Technology | Compliance | Mission Assurance**

[LinkedIn](https://www.linkedin.com/in/abe-fakoya-msc-0657bb23a/)

---

*Educational portfolio project. No actual DoD systems, classified information, or CUI are represented.*
