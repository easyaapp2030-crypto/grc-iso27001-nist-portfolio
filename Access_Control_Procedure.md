# SDS Access Control Procedure — DRAFT

**Procedure ID:** SDS-SEC-PROC-AC-001  
**Owner:** IAM Administrator / ISSO  
**Status:** Draft / Not implemented or tested

## Trigger and prerequisites
Use for new access, role changes, privileged access, emergency access, and separation. Require an identified requester, business purpose, target system, classification/CUI scope, and accountable manager.

## Workflow
1. **Request:** Manager submits a ticket with named user, requested role, system, business need, and required duration.
2. **Authorize:** System/data owner approves; ISSO reviews elevated privileges and sensitive CUI access; segregation-of-duties conflicts are resolved.
3. **Provision:** IAM administrator creates or changes a unique identity, applies least privilege and required MFA, and logs changes.
4. **Verify:** Requester and owner confirm correct access; record ticket ID, role, approval, and timestamp.
5. **Review:** Owners attest access quarterly for privileged/CUI roles and at least semiannually for other roles (illustrative internal targets; validate against requirements).
6. **Change:** Reassess access upon transfer, assignment change, or contract expiration; remove unnecessary entitlements.
7. **Terminate:** Disable access promptly upon verified separation notification; revoke sessions, credentials, keys, tokens, and physical access as applicable.
8. **Emergency access:** Time-bound break-glass approval, enhanced logging, and post-use review within one business day (proposed target).

## Evidence
Access request/approval tickets; identity and role exports; MFA configuration; provisioning logs; recertification attestations; separation records; privileged-access reviews; exception approvals.

## Escalation
Unauthorized access, orphaned accounts, or suspected compromise triggers the Incident Response Procedure. Delayed removal is documented as a risk or corrective action.

## Control references (illustrative)
NIST SP 800-53 AC-2, AC-3, AC-6, IA-2; NIST SP 800-171 Rev. 2 3.1.1, 3.1.2, 3.1.5, 3.5.3; CMMC Level 2 related practices. Validate before use.
