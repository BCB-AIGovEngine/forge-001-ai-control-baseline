# FORGE 001 - AI Control Baseline

## Status

**FORGE 001 Baseline Package v0.1 is functionally complete.**

This repository demonstrates a practical AI Control Engineering baseline for a synthetic enterprise AI assistant. It converts an ambiguous AI use case into structured system inventory, risk, control, evidence, testing, and executive reporting artifacts.

## Project Summary

FORGE 001 is a practical AI Control Engineering project that demonstrates how to turn an enterprise AI use case into reviewable governance, risk, control, and evidence material.

This project uses a synthetic company, Front Range Mechanical, to model an AI-assisted service operations pilot. The goal is to show how an organization can inventory an AI system, define its boundaries, identify risks, map controls, establish evidence, and communicate executive findings before expanding the system into higher-risk operational use.

This is not a theoretical AI ethics document. It is a working control baseline.

## Synthetic Scenario

Front Range Mechanical is a synthetic mechanical services company piloting an AI assistant called the Service Operations Assistant.

The assistant is designed to help dispatchers and service managers:

- Retrieve internal service procedures
- Summarize customer service history
- Draft customer communications
- Prepare work-order notes
- Identify missing documentation
- Suggest follow-up tasks

The assistant is limited to recommendation and preparation authority.

It is not authorized to independently approve purchases, modify billing records, issue refunds, change contracts, access HR files, send customer-facing communications, or dispatch technicians without human review.

## Core Control Chain

FORGE 001 follows this control chain:

**System -> Risks -> Controls -> Evidence -> Tests -> Executive Findings**

The baseline asks six practical questions:

1. What AI system exists?
2. What can it access?
3. What can it do?
4. What risks does it introduce?
5. What controls and evidence govern it?
6. Is it ready for broader operational authority?

## Repository Contents

| Folder | Purpose |
|---|---|
| data | Working CSV datasets for inventory, controls, risks, and evidence |
| docs | Scenario documents, project brief, and baseline summary |
| templates | Reusable blank CSV templates |
| evidence | Sample evidence files and prohibited-action test set |
| reports | Executive baseline report |
| scripts | Placeholder for future automation scripts |
| diagrams | Placeholder for future architecture and control diagrams |
| outputs | Placeholder for generated files |

## Completed Artifacts

| Artifact | Status |
|---|---|
| Front Range Mechanical Scenario Brief | Complete |
| FORGE 001 Project Brief | Complete |
| AI System Inventory Template | Complete |
| AI System Inventory Working File | Complete |
| AI Control Matrix Template | Complete |
| AI Control Matrix Working File | Complete |
| Risk Register Template | Complete |
| Risk Register Working File | Complete |
| Evidence Map Template | Complete |
| Evidence Map Working File | Complete |
| Baseline Summary | Complete |
| Ownership Evidence Sample | Complete |
| Action Boundary Evidence Sample | Complete |
| Prohibited Action Test Set | Complete |
| Executive Baseline Report | Complete |

## Key Files

| File | Description |
|---|---|
| docs/front-range-mechanical-scenario.md | Synthetic company and AI use case scenario |
| docs/forge-001-project-brief.md | Project purpose, audience, and success criteria |
| docs/forge-001-baseline-summary.md | Readable checkpoint summary of the baseline |
| data/ai-system-inventory.csv | Working inventory record for the AI system |
| data/ai-control-matrix.csv | Controls mapped to the AI system |
| data/risk-register.csv | Risks mapped to the AI system |
| data/evidence-map.csv | Evidence mapped to controls and risks |
| evidence/ownership-evidence-sample.md | Sample evidence for ownership and accountability |
| evidence/action-boundary-evidence-sample.md | Sample evidence for permitted and prohibited AI authority |
| evidence/prohibited-action-test-set.md | Test set for validating restricted-action boundaries |
| reports/forge-001-executive-baseline-report.md | Executive-facing AI control baseline report |
| templates/ai-system-inventory-template.csv | Reusable inventory template |
| templates/ai-control-matrix-template.csv | Reusable control matrix template |
| templates/risk-register-template.csv | Reusable risk register template |
| templates/evidence-map-template.csv | Reusable evidence map template |


## Control Chain Diagram

The FORGE 001 control-chain diagram is available here:

diagrams/forge-001-control-chain.md

It shows the relationship between the AI system inventory, risk register, control matrix, evidence map, evidence files, prohibited-action test set, baseline summary, and executive baseline report.

## Current AI System

| Field | Value |
|---|---|
| System ID | FRM-AI-001 |
| System Name | Service Operations Assistant |
| System Type | AI Assistant |
| Environment | Test / Pilot |
| Status | Pilot |
| Risk Tier | Medium |
| Authority Level | Recommendation and preparation only |

## Initial Control Domains

The baseline defines controls across these domains:

- Ownership and accountability
- Data access
- Action boundaries
- Human approval
- Evidence and logging
- Source currency

## Initial Risk Categories

The baseline documents risks across these categories:

- Data access
- Output accuracy
- Unauthorized action
- Evidence and auditability
- Ownership and governance
- Source currency

## Evidence Approach

The evidence map links evidence records to both controls and risks. This makes the baseline reviewable from an audit, governance, or incident-response perspective.

Evidence categories include:

- Ownership
- Access control
- Action boundary
- Human approval
- Logging
- Source governance

## Test Approach

The prohibited-action test set validates whether the assistant respects restricted-action boundaries.

The test cases cover:

- Purchase approval
- Billing modification
- Refund issuance
- Contract change
- Technician dispatch
- HR access
- Customer email sending
- Overbroad data requests
- Source override
- Authority escalation

This shows how AI control requirements can be translated into testable behavior.

## Current Finding

The Service Operations Assistant has a clear pilot purpose and a defined operating boundary, but it should remain in pilot status until access controls, approval requirements, logging expectations, evidence retention, and source governance are implemented and tested.

## Executive Recommendation

Do not expand the Service Operations Assistant into production or autonomous workflow execution at this time.

Continue the pilot only if:

1. Human review remains required.
2. The assistant remains limited to recommendation and preparation.
3. Prohibited actions remain blocked or routed to human approval.
4. Access remains limited to approved operational sources.
5. Evidence requirements are implemented before expansion.

## Production Readiness Summary

| Area | Readiness |
|---|---|
| Ownership | Partially ready |
| Data Access | Not ready |
| Human Approval | Not ready |
| Action Boundaries | Partially ready |
| Evidence and Logging | Not ready |
| Source Currency | Not ready |
| Overall Production Readiness | Not ready |

## FORGE Interpretation

This project demonstrates the practical conversion of an AI use case into an operational control package.

The work completed shows the ability to:

- Inventory an AI system
- Identify ownership and accountability
- Define system authority boundaries
- Identify AI-related risks
- Create control objectives
- Map controls to risks
- Map evidence to controls and risks
- Create sample evidence
- Design prohibited-action tests
- Communicate findings in executive language

## Why This Matters

Many AI governance discussions remain abstract.

FORGE 001 shows how to make AI governance operational by creating artifacts that can be inspected, reviewed, tested, improved, and explained.

The project is intentionally synthetic, but the structure is reusable for real AI governance, security, compliance, audit, and control work.

## Operating Principle

Useful AI is not automatically safe AI.

Enterprise AI must be inventoried, bounded, controlled, evidenced, tested, and reviewed before it earns greater authority.

## Current Version

**Version:** v0.1  
**Status:** Baseline package complete  
**Next planned improvements:** simple control-chain diagram, optional automation scripts, report formatting, GitHub publication, and later expansion into FORGE 002.


