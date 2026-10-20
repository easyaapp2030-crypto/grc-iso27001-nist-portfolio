# Proposed ISMS and CUI Environment Scope Statement

**Document status:** Draft for fictional management approval  
**Version:** 0.1  
**Owner:** Fictional ISSM  
**Date:** 2026-10-12

## 1. Purpose

Define the organizational and technical boundaries for the fictional SDS information security management system (ISMS) and identify the narrower contractor CUI environment to be examined in later deliverables.

## 2. Proposed ISMS scope

The ISMS covers governance and oversight of the people, processes, information, and supporting technology used by SDS to deliver unclassified defense engineering support services. It includes executive risk decisions, contracts intake, workforce security, supplier oversight, security operations, and the contractor-managed CUI enclave.

## 3. Proposed CUI environment boundary

**In scope (subject to Day 2 validation):**

- Contractor-managed CUI collaboration and document storage services.
- Authorized managed workstations used to access, process, or transmit simulated CUI.
- Identity, authentication, access control, logging, endpoint protection, backup, and administration services that protect the CUI environment.
- Authorized users, security administrators, documented workflows, and relevant physical office controls.
- External service provider components to the extent they store, process, transmit, or provide security protection for CUI, subject to contract and shared-responsibility review.

**Outside the proposed CUI boundary, but within broader ISMS governance where applicable:**

- General marketing website and public social media accounts.
- Corporate finance and HR applications that neither process CUI nor provide security protection to the CUI environment.
- Personal/unmanaged devices, which are **prohibited** from CUI access in this fictional design.

**Boundary caution:** A service cannot be excluded merely by calling it “corporate IT” if it actually stores, processes, transmits, or protects CUI assets. Day 2 must verify data paths and shared dependencies before exclusions are accepted.

## 4. Interfaces and dependencies

- Fictional contract intake and CUI marking/handling procedures.
- Approved cloud provider and inherited/shared security responsibilities (to be documented; not assumed).
- Contractor identity provider, logging and alerting, managed device configuration, and backup services.
- External supplier and customer exchanges through authorized channels only.

## 5. Framework applicability

- **NIST SP 800-171 / CMMC Level 2:** simulated contractor CUI protection baseline, with real-world applicability determined by contractual/regulatory requirements.
- **NIST SP 800-53:** supplementary control catalog and comparison source; not automatically imposed on this contractor.
- **ISO/IEC 27001:2022:** voluntary ISMS design framework used to structure governance.
- **NIST CSF 2.0:** outcome-based view of risk governance and management.

## 6. Approval and review

Fictional executive sponsor and ISSM must review scope, dependencies, exclusions, and changes in the contract/technical environment. Scope will be revisited after the Day 2 inventory and whenever material business, system, or contract changes occur.

**Approval status:** NOT APPROVED — educational draft only.
