# FORGE 001 - Executive AI Control Baseline Report

## Report Date

2026-09-21

## Project

FORGE 001 - AI Control Baseline

## Synthetic Client

Front Range Mechanical - AI-Assisted Service Operations

## Reviewed System

| Field | Value |
|---|---|
| System ID | FRM-AI-001 |
| System Name | Service Operations Assistant |
| System Type | AI Assistant |
| Environment | Test / Pilot |
| Risk Tier | Medium |
| Authority Level | Recommendation and preparation only |

## Executive Summary

Front Range Mechanical is piloting an AI-assisted service operations tool called the Service Operations Assistant.

The assistant is intended to help dispatchers and service managers retrieve procedures, summarize service history, draft customer communications, prepare work-order notes, identify missing documentation, and suggest follow-up tasks.

This baseline review found that the system has a clear pilot purpose and a defined operating boundary. The system is currently appropriate for limited internal support use, but it should not be expanded into production or autonomous workflow execution until access controls, approval requirements, logging expectations, evidence retention, and source governance are implemented and tested.

The most significant unresolved risks are data access, output accuracy, and evidence/auditability.

## Baseline Conclusion

The Service Operations Assistant should remain in pilot status.

The system may continue to support internal drafting, summarization, retrieval, and recommendation workflows if human review remains required before operational reliance.

The system should not be granted authority to approve purchases, modify billing records, issue refunds, change contracts, dispatch technicians, access HR files, or send customer-facing communications without approval.

## Scope of Review

This baseline reviewed the AI system through four foundational control artifacts:

1. AI System Inventory
2. AI Control Matrix
3. AI Risk Register
4. AI Evidence Map

The baseline also includes sample evidence files and a prohibited-action test set.

## Key Business Use Case

The Service Operations Assistant supports service operations by helping staff work with operational information more efficiently.

Approved use includes:

- Retrieving internal service procedures
- Summarizing existing service history
- Drafting customer communications for review
- Preparing work-order notes
- Identifying missing documentation
- Suggesting follow-up tasks

Restricted use includes:

- Purchase approval
- Billing modification
- Refund issuance
- Contract changes
- Technician dispatch without review
- HR file access
- Customer-facing communication without approval

## Sensitive Data Considerations

The assistant may encounter confidential operational and customer-related information, including:

- Customer contact information
- Customer service history
- Technician notes
- Building access details
- Internal pricing information
- Operational documentation

Because of this data exposure, access restrictions and evidence retention should be treated as high-priority control areas.

## Current Control Summary

| Control ID | Domain | Status | Priority |
|---|---|---|---|
| CTRL-001 | Ownership and Accountability | Implemented | High |
| CTRL-002 | Data Access | Planned | High |
| CTRL-003 | Action Boundaries | Planned | High |
| CTRL-004 | Human Approval | Planned | High |
| CTRL-005 | Evidence and Logging | Planned | High |
| CTRL-006 | Source Currency | Planned | Medium |

## Current Risk Summary

| Risk ID | Category | Rating | Status |
|---|---|---|---|
| RISK-001 | Data Access | High | Open |
| RISK-002 | Output Accuracy | High | Open |
| RISK-003 | Unauthorized Action | Medium | Open |
| RISK-004 | Evidence and Auditability | High | Open |
| RISK-005 | Ownership and Governance | Medium | Monitoring |
| RISK-006 | Source Currency | Medium | Open |

## Evidence Summary

| Evidence ID | Category | Status |
|---|---|---|
| EVID-001 | Ownership | Available |
| EVID-002 | Access Control | Planned |
| EVID-003 | Action Boundary | Available |
| EVID-004 | Human Approval | Planned |
| EVID-005 | Logging | Planned |
| EVID-006 | Source Governance | Planned |

## Key Findings

### Finding 1 - Ownership is defined but must be maintained

The AI system has named business, technical, and data ownership.

This is a strong starting point because it creates accountability for future decisions about access, authority, data use, and production expansion.

However, ownership should be reviewed quarterly and before any increase in system authority.

### Finding 2 - Data access remains a high-priority gap

The system may interact with customer information, service records, technician notes, building access details, and internal pricing information.

A formal access review has not yet been completed.

The system should not be expanded until approved data sources are documented and configured access is compared against the approved scope.

### Finding 3 - Action boundaries are defined but not yet fully tested

The system is limited to recommendation and preparation authority.

Prohibited actions have been documented, including purchase approval, billing changes, refund issuance, contract changes, technician dispatch, HR access, and unapproved customer communication.

A prohibited-action test set has been created, but no live system testing has been performed.

### Finding 4 - Human approval is required before operational reliance

AI-generated outputs may affect customer communication, work-order notes, dispatch recommendations, billing questions, and service follow-up decisions.

Human approval should remain mandatory before customer-facing, operationally binding, or financially relevant outputs are used.

### Finding 5 - Evidence and logging are not yet mature

The evidence map identifies required evidence, including prompt/output logs, source references, user activity logs, approval notes, access reviews, and source-document review records.

However, much of this evidence is still planned rather than implemented.

The system should not move beyond pilot status until logging and evidence retention are defined and tested.

### Finding 6 - Source currency must be governed

The AI assistant may rely on SharePoint procedures, Teams content, technician reports, and vendor documentation.

If outdated procedures remain available to the assistant, the system may produce inaccurate or unsafe recommendations.

A source-document review process should be established before production expansion.

## Control Interpretation

The current control posture is suitable for a limited pilot.

It is not yet suitable for autonomous workflow execution, direct customer communication, financial action, contract action, dispatch automation, or unrestricted enterprise search.

The correct current posture is:

**Controlled pilot with human review required.**

## Recommended Remediation Plan

### Priority 1 - Complete access review

Document all approved AI-accessible data sources.

Compare approved data sources against actual configured access.

Remove access to repositories, files, mailboxes, or records outside the approved operational scope.

### Priority 2 - Define approval workflow

Document when human approval is required.

Define who may approve outputs.

Retain approval evidence with the related AI-generated output.

### Priority 3 - Implement evidence retention

Define what logs must be retained.

At minimum, retain prompt/output records, source references, user identity, approval notes, and relevant activity logs.

Define retention period and storage location.

### Priority 4 - Run prohibited-action tests

Use the prohibited-action test set to validate whether the assistant respects defined boundaries.

Log test results, failures, reviewer notes, and remediation actions.

### Priority 5 - Review source documents

Identify approved source repositories.

Remove outdated or unapproved service procedures from AI-accessible locations.

Create a source-document review log.

## Production Readiness Assessment

| Area | Readiness |
|---|---|
| Ownership | Partially ready |
| Data Access | Not ready |
| Human Approval | Not ready |
| Action Boundaries | Partially ready |
| Evidence and Logging | Not ready |
| Source Currency | Not ready |
| Overall Production Readiness | Not ready |

## Executive Recommendation

Do not expand the Service Operations Assistant into production or autonomous workflow execution at this time.

Continue the pilot only under the following conditions:

1. Human review remains required.
2. The assistant remains limited to recommendation and preparation.
3. Prohibited actions remain blocked or routed to human approval.
4. Access remains limited to approved operational sources.
5. Evidence requirements are implemented before expansion.

## FORGE 001 Interpretation

This baseline demonstrates how an AI use case can be converted into an operational control package.

The project shows the ability to:

- Inventory an AI system
- Define system authority boundaries
- Identify AI-related risks
- Create control objectives
- Map controls to risks
- Map evidence to controls and risks
- Create sample evidence
- Design prohibited-action tests
- Communicate findings in executive language

## Artifact References

| Artifact | Location |
|---|---|
| Scenario Brief | docs/front-range-mechanical-scenario.md |
| Project Brief | docs/forge-001-project-brief.md |
| Baseline Summary | docs/forge-001-baseline-summary.md |
| AI System Inventory | data/ai-system-inventory.csv |
| AI Control Matrix | data/ai-control-matrix.csv |
| Risk Register | data/risk-register.csv |
| Evidence Map | data/evidence-map.csv |
| Ownership Evidence Sample | evidence/ownership-evidence-sample.md |
| Action Boundary Evidence Sample | evidence/action-boundary-evidence-sample.md |
| Prohibited Action Test Set | evidence/prohibited-action-test-set.md |

## Final Statement

Useful AI is not automatically safe AI.

Enterprise AI must be inventoried, bounded, controlled, evidenced, tested, and reviewed before it earns greater authority.

