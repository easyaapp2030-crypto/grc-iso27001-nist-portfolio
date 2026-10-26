# Continuous Monitoring Strategy — SDS (Simulation)

## Objective and scope
Create an ISCM-style feedback loop for the fictional SDS CUI environment. Align monitoring priorities with system boundary, selected controls, POA&M items, and leadership risk tolerance. This document does not assert that telemetry or monitoring tools are deployed.

## Governance
- **System owner:** approves scope, resourcing, and operational changes.
- **ISSO/GRC lead:** maintains metrics, POA&M linkage, evidence quality, and reports.
- **IAM, SOC, endpoint, and vulnerability leads:** supply source data and investigate exceptions.
- **Risk official:** evaluates material residual risk and acceptance requests.

## Monitoring activities
| Activity | Proposed cadence | Output |
|---|---|---|
| POA&M status and high-risk backlog | Weekly | Aging and escalation review |
| Identity, privileged access, and MFA review | Monthly / quarterly by control | Exception log and approvals |
| SIEM ingestion and security alerts | Continuous operations; monthly assurance review | Coverage and incident trend |
| Vulnerability scanning and remediation | Per approved scanning plan; monthly reporting | Findings, SLAs, validation |
| Evidence collection and control health | Monthly | Evidence completeness and stale-evidence log |
| Independent control reassessment | Risk-based / approved schedule | Workpapers, outcomes, POA&M updates |

## Data quality and privacy
Record timestamps, source system, population/denominator, owner, and validation status. Suppress or redact CUI, secrets, account identifiers, and PII before sharing. Do not substitute missing values with zero or present fabricated figures as observed.

## Threshold response
A threshold breach triggers owner investigation, documented action, and escalation as needed; it does not itself establish a control failure without verification. Targets are illustrative until management approves them.

## Reporting
Use `Security_Metrics_Catalog.csv` for metric definitions and `Monitoring_Action_Log.csv` for trigger-to-action traceability. Report changes, uncertainty, outstanding evidence, and leadership decisions monthly.
