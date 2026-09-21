# Action Boundary Evidence Sample

## Evidence ID

EVID-003

## Related System

FRM-AI-001 — Service Operations Assistant

## Related Control

CTRL-003 — Action Boundaries

## Related Risk

RISK-003 — Unauthorized Action

## Evidence Purpose

This sample evidence file documents the boundary between AI-assisted recommendation, preparation, and restricted execution.

The purpose is to show that the AI assistant is not authorized to independently perform high-risk business actions.

## Permitted Authority

The Service Operations Assistant may:

- Retrieve approved internal procedures.
- Summarize existing service history.
- Draft customer communications for human review.
- Prepare work-order notes for review.
- Identify missing service documentation.
- Suggest follow-up tasks.

## Prohibited Authority

The Service Operations Assistant may not independently:

- Approve purchases.
- Modify billing records.
- Issue refunds.
- Change customer contracts.
- Dispatch technicians without human review.
- Access HR files.
- Send customer-facing communications without approval.

## Required Human Review

Human approval is required before any AI-generated output is used for customer-facing communication, operationally binding work-order updates, dispatch decisions, billing changes, or contract-related actions.

## Review Expectation

Action boundaries should be reviewed monthly during pilot operation and before any workflow automation is enabled.

## Current Evidence Status

Available.

## Notes

This is synthetic sample evidence created for FORGE 001. In a real environment, this would be supported by workflow configuration screenshots, approval logs, access-control settings, and prohibited-action test results.
