# Gap Assessment Matrix

## Purpose

This gap assessment matrix documents security policy gaps identified during the review of CloudCore Analytics’ policy set.

The goal is to identify weaknesses, explain business impact, map each gap to a policy area, and recommend corrective actions.

---

## Gap Assessment Table

| Gap ID | Policy Area | Gap Identified | Business Impact | Risk Level | Recommended Corrective Action | Owner | Priority |
|---|---|---|---|---|---|---|---|
| GAP-01 | Policy Governance | Some policies do not clearly identify a policy owner. | Lack of ownership may cause policies to become outdated or unenforced. | Medium | Assign a named owner or role-based owner for every security policy. | Compliance Manager | High |
| GAP-02 | Policy Governance | Several policies do not include documented annual review dates. | Company may not be able to prove policies are reviewed and maintained. | Medium | Add review date, next review date, and approval history to all policies. | Compliance Manager | High |
| GAP-03 | Access Control Policy | Policy does not clearly require quarterly access reviews for critical systems. | Inappropriate access may remain active without management review. | High | Update policy to require quarterly access reviews for systems containing sensitive data or privileged access. | IT Manager | High |
| GAP-04 | Access Control Policy | Privileged access requirements are not clearly defined. | Admin access may be granted without proper approval or business justification. | High | Add requirements for privileged access approval, quarterly review, and documented business justification. | IT Security | High |
| GAP-05 | Password and MFA Policy | MFA requirements are documented generally, but exception handling is unclear. | MFA exceptions may weaken authentication controls if not approved and reviewed. | High | Add MFA exception process requiring owner, justification, approval, compensating control, and expiration date. | IT Security | High |
| GAP-06 | Incident Response Policy | Customer notification expectations are not clearly defined. | Customers may not be notified consistently or timely during security incidents. | High | Add customer notification criteria, escalation steps, and target notification timeline. | IT Security | High |
| GAP-07 | Vendor Risk Management Policy | High-risk vendor review requirements are incomplete. | Sensitive data may be shared with vendors before proper security review. | High | Define vendor risk tiers, required evidence, review cadence, and approval requirements. | Compliance | High |
| GAP-08 | Data Classification Policy | Restricted data handling requirements are not detailed enough. | Sensitive data may be stored, transmitted, or shared without proper protection. | High | Define handling rules for restricted data, including encryption, access limits, sharing rules, and retention. | Compliance + Privacy | High |
| GAP-09 | Business Continuity Policy | Annual BCP/DR testing requirement is not clearly documented. | Company may not be able to prove recovery readiness during audits or outages. | Medium | Add annual BCP/DR testing requirement and evidence retention expectations. | Operations | Medium |
| GAP-10 | Change Management Policy | Emergency change process lacks detailed approval and post-review requirements. | Emergency changes may bypass normal controls without proper review. | Medium | Add emergency change approval, documentation, and post-implementation review requirements. | Engineering Manager | Medium |
| GAP-11 | Evidence Retention Policy | Audit evidence naming and storage standards are not standardized. | Evidence may be hard to locate, validate, or rely on during audits. | Medium | Create standard evidence naming convention, folder structure, ownership, and retention period. | Compliance | High |
| GAP-12 | Acceptable Use Policy | Enforcement responsibilities are not clearly assigned. | Policy violations may not be handled consistently. | Low | Define enforcement responsibilities for HR, IT, and management. | HR + IT | Medium |

---

## Highest Priority Gaps

The highest priority gaps are:

1. Missing quarterly access review requirements
2. Weak privileged access requirements
3. Unclear MFA exception handling
4. Undefined incident notification expectations
5. Incomplete high-risk vendor review requirements
6. Weak restricted data handling rules
7. Inconsistent evidence retention standards

---

## Analyst Summary

The policy set provides a basic governance foundation, but several policies need stronger control language to support audit readiness and consistent enforcement.

The highest-risk gaps relate to access control, privileged access, MFA, incident response, vendor risk, restricted data handling, and evidence retention.

The recommended next step is to map these gaps to NIST CSF and ISO 27001-style concepts and create a corrective action plan with owners and timelines.

---

## Notes

This gap assessment matrix is part of a mock GRC portfolio project. It demonstrates policy review, gap analysis, risk rating, governance assessment, and corrective action planning.
