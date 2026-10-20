# SDS — Day 3 Risk Assessment Report

**Date:** 2026-10-19 | **Classification:** Fictional training scenario — no real CUI  
**Assessment status:** Desktop scenario analysis; unverified assumptions.

## Executive summary
Twelve hypothetical risks were evaluated for SDS's simulated CUI processing environment using the documented 5×5 methodology. **Three risks score Critical (17–25)** and **nine score High (10–16)** on an inherent basis. These are modeled priorities, not findings from testing.

## Scope and method
The working environment includes endpoints, cloud CUI collaboration/repository services, identity and remote access, backups, logging, and third-party exchange. See [methodology](01-Risk-Assessment-Methodology.md) and [register](02-Risk-Register.csv). Day 1 boundary and Day 2 asset inventory must be reconciled before risk statements are operationalized.

## Highest-priority scenarios
| Risk | Scenario | L×I | Score | Proposed lead |
|---|---|---|---|---|
| R-01 | Compromised identity accesses CUI | 4×5 | 20 Critical | IAM Lead |
| R-02 | Misconfigured external sharing exposes CUI | 4×5 | 20 Critical | Collaboration Admin |
| R-03 | Ransomware disrupts CUI systems and recovery | 4×5 | 20 Critical | Infrastructure Lead |
| R-04 | Unpatched endpoint provides attacker foothold | 4×4 | 16 High | Endpoint Lead |
| R-05 | Third-party exchange sends CUI to unauthorized destination | 3×5 | 15 High | Contracts/Program Lead |

## Distribution and interpretation
- **Critical:** R-01, R-02, R-03 (3).
- **High:** R-04 through R-12 (9).
- **Moderate/Low:** none under the chosen illustrative assumptions.

This distribution was intentionally designed to support treatment prioritization; it is not a statistical estimate of SDS's true risk posture.

## Material dependencies
Identity access, cloud sharing settings, endpoint hardening, verified recovery capability, vendor oversight, and log visibility interact. A single failure may enable multiple scenarios; owners should avoid double-counting risk reduction across control plans.

## Immediate recommendations (0–30 days)
1. Validate Day 2 CUI paths and current control implementation before asserting gaps.
2. Require phishing-resistant MFA where feasible for privileged and CUI-relevant access; review conditional access and legacy authentication.
3. Review external sharing permissions, default link types and guest access for CUI repositories.
4. Verify backup immutability/isolation and conduct a documented restore test.
5. Triage externally exposed or high-severity vulnerabilities on CUI-connected endpoints.

## Leadership decisions
Appoint risk acceptance authority; approve owners and treatment deadlines; determine acceptable exposure and budget; confirm contractual CUI/CMMC requirements and applicable NIST SP 800-171 revision. Any decision to accept risk does not remove contractual requirements.

## Limitations and next step
No technical validation, threat intelligence tailoring, actual loss data, interviews or audit evidence were obtained. Target residual scores are forecasts. **Day 4** will map selected safeguards to applicable controls and define evidence requests.
