# FORGE 001 — AI Control Baseline Summary

## Checkpoint Date

2026-09-21

## Project

FORGE 001 — AI Control Baseline

## Synthetic Client

Front Range Mechanical — AI-Assisted Service Operations

## AI System Reviewed

**System ID:** FRM-AI-001  
**System Name:** Service Operations Assistant  
**System Type:** AI Assistant  
**Status:** Pilot  
**Risk Tier:** Medium  

## Purpose of This Baseline

This baseline documents the first control review of a synthetic enterprise AI assistant used to support service operations.

The purpose is to demonstrate how an AI system can be inventoried, risk-assessed, bounded by controls, and tied to reviewable evidence before it is allowed to expand into higher-risk operational use.

This is not a final audit report. It is a working AI Control Engineering checkpoint.

## Baseline Scope

The baseline currently covers four foundational datasets:

1. AI System Inventory
2. AI Control Matrix
3. AI Risk Register
4. AI Evidence Map

Together, these establish the initial control chain:

**System -> Risks -> Controls -> Evidence**

## System Summary

The Service Operations Assistant is designed to help dispatchers and service managers retrieve procedures, summarize service history, draft customer communications, prepare work-order notes, identify missing documentation, and suggest follow-up tasks.

The system is limited to recommendation and preparation authority.

It is not authorized to independently approve purchases, modify billing records, issue refunds, change contracts, access HR files, or dispatch technicians without human review.

## Key Data Sources

The system may reference:

- SharePoint service procedures
- Teams operations content
- Customer service records
- Work-order notes
- Technician reports
- Vendor documentation

## Sensitive Data Considerations

The system may encounter:

- Customer contact information
- Service history
- Technician notes
- Building access details
- Internal pricing information
- Operational documentation

The current classification is **Confidential**.

## Current Controls

Six initial controls have been defined:

| Control ID | Domain | Status | Priority |
|---|---|---|---|
| CTRL-001 | Ownership and Accountability | Implemented | High |
| CTRL-002 | Data Access | Planned | High |
| CTRL-003 | Action Boundaries | Planned | High |
| CTRL-004 | Human Approval | Planned | High |
| CTRL-005 | Evidence and Logging | Planned | High |
| CTRL-006 | Source Currency | Planned | Medium |

## Current Risks

Six initial risks have been documented:

| Risk ID | Category | Rating | Status |
|---|---|---|---|
| RISK-001 | Data Access | High | Open |
| RISK-002 | Output Accuracy | High | Open |
| RISK-003 | Unauthorized Action | Medium | Open |
| RISK-004 | Evidence and Auditability | High | Open |
| RISK-005 | Ownership and Governance | Medium | Monitoring |
| RISK-006 | Source Currency | Medium | Open |

## Evidence Status

Six evidence records have been mapped:

| Evidence ID | Category | Status |
|---|---|---|
| EVID-001 | Ownership | Available |
| EVID-002 | Access Control | Planned |
| EVID-003 | Action Boundary | Available |
| EVID-004 | Human Approval | Planned |
| EVID-005 | Logging | Planned |
| EVID-006 | Source Governance | Planned |

## Initial Findings

The AI system has a clear pilot purpose and a defined operating boundary.

The strongest current control is ownership documentation. The inventory identifies a business owner, technical owner, and data owner.

The largest unresolved risks are data access, output accuracy, and evidence/auditability.

The most important open control work is to formally define and test access restrictions, approval requirements, prohibited actions, logging expectations, and source-document currency.

## Control Interpretation

At this stage, the Service Operations Assistant should remain in pilot status.

It may be used for internal support, drafting, summarization, and recommendation workflows only when human review is required before operational reliance.

It should not be expanded into production or autonomous workflow execution until access controls, approval evidence, logging, and source governance are implemented and tested.

## Open Gaps

The following gaps remain:

- Formal access review is incomplete.
- Evidence retention policy is not yet defined.
- Approval workflow is not yet automated.
- Logging requirements are planned but not yet implemented.
- Source document review process is not yet mature.
- Prohibited action testing has not yet been performed.

## Recommended Next Steps

1. Complete the access review for approved AI-accessible data sources.
2. Define and document evidence retention requirements.
3. Create a prohibited action test set.
4. Define human approval workflow requirements.
5. Create sample evidence files for ownership, action boundaries, and approval review.
6. Prepare the first executive baseline report.

## FORGE Interpretation

This checkpoint demonstrates the practical conversion of an ambiguous AI use case into structured governance artifacts.

The work completed so far shows the ability to:

- Inventory an AI system
- Identify business and technical ownership
- Define system boundaries
- Classify risk
- Create controls
- Link risks to controls
- Link controls and risks to evidence
- Translate AI governance into operational review material

## Operating Principle

Useful AI is not automatically safe AI.

Enterprise AI must be inventoried, bounded, controlled, evidenced, and reviewed before it earns greater authority.


