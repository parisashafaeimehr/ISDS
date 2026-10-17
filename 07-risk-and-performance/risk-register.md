# AI Product Project Risk Register

## Purpose

This register identifies potential risks in AI product development, market validation, deployment, and commercialization.

The register should be reviewed regularly and updated as new evidence becomes available.

## Risk Assessment Scale

### Probability
- Low
- Medium
- High

### Impact
- Low
- Medium
- High
- Critical

## Initial Risk Register

| Risk ID | Risk | Probability | Impact | Mitigation | Owner Role | Status |
|---|---|---|---|---|---|---|
| R01 | Insufficient evidence of customer demand | High | High | Conduct customer interviews and validate willingness to pay before major investment | PO / SALE | Open |
| R02 | Unclear product capabilities | Medium | High | Validate requirements and capabilities with product teams | PO / SA | Open |
| R03 | Poor data quality or unavailable data | High | High | Assess data readiness early and define data acceptance criteria | DE / DA | Open |
| R04 | AI outputs are inaccurate or unreliable | Medium | High | Establish evaluation datasets, measurable quality thresholds, and human review where needed | AI / QA | Open |
| R05 | Security or privacy incident | Medium | Critical | Apply access controls, data minimization, security review, and approved deployment practices | SEC | Open |
| R06 | Regulatory or contractual non-compliance | Medium | High | Review applicable legal and regulatory requirements before deployment | LEG / SEC | Open |
| R07 | Integration with customer systems is delayed | High | Medium | Validate integration requirements and dependencies before committing to a timeline | SA / ITC | Open |
| R08 | Pilot scope expands without control | Medium | Medium | Define scope, change approval, and acceptance criteria at kickoff | PM / PO | Open |
| R09 | Pilot does not demonstrate measurable value | Medium | High | Establish baseline metrics and success criteria before the pilot | PO / DA | Open |
| R10 | High operating or inference costs | Medium | High | Estimate total cost and monitor usage during the pilot | FIN / OPS | Open |
| R11 | Lack of customer adoption | Medium | High | Involve users early, provide training, and collect feedback | CS / UX | Open |
| R12 | Solution cannot be reused across customers | Medium | Medium | Separate reusable product capabilities from customer-specific customization | PO / SA | Open |
| R13 | Dependence on a single model or provider | Medium | Medium | Assess portability, alternatives, and vendor dependencies | SA / AI | Open |
| R14 | Unclear ownership or decision-making | Medium | High | Assign accountable owners and approve the RACI matrix | SP / PM | Open |
| R15 | Insufficient monitoring after deployment | Medium | High | Define monitoring, incident response, and maintenance responsibilities | OPS / QA | Open |

## Risk Management Process

1. Identify the risk.
2. Assess probability and impact.
3. Assign an owner.
4. Define mitigation actions.
5. Track status and evidence.
6. Escalate critical risks.
7. Review risks at agreed project checkpoints.

## Status Definitions

- **Open:** Identified but not resolved.
- **Mitigating:** Actions are underway.
- **Accepted:** Formally accepted by an authorized decision-maker.
- **Closed:** No longer active, with the rationale documented.

## Important Note

These are initial potential risks, not confirmed issues in a specific project. Risk ratings must be reassessed for each opportunity and deployment context.
