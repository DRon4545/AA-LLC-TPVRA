# AA LLC — Third-Party Vendor Risk Assessment

A fictional, GitHub-ready Third-Party Vendor Risk Assessment (TPVRA) package for **AA LLC**, a government contracting and procurement business.

> **Important:** All vendors, responses, scores, and results in this repository are fictional examples created for training, portfolio, and GRC practice purposes. This package is not a determination of compliance with any specific federal contract, FAR/DFARS clause, CMMC requirement, NIST publication, or agency requirement.

## Repository Contents

| File | Purpose |
|---|---|
| `README.md` | Project overview, methodology, and usage |
| `vendor-assessment.md` | Complete questionnaire, fictional responses, scoring, and findings |
| `risk-matrix.md` | Scoring model, thresholds, and risk matrix |
| `risk-register.md` | Consolidated risk register and remediation tracking |
| `NOTES.md` | Assessment assumptions and analyst notes |

## Business Context

AA LLC is modeled as a government contracting/procurement business that uses third-party vendors for IT, procurement, logistics, and operational services.

Potential third-party exposure includes:

- Government-related contract information
- Procurement and supplier information
- Company confidential information
- Personally identifiable information (PII)
- Access to AA LLC systems
- Operational dependency on external suppliers and subcontractors

## Risk Domains

| Domain | Weight |
|---|---:|
| Information Security & Cybersecurity | 30% |
| Data Protection & Privacy | 20% |
| Government Contracting / Compliance | 20% |
| Business Continuity & Resilience | 15% |
| Third-Party / Operational Risk | 15% |
| **Total** | **100%** |

## Risk Rating

Higher scores represent higher risk.

| Score | Rating | General Treatment |
|---:|---|---|
| 1.00–1.99 | Low | Standard vendor management |
| 2.00–2.99 | Moderate | Remediation and enhanced monitoring |
| 3.00–3.99 | High | Management approval and formal remediation |
| 4.00–5.00 | Critical | Do not onboard without remediation or documented risk acceptance |

## Assessment Results

| Vendor | Service | Score | Rating | Recommended Status |
|---|---|---:|---|---|
| FederalTech Solutions LLC | IT / Managed Services | 1.69 | Low | Approve |
| SecureSource Procurement Inc. | Procurement / Logistics | 2.85 | Moderate | Conditional Approval |
| RapidSource Logistics LLC | Logistics / Procurement | 4.27 | Critical | Remediation Required |

## Suggested Workflow

1. Identify vendor
2. Determine inherent risk
3. Issue assessment questionnaire
4. Collect supporting evidence
5. Score responses
6. Calculate weighted risk
7. Assign risk rating
8. Conduct management review
9. Approve, conditionally approve, or reject
10. Establish contractual requirements
11. Monitor vendor
12. Reassess periodically

## Suggested Evidence

Depending on the vendor and applicable contract requirements, AA LLC may request:

- Security policies
- SOC 2 or equivalent independent assurance reports
- Vulnerability-management evidence
- Penetration-test summary
- Incident-response plan
- Business continuity/disaster recovery plan
- MFA and access-control evidence
- Cyber insurance certificate
- Data retention/deletion procedures
- Security-awareness training evidence
- Subcontractor management procedures
- Relevant government-contract compliance documentation

## Portfolio Note

This repository demonstrates a repeatable GRC process: **identify → assess → score → rate → remediate → monitor**.
