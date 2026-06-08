# Policy Findings Report

## Purpose

This findings report summarizes security policy gaps identified during the policy gap assessment for CloudCore Analytics.

The goal is to document each major governance issue in a clear audit-style format, including observation, business impact, root cause, risk level, and recommendation.

---

## Finding 1: Access Control Policy Does Not Require Quarterly Access Reviews

**Risk Level:** High  
**Related Gap:** GAP-03  
**Owner:** IT Manager  
**Related Framework Concepts:** NIST CSF Protect / ISO 27001 User Access Rights Review  

### Observation

The Access Control Policy does not clearly require quarterly access reviews for critical systems or systems containing sensitive data.

### Business Impact

Without formal access review requirements, inappropriate or excessive user access may remain active without management detection. This could increase the risk of unauthorized access and create audit readiness issues.

### Root Cause

The policy was written at a high level and does not include specific control frequency, scope, evidence, or ownership requirements.

### Recommendation

Update the Access Control Policy to require quarterly access reviews for critical systems, privileged access, and systems containing sensitive data. The policy should define required evidence, reviewer responsibilities, and remediation expectations.

---

## Finding 2: Privileged Access Requirements Are Incomplete

**Risk Level:** High  
**Related Gap:** GAP-04  
**Owner:** IT Security  
**Related Framework Concepts:** NIST CSF Protect / ISO 27001 Privileged Access Rights Management  

### Observation

The Access Control Policy does not clearly define privileged access approval, business justification, least privilege expectations, review frequency, or removal requirements.

### Business Impact

Privileged accounts may be granted or retained without proper approval, increasing the risk of unauthorized changes, data exposure, or misuse of administrative permissions.

### Root Cause

Privileged access governance was not fully documented as the company grew.

### Recommendation

Add privileged access requirements to the Access Control Policy, including approval, business justification, least privilege, quarterly review, and removal when no longer needed.

---

## Finding 3: MFA Exception Process Is Not Clearly Defined

**Risk Level:** High  
**Related Gap:** GAP-05  
**Owner:** IT Security  
**Related Framework Concepts:** NIST CSF Protect / ISO 27001 Authentication and Secure Access  

### Observation

The Password and MFA Policy requires MFA generally, but does not clearly define how MFA exceptions are approved, tracked, reviewed, or expired.

### Business Impact

Unmanaged MFA exceptions may weaken authentication controls and increase the risk of account compromise.

### Root Cause

The organization does not have a formal exception management process for authentication controls.

### Recommendation

Create a formal MFA exception process requiring owner, business justification, approval, compensating control, review date, and expiration date.

---

## Finding 4: Incident Response Customer Notification Requirements Are Unclear

**Risk Level:** High  
**Related Gap:** GAP-06  
**Owner:** IT Security  
**Related Framework Concepts:** NIST CSF Respond / ISO 27001 Information Security Incident Management  

### Observation

The Incident Response Policy describes internal incident handling but does not clearly define customer notification criteria, escalation steps, or target notification timeline.

### Business Impact

During a security incident, unclear notification requirements may delay customer communication, increase legal or contractual risk, and reduce customer trust.

### Root Cause

The policy focuses on internal response steps but does not fully address external communication obligations.

### Recommendation

Update the Incident Response Policy to define customer notification criteria, escalation responsibilities, approval process, and target notification timeline.

---

## Finding 5: Vendor Risk Management Policy Does Not Fully Define High-Risk Vendor Requirements

**Risk Level:** High  
**Related Gap:** GAP-07  
**Owner:** Compliance  
**Related Framework Concepts:** NIST CSF Govern / ISO 27001 Supplier Relationship Security  

### Observation

The Vendor Risk Management Policy does not fully define risk tiers, required evidence, review frequency, approval criteria, or monitoring expectations for high-risk vendors.

### Business Impact

Sensitive data may be shared with vendors before proper security and compliance review is completed.

### Root Cause

The vendor risk process was created informally and does not yet reflect risk-based review requirements.

### Recommendation

Update the Vendor Risk Management Policy to define vendor risk tiers, required evidence by risk level, approval requirements, review frequency, and remediation expectations.

---

## Finding 6: Restricted Data Handling Requirements Are Not Detailed Enough

**Risk Level:** High  
**Related Gap:** GAP-08  
**Owner:** Compliance + Privacy  
**Related Framework Concepts:** NIST CSF Protect / ISO 27001 Information Classification and Handling  

### Observation

The Data Classification Policy identifies restricted data but does not clearly define handling rules for storage, transmission, access, sharing, retention, and deletion.

### Business Impact

Sensitive data may be stored, transmitted, or shared without proper protection, increasing privacy, compliance, and security risk.

### Root Cause

The policy defines classification labels but does not provide enough operational handling requirements.

### Recommendation

Update the Data Classification Policy to define restricted data handling rules, including encryption, access limitations, approved storage locations, sharing restrictions, retention, and deletion requirements.

---

## Finding 7: Evidence Retention Standards Are Not Standardized

**Risk Level:** Medium  
**Related Gap:** GAP-11  
**Owner:** Compliance  
**Related Framework Concepts:** NIST CSF Govern / ISO 27001 Documented Information and Audit Evidence  

### Observation

The Evidence Retention Policy is still in draft status and does not define a standard folder structure, naming convention, retention period, evidence owner, or acceptable evidence types.

### Business Impact

Audit evidence may be difficult to locate, validate, or rely on during audits, customer security reviews, or internal assessments.

### Root Cause

Evidence collection has been handled manually and inconsistently by different teams.

### Recommendation

Create a formal evidence retention process with naming standards, folder structure, retention periods, ownership, and acceptable evidence criteria.

---

## Overall Conclusion

CloudCore Analytics has a basic security policy foundation, but several policies need stronger governance language, ownership, review expectations, and control requirements.

The highest-risk gaps relate to access control, privileged access, MFA exceptions, incident response, vendor risk, restricted data handling, and evidence retention.

The company should prioritize policy updates that directly support audit readiness, customer security reviews, and consistent enforcement of security controls.

---

## Notes

This policy findings report is part of a mock GRC portfolio project. It demonstrates policy gap documentation, audit-style findings, root cause analysis, business impact writing, and remediation recommendations.
