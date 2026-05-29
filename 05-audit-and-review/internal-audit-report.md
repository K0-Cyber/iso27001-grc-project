# Internal Audit Report

**Organisation:** EugTech Solutions Ltd
**Audit:** ISMS Audit 2026-01
**ISO 27001 Clause:** 9.2

**Audit Date:** January 2026
**Auditor:** Kofi Amanquah (Independent from operations)

## Scope

All mandatory ISO 27001:2022 clauses (4–10) and selected Annex A controls.

## Method

* Document review
* Staff interviews
* System configuration inspection
* Log review

## Overall Conclusion

The ISMS demonstrates a solid foundation with good implementation of technical controls, particularly in cloud security and identity management.

Key areas requiring attention are supplier management, knowledge management, and vulnerability scanning programme formalisation.

## Audit Findings

| Ref  | Clause                        | Finding Type        | Description                                                                                                                                                                         | Evidence Reviewed                       | Corrective Action                                                                                                               |
| ---- | ----------------------------- | ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| F-01 | A5.19 Supplier                | Minor Nonconformity | Supplier security questionnaires sent but 3 of 8 suppliers have not returned completed forms. Unsigned suppliers have access to company systems.                                    | Supplier register, email correspondence | Obtain signed questionnaires within 30 days. Suspend system access for non-responsive suppliers after 45 days.                  |
| F-02 | A8.8 Vulnerability Management | Minor Nonconformity | Vulnerability scanning is performed but no formal documented process exists for prioritisation or tracking of remediation. Two medium vulnerabilities from last scan are untracked. | Scan reports, patch records             | Document vulnerability management procedure. Create tracking spreadsheet. Remediate outstanding vulnerabilities within 30 days. |
| F-03 | A6.3 Training                 | Observation         | Security awareness training completion rate is 88%. Six staff have not completed annual training. No escalation process for non-completion.                                         | Training records, HR system             | Establish escalation to line managers for non-completion after 14 days. Achieve 100% by end of Q1.                              |
| F-04 | 9.1 Monitoring                | Observation         | KPIs for ISMS performance have been defined but not formally reviewed at management level since implementation. Management review not yet scheduled.                                | ISMS KPI document, management calendar  | Schedule management review for February 2026. Establish quarterly cadence going forward.                                        |
| F-05 | A5.9 Asset Inventory          | Observation         | Asset register is accurate for primary assets but personal devices used for company email by four contractors are not registered.                                                   | Asset register, contractor access logs  | Add contractor devices to asset register. Update MDM enrolment requirement in contractor agreements.                            |
