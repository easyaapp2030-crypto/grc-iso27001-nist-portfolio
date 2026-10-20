# SDS — Risk Treatment Recommendations

**Purpose:** Turn Day 3's illustrative scenarios into a sequenced, owner-led response plan. Dates are target windows measured from leadership approval, not commitments already made.

## Treatment waves
| Window | Risks | Action | Responsible role | Verification evidence |
|---|---|---|---|---|
| 0–15 days | R-01, R-08 | Review privileged/CUI access; enforce appropriate MFA and remove stale accounts | IAM Lead | MFA/conditional access settings, privileged access review |
| 0–15 days | R-02, R-05 | Inventory external sharing and approved CUI exchange routes; disable unapproved paths | Collaboration Admin + Contracts Lead | Sharing policy export, exception approvals, exchange register |
| 0–30 days | R-03, R-09 | Test isolated/immutable backup restore and ransomware recovery runbook | Infrastructure Lead | Restore-test record, recovery objectives and exceptions |
| 0–30 days | R-04, R-06 | Triage vulnerable endpoints and encryption compliance; apply prioritized remediation | Endpoint Lead | Patch status, encryption coverage and exceptions |
| 15–45 days | R-07, R-10 | Improve alert coverage and harden remote access | SOC Lead + Network Lead | Alert test cases, VPN configuration review |
| 30–60 days | R-11, R-12 | Formalize joiner/mover/leaver and CUI handling training | HR/IT Lead + Security Manager | Access revocation samples, training completion records |

## Risk-by-risk planned treatments
| ID | Preferred response | Primary safeguard | Owner | Target residual (L×I) |
|---|---|---|---|---|
| R-01 | Mitigate | Strong MFA, privileged access controls, sign-in monitoring | IAM Lead | 2×5=10 High |
| R-02 | Mitigate | Restrict external sharing, DLP, approved collaboration paths | Collaboration Admin | 2×5=10 High |
| R-03 | Mitigate | Segmentation, endpoint defense, tested isolated backups | Infrastructure Lead | 2×5=10 High |
| R-04 | Mitigate | Risk-based patching, device health enforcement | Endpoint Lead | 2×4=8 Moderate |
| R-05 | Mitigate | Approved recipient validation and CUI transfer workflow | Contracts/Program Lead | 1×5=5 Moderate |
| R-06 | Mitigate | Full-disk encryption, endpoint inventory, remote wipe | Endpoint Lead | 2×4=8 Moderate |
| R-07 | Mitigate | Centralized audit collection and actionable alerting | SOC Lead | 2×4=8 Moderate |
| R-08 | Mitigate | Periodic access recertification, least privilege | IAM Lead | 2×4=8 Moderate |
| R-09 | Mitigate | Recovery exercises, backup retention and isolation | Infrastructure Lead | 2×4=8 Moderate |
| R-10 | Mitigate | Managed remote access, posture checks, session logging | Network Lead | 2×4=8 Moderate |
| R-11 | Mitigate | Timely offboarding and automated account disablement | HR/IT Lead | 2×4=8 Moderate |
| R-12 | Mitigate | Role-based CUI handling training and secure workflows | Security Manager | 2×4=8 Moderate |

## Acceptance and evidence gates
No risk is marked closed on plan approval alone. Each action requires (1) implemented control, (2) evidence, (3) effectiveness validation, (4) reassessed likelihood/impact, and (5) owner and leadership sign-off where applicable. Target residual scores are *hypothetical planning estimates*. Escalate any unmet contractual CUI safeguard independently of the numeric risk score.

## Control-mapping handoff
Day 4 should map these treatments to the **contractually applicable** NIST SP 800-171/CMMC requirements and supporting NIST CSF 2.0 outcomes. The framework crosswalk is a reference, not proof of implementation.
