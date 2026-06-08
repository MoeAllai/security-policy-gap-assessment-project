# NIST CSF Mapping

## Purpose

This document maps identified security policy gaps to NIST Cybersecurity Framework concepts.

The goal is to show how policy weaknesses relate to governance, identity and access management, incident response, vendor risk, data protection, and audit readiness.

---

## NIST CSF Mapping Table

| Gap ID | Policy Area | Gap Summary | NIST CSF Function | NIST CSF Category | Why It Matters |
|---|---|---|---|---|---|
| GAP-01 | Policy Governance | Some policies do not clearly identify a policy owner. | Govern | Organizational Context / Roles and Responsibilities | Policies need owners to ensure accountability, review, enforcement, and updates. |
| GAP-02 | Policy Governance | Several policies do not include documented annual review dates. | Govern | Policy / Oversight | Regular review helps ensure policies stay current with business, security, and compliance needs. |
| GAP-03 | Access Control | Quarterly access reviews are not clearly required. | Protect | Identity Management, Authentication, and Access Control | Access reviews help confirm users retain only appropriate access. |
| GAP-04 | Privileged Access | Privileged access requirements are not clearly defined. | Protect | Identity Management, Authentication, and Access Control | Admin access creates higher risk and should require approval, justification, and review. |
| GAP-05 | Password and MFA | MFA exception handling is unclear. | Protect | Identity Management, Authentication, and Access Control | MFA exceptions can weaken authentication if not approved, tracked, and reviewed. |
| GAP-06 | Incident Response | Customer notification expectations are not clearly defined. | Respond | Incident Management / Communications | Incident notification expectations help ensure timely communication during security events. |
| GAP-07 | Vendor Risk Management | High-risk vendor review requirements are incomplete. | Govern / Identify | Supply Chain Risk Management | Vendors may introduce security, privacy, operational, and compliance risks. |
| GAP-08 | Data Classification | Restricted data handling requirements are not detailed enough. | Protect | Data Security | Sensitive data requires clear handling, storage, transmission, access, and retention rules. |
| GAP-09 | Business Continuity | Annual BCP/DR testing is not clearly required. | Recover | Recovery Planning | Recovery testing helps validate the company can continue or restore operations after disruption. |
| GAP-10 | Change Management | Emergency change approval and post-review requirements are incomplete. | Protect / Detect | Platform Security / Continuous Monitoring | Emergency changes can introduce risk if not documented, approved, and reviewed. |
| GAP-11 | Evidence Retention | Evidence naming and storage standards are not standardized. | Govern | Oversight / Audit Readiness | Audit evidence must be complete, organized, dated, and easy to validate. |
| GAP-12 | Acceptable Use | Enforcement responsibilities are not clearly assigned. | Protect | Awareness and Training / Data Security | Clear responsibilities help ensure policy violations are handled consistently. |

---

## NIST CSF Function Summary

| NIST CSF Function | Related Gaps | Summary |
|---|---|---|
| Govern | GAP-01, GAP-02, GAP-07, GAP-11 | Governance gaps relate to ownership, oversight, vendor risk, and evidence management. |
| Identify | GAP-07 | Vendor risk management helps identify third-party security and compliance exposure. |
| Protect | GAP-03, GAP-04, GAP-05, GAP-08, GAP-10, GAP-12 | Protect gaps relate to access control, MFA, data handling, change management, and acceptable use. |
| Detect | GAP-10 | Change management and monitoring support detection of unauthorized or risky changes. |
| Respond | GAP-06 | Incident response policy gaps affect communication and response expectations. |
| Recover | GAP-09 | Business continuity gaps affect recovery readiness and resilience. |

---

## Highest Priority NIST-Aligned Improvements

The highest priority improvements are:

1. Strengthen access control policy requirements
2. Define privileged access approval and review requirements
3. Formalize MFA exception management
4. Define incident response notification expectations
5. Complete high-risk vendor review requirements
6. Strengthen restricted data handling rules
7. Standardize audit evidence retention expectations

---

## Analyst Summary

The policy gaps map most heavily to the Govern and Protect functions.

This indicates that CloudCore Analytics should prioritize security governance, access control, data protection, vendor risk, and evidence management before future audits or customer security reviews.

The company has a foundation in place, but policy language should be strengthened so control expectations are clear, enforceable, and auditable.

---

## Notes

This NIST CSF mapping is part of a mock GRC portfolio project. It demonstrates framework mapping, policy gap analysis, governance review, and audit readiness support.
