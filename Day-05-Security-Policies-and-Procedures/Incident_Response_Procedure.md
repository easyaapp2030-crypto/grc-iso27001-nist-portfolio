# SDS Incident Response Procedure — DRAFT

**Procedure ID:** SDS-SEC-PROC-IR-001  
**Owner:** Incident Response Lead / ISSO  
**Status:** Draft / Not exercised

## Purpose
Provide repeatable actions for suspected or confirmed incidents affecting simulated SDS systems or simulated CUI.

## Roles
Reporter identifies concerns; SOC/IT receives alerts; Incident Response Lead coordinates investigation; ISSO assesses compliance/contract impacts; System Owner authorizes operational changes; Legal/Contracts evaluates external notification duties; Executive Sponsor approves major business decisions.

## Workflow
1. **Report:** Employees and contractors report suspected phishing, malware, unauthorized access, data exposure, or service disruption immediately through the designated channel.
2. **Log and triage:** Record incident ID, discovery time, reporter, affected assets/data, initial indicators, and severity. Distinguish event from confirmed incident.
3. **Escalate:** Notify the response lead and relevant stakeholders according to severity. Engage legal/contracts for potential CUI or reportable incidents.
4. **Preserve evidence:** Protect relevant logs, volatile data when feasible, timestamps, chain of custody, and case notes before destructive actions.
5. **Contain:** Isolate affected accounts/endpoints or restrict network access with owner approval; document operational tradeoffs.
6. **Eradicate and recover:** Remove root cause, restore trusted services, validate controls, and monitor for recurrence.
7. **Communicate:** Coordinate internal updates and external notices through authorized personnel. **Do not assume a universal DoD reporting deadline**; validate applicable contract, DFARS, agency, and legal obligations for each event.
8. **Close and learn:** Document timeline, impact, root cause, decisions, evidence, lessons learned, and corrective actions; update risks and control documentation.

## Evidence
Incident ticket, alert/log exports, investigation notes, chain-of-custody records, containment approvals, restoration tests, notification decisions, lessons-learned report, POA&M actions.

## Exercise and review
Conduct at least an annual tabletop as a proposed internal target; review this procedure after exercises and major incidents.

## Control references (illustrative)
NIST SP 800-53 IR-4, IR-5, IR-6, IR-8; NIST SP 800-171 Rev. 2 3.6.1–3.6.3; CMMC Level 2 related practices.
