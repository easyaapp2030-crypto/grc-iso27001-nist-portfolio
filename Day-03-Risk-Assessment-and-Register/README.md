
# Day 3 — Risk Assessment & Risk Register

**GRC Portfolio Series | Day 3 of 10**

**Organization:** Sentinel Defense Solutions (SDS)  
**Industry:** Defense Contracting  
**Environment:** Simulated Controlled Unclassified Information (CUI)  
**Assessment Type:** Qualitative Cybersecurity Risk Assessment

## 1. Project Overview

Sentinel Defense Solutions (SDS) is a fictional 100-employee defense contractor supporting U.S. Department of Defense programs.

Following the organizational scoping exercise in Day 1 and asset inventory and CUI classification in Day 2, this stage evaluates cybersecurity risks that could affect the confidentiality, integrity, and availability of SDS information systems.

The objective is to identify credible threats, evaluate their potential business impact, prioritize risks, and recommend appropriate treatment strategies.

## 2. Assessment Objectives

- Identify threats and vulnerabilities affecting in-scope systems.
- Evaluate risks associated with storing, processing, and transmitting simulated CUI.
- Apply a consistent likelihood-and-impact scoring methodology.
- Assign accountability for identified risks.
- Recommend risk treatment activities.
- Establish a baseline for subsequent security control mapping and gap assessment.

## 3. Risk Assessment Methodology

The assessment uses a qualitative **5 × 5 risk matrix**, informed by the principles of NIST SP 800-30.

Each risk receives two ratings:

**Likelihood (1–5):** The estimated probability or frequency of a risk scenario occurring.

**Impact (1–5):** The estimated severity of consequences if the scenario occurs.

Risk scores are calculated as:

**Risk Score = Likelihood × Impact**

| Score | Risk Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–14 | High |
| 15–25 | Critical |

These thresholds are illustrative project assumptions, not mandatory NIST scoring thresholds.

## 4. Day 3 Deliverables

| Document | Description |
|---|---|
| `01-Risk-Assessment-Methodology.md` | Defines assessment criteria, scoring methodology, and risk evaluation approach |
| `02-Risk-Register.csv` | Records identified risks, ratings, assigned owners, and proposed treatment activities |
| `03-Risk-Assessment-Report.md` | Summarizes the simulated assessment findings and priority risks |
| `04-Risk-Treatment-Recommendations.md` | Documents proposed risk responses and mitigation priorities |

## 5. Key Risk Areas

The assessment considers security scenarios involving:

- Compromised identities and unauthorized access.
- Accidental or unauthorized CUI disclosure.
- Ransomware and business interruption.
- Unpatched systems and endpoint vulnerabilities.
- Cloud configuration and information-sharing weaknesses.
- Third-party and supplier security dependencies.
- Backup, recovery, and incident response limitations.

The risk register contains the individual scenarios and their assigned scores.

## 6. Framework Alignment

**NIST SP 800-30:** Provides guidance for conducting information security risk assessments.

**NIST SP 800-171:** Provides relevant security requirements for protecting CUI in applicable nonfederal systems.

**CMMC Level 2:** Provides a defense contracting assessment context where contractually applicable.

**NIST CSF 2.0:** Supports identifying, assessing, prioritizing, and responding to cybersecurity risks.

**ISO/IEC 27001:** Supports risk assessment and risk treatment within an Information Security
