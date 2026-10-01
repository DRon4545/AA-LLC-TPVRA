# AA LLC — Assessment Notes

## Purpose

These notes document the assumptions and analyst reasoning behind the fictional third-party vendor risk assessment.

## Analyst Assumptions

1. AA LLC is modeled as a government contracting/procurement organization.
2. The three vendors are entirely fictional.
3. Vendor responses are fictional and intentionally varied to demonstrate the scoring process.
4. Higher scores represent greater control weakness/risk.
5. The five risk domains are weighted according to their assumed importance to AA LLC.
6. The assessment is intended as a practical GRC portfolio example rather than a legal or contractual compliance determination.
7. Actual government requirements must be identified from the specific contract, solicitation, agency, data type, and applicable clauses before making a compliance determination.

## Analyst Thought Process

### Step 1 — Identify the Risk Context

Because AA LLC operates in government contracting/procurement, vendor risk can affect:

- Confidential business information
- Procurement information
- Government contract information
- PII
- System availability
- Supply-chain integrity
- Contractual and regulatory obligations

### Step 2 — Select Risk Domains

The assessment uses five domains:

- Information Security
- Data Protection
- Government Contracting/Compliance
- Business Continuity
- Operational/Supply-Chain Risk

These domains provide coverage across technical, contractual, privacy, resilience, and vendor-management concerns.

### Step 3 — Use a Consistent Scoring Scale

A 1–5 scale makes the questionnaire simple to score and easy to automate later.

The scale is intentionally directional:

> 1 = strong control; 5 = major deficiency.

### Step 4 — Apply Weighting

Information security receives the largest weight because vendors may connect to AA LLC systems or handle sensitive information.

Data protection and government-contract compliance receive the next-largest weights because of the potential consequences of mishandling contract or personal information.

Business continuity and operational risk are also included because vendor failure can disrupt government contracting operations.

### Step 5 — Compare Vendors

FederalTech demonstrates relatively mature controls and therefore receives a low score.

SecureSource demonstrates reasonable but inconsistent controls, particularly around independent validation and subcontractors, producing a moderate score.

RapidSource has deficiencies across nearly every domain, producing a critical score and requiring remediation before sensitive access.

## Important GRC Distinction

The questionnaire score should not be treated as the entire vendor-risk decision.

A mature program should evaluate:

**Inherent Risk + Control Effectiveness + Business Criticality + Contractual Requirements + Compensating Controls = Residual Risk Decision**

## Evidence Validation

A questionnaire response should be considered an assertion until AA LLC validates it with appropriate evidence.

Examples:

- Policy → request policy document
- MFA → obtain configuration evidence or assessment report
- Incident response → review plan/tabletop evidence
- DR → review test results
- Insurance → review certificate
- Independent assessment → review relevant report or attestation
- Subcontractor controls → review supplier-management evidence

## Reassessment

Suggested reassessment cadence:

- Critical: continuous/enhanced monitoring and formal reassessment at least annually
- High: at least annually
- Moderate: annually or according to risk
- Low: periodically based on business criticality

## NIST Alignment Note

This package uses NIST-oriented risk-management concepts such as identifying risk, assessing risk, implementing/assessing controls, responding to risk, and continuous monitoring.

It should **not** be represented as an official NIST assessment or as proof of compliance with NIST SP 800-53, NIST SP 800-161, CMMC, FAR, DFARS, or another specific requirement unless the assessment has been explicitly mapped to the applicable authoritative requirements.

## Portfolio Learning Objective

The project demonstrates the ability to:

- Build a third-party risk questionnaire
- Establish a scoring methodology
- Apply weighted risk calculations
- Assess fictional vendors
- Create a risk register
- Identify remediation priorities
- Document analyst assumptions
- Communicate risk to procurement and management
