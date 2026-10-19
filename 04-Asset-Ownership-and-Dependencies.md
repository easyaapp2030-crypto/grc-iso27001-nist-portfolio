# Asset Ownership and Dependencies

## Responsibility model (fictional)

| Role | Primary responsibility | Key assets |
|---|---|---|
| Program Manager | Determine program information handling requirements and approve business access | CUI workspace and repository |
| IT Director | Own infrastructure operations, recovery readiness, and service dependencies | Identity, backups, endpoints |
| Security Manager | Coordinate security requirements, assessments, monitoring, and exceptions | SIEM and cross-cutting controls |
| Identity Administrator | Provision access and administer MFA / RBAC under approval | Identity service |
| Collaboration Administrator | Configure approved workspaces and enforce sharing rules | Collaboration platform |
| Vendor Manager | Review supplier access and service dependencies | Third-party support interfaces |

## Critical dependencies
- **Identity:** A compromise or outage may affect all in-scope access paths.
- **Endpoints:** Managed devices are a prerequisite for secure user access.
- **Cloud service approval:** Technical capabilities alone do not establish suitability for CUI; authorization and contractual constraints must be confirmed.
- **Logging:** Audit collection depends on integrations and retention configuration.
- **Backups:** Recoverability depends on protected copies, keys, and tested restore procedures.

## Open decisions for Day 3
- Validate whether the assumed cloud services are approved for the specific CUI workload.
- Confirm data owners, inventory accuracy, and required CUI categories.
- Define acceptable recovery objectives, audit retention, and third-party restrictions.
- Assess risks from excessive access, misconfiguration, data transfer, and backup failure.
