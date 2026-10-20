# Assumptions, Decisions, and Open Items

| ID | Item | Status | Follow-up |
|---|---|---|---|
| A-01 | SDS is a fictional 100-person U.S. DoD contractor | Scenario assumption | Retain throughout project |
| A-02 | SDS handles simulated unclassified CUI | Scenario assumption | Trace flows on Day 2 |
| A-03 | CUI is limited to managed endpoints and approved services | Design intent, not verified | Validate asset inventory |
| A-04 | Corporate marketing and unrelated HR systems are outside CUI scope | Conditional exclusion | Verify no CUI or security protection role |
| A-05 | CMMC Level 2 is modeled for educational purposes | Assumed baseline | Verify real-world contract clauses in real engagements |
| A-06 | NIST 800-53 is used as supplementary reference | Framework decision | Avoid claims of full federal RMF/ATO applicability |
| A-07 | ISO 27001 is used for ISMS design | Framework decision | Do not claim certification |
| O-01 | Select hypothetical approved cloud services and configurations | Open | Day 2 |
| O-02 | Identify security protection assets and external service providers | Open | Day 2 |
| O-03 | Confirm CUI categories, retention, and transfer methods | Open | Day 2 |
| O-04 | Define hypothetical contract requirements and assessment approach | Open | Day 4 |

## Day 1 decision record

**Decision:** Start with a proposed contractor CUI environment nested inside a broader organizational ISMS.  
**Rationale:** Keeps system scoping distinct from enterprise governance and avoids treating every corporate application as a CUI asset.  
**Risk:** Unmapped shared services may expand the actual CUI assessment scope.  
**Next review:** Day 2.
