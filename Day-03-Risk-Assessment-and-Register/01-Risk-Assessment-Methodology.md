# SDS Risk Assessment Methodology — v1.0

**Assessment date:** 2026-10-19 (illustrative)  
**Prepared for:** Fictional SDS security governance team  
**Approach:** Qualitative, scenario-based risk assessment informed by NIST SP 800-30 Rev. 1.

## 1. Scope and limitations
In scope: simulated CUI stored, processed or transmitted by SDS-managed endpoints, identity platform, collaboration and CUI repositories, remote access, backups, security monitoring, and approved third-party exchange points. Exclude public marketing systems unless they create an access path into this environment. Day 1 boundary and Day 2 asset/CUI flow take precedence over this working description.

No interviews, vulnerability scans, configuration reviews or control tests were conducted. All likelihood, impact and control-gap judgments are **hypotheses for portfolio demonstration**. Validate against inventory, data-flow, incidents, contract requirements and actual evidence before use.

## 2. Scenario formulation
Each risk states a **threat event + exploitable condition + affected asset/process + consequence**. Record the risk owner, existing controls (assumed/unknown), proposed response, planned action owner, review date and acceptance authority.

## 3. Likelihood scale (L)
| Value | Rating | Interpretation over next 12 months |
|---|---|---|
| 1 | Rare | Exceptional scenario; strong barriers assumed |
| 2 | Unlikely | Possible but requires unusual conditions |
| 3 | Possible | Credible scenario given normal exposure |
| 4 | Likely | Frequent threat and meaningful exposure assumed |
| 5 | Almost certain | Recurring exposure with few barriers assumed |

Ratings are ordinal judgments, **not calibrated probabilities**.

## 4. Impact scale (I)
Use the **highest reasonably credible** impact among CUI confidentiality, integrity, availability, contractual obligations, and business operations.

| Value | Rating | Illustrative effect |
|---|---|---|
| 1 | Insignificant | Minor local disruption, no CUI compromise |
| 2 | Minor | Limited reversible operational effect |
| 3 | Moderate | Material remediation, limited sensitive-data exposure or interruption |
| 4 | Major | Significant CUI or contractual impact; extended disruption |
| 5 | Severe | Broad CUI compromise, mission-critical interruption or severe contractual impact |

## 5. Score, band and treatment
**Inherent score = L × I**, before proposed additional controls. Score is a **prioritization heuristic**; ordinal multiplication does not imply monetary precision.

| Score | Band | Expected action |
|---|---|---|
| 1–4 | Low | Monitor and document |
| 5–9 | Moderate | Owner plans proportionate response |
| 10–16 | High | Prioritize treatment and management review |
| 17–25 | Critical | Prompt leadership escalation and time-bound plan |

Tie-breakers: CUI consequence, external exposure, dependency concentration, and feasibility of near-term containment. High impact with low likelihood still warrants explicit review.

## 6. Residual risk and acceptance
The **target residual** score in the register is a *forecast conditional on successful control implementation*, not a current measured score. Record actual residual risk only after evidence-based validation. No score is automatically accepted; SDS leadership assigns risk acceptance authority, with CUI contractual requirements treated as obligations rather than waivable risks.

## 7. Risk response choices
Mitigate, avoid, transfer/share, or accept (only by designated authority). Transfer does not transfer legal or contractual responsibility for protecting CUI.

## 8. Ownership, cadence, and evidence
Security Manager coordinates quarterly reassessment and event-driven review after incidents, significant system changes, new CUI flows or contract changes. Asset/process owners own individual risks; technical leads own implementation; leadership approves risk tolerance and documented exceptions. Evidence may include identity settings, MFA enrollment, access reviews, patch reports, immutable-backup tests, logs, vendor agreements and approved CUI flow diagrams.

## 9. References and revision caveat
- NIST SP 800-30 Rev. 1, *Guide for Conducting Risk Assessments*.
- NIST SP 800-171 (contractually applicable revision must be confirmed; Rev. 3 exists).
- NIST CSF 2.0, Govern/Identify/Protect/Detect/Respond/Recover outcomes.
- CMMC Level 2 requirements, as applicable to SDS's hypothetical contract.

This methodology is educational and is not an official DoD risk determination.
