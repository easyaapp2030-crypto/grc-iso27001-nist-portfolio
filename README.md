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
| **04** | Security Control Selection & Mapping | Risk-to-control matrix, selection methodology, implementation/evidence tracker | Completed |
| **05** | Security Policies & Procedures | Information security policy, access control and incident response procedures, traceability and approval register | Completed |
| **06** | Control Implementation & Evidence Collection | Implementation tracker, evidence register, collection procedure, assessment summary | Completed |
| **07** | Security Control Assessment & Gap Analysis | Assessment methodology, 12-control workbook, gap analysis, remediation register | Completed |
| **08** | POA&M & Remediation Planning | Corrective-action tracker and remediation priorities | Planned |
| **09** | Continuous Monitoring & Metrics | Monitoring strategy, metrics, reporting | Planned |
| **10** | Executive Risk Brief & Portfolio Wrap-Up | Leadership briefing and consolidated project findings | Planned |

*Days 8–10 are planned; all control findings and evidence in this project are simulated.*

## Repository navigation

- **Day 01:** Organization profile, ISMS scope, system boundary, and stakeholder governance.
- **Day 02:** Asset inventory and CUI classification.
- **Day 03:** Risk assessment, risk register, and risk treatment.
- **Day 04:** [`Day-04-Security-Control-Mapping/`](Day-04-Security-Control-Mapping/) — control-selection methodology, mapping matrix, and implementation tracker.

> Folder names for Days 1–3 should match the folders already in this repository; update these navigation entries when their exact names are confirmed.

- **Day 05:** [`Day-05-Security-Policies-and-Procedures/`](Day-05-Security-Policies-and-Procedures/) — policy, procedures, traceability, and approval tracker.

- **Day 06:** [`Day-06-Control-Implementation-and-Evidence/`](Day-06-Control-Implementation-and-Evidence/) — implementation tracker, evidence collection, and assessment summary.
- **Day 07:** [`Day-07-Security-Control-Assessment-and-Gap-Analysis/`](Day-07-Security-Control-Assessment-and-Gap-Analysis/) — assessment methodology, control testing workbook, gap analysis, and remediation findings.

## Day 4: Security Control Selection & Mapping

Day 4 converts Day 3's identified risks into proposed safeguards and evidence expectations.

**Artifacts** (inside `Day-04-Security-Control-Mapping/`):

1. [`README.md`](Day-04-Security-Control-Mapping/README.md) — Day 4 scope, workflow, and limitations.
2. [`control_selection_methodology.md`](Day-04-Security-Control-Mapping/control_selection_methodology.md) — criteria and decision process.
3. [`day4_control_mapping_matrix.csv`](Day-04-Security-Control-Mapping/day4_control_mapping_matrix.csv) — 12 illustrative risk-to-control mappings.
4. [`implementation_tracker.csv`](Day-04-Security-Control-Mapping/implementation_tracker.csv) — owners, status, and planned evidence.

**Important:** Day 4 risk IDs and scenarios must be reconciled with the actual Day 3 register. Control mappings are proposed references, not proof of implementation or equivalence between standards. Implementation status is **Not assessed** until validated.

## Day 5: Security Policies & Procedures

Day 5 translates risk and control selection into governance and operational instructions. Drafts are not approved or tested.

- [`README.md`](Day-05-Security-Policies-and-Procedures/README.md)
- [`Information_Security_Policy.md`](Day-05-Security-Policies-and-Procedures/Information_Security_Policy.md)
- [`Access_Control_Procedure.md`](Day-05-Security-Policies-and-Procedures/Access_Control_Procedure.md)
- [`Incident_Response_Procedure.md`](Day-05-Security-Policies-and-Procedures/Incident_Response_Procedure.md)
- [`Policy_Control_Traceability.csv`](Day-05-Security-Policies-and-Procedures/Policy_Control_Traceability.csv)
- [`Approval_and_Review_Register.csv`](Day-05-Security-Policies-and-Procedures/Approval_and_Review_Register.csv)

## Day 6: Control Implementation & Evidence Collection

Day 6 tracks proposed control implementation and the evidence needed to substantiate security claims. It establishes a repeatable collection process and identifies evidence gaps. All implementation and evidence statuses are illustrative, not verified.

- [Day 6 project folder](Day-06-Control-Implementation-and-Evidence/)
- Control Implementation Tracker
- Evidence Collection Register
- Evidence Collection Procedure
- Control Assessment Summary
- Day 6 README

## Day 7: Security Control Assessment & Gap Analysis

Day 7 applies a documented assessment approach to 12 simulated control tests, identifies gaps, and assigns proposed corrective actions. The exercise demonstrates the distinction between a documented control, available evidence, and independently validated effectiveness.

- [Day 7 project README](Day-07-Security-Control-Assessment-and-Gap-Analysis/README.md)
- [Assessment Methodology](Day-07-Security-Control-Assessment-and-Gap-Analysis/Assessment_Methodology.md)
- [Control Assessment Workbook](Day-07-Security-Control-Assessment-and-Gap-Analysis/Control_Assessment_Workbook.csv)
- [Gap Analysis](Day-07-Security-Control-Assessment-and-Gap-Analysis/Gap_Analysis.md)
- [Findings & Remediation Register](Day-07-Security-Control-Assessment-and-Gap-Analysis/Findings_and_Remediation_Register.csv)

**Assessment disclaimer:** Results, owners, evidence, and remediation recommendations are fictional training examples. No real systems have been assessed, and no certification or compliance determination is claimed.

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
