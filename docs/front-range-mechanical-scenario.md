# Front Range Mechanical — AI-Assisted Service Operations Scenario

## Scenario Purpose

Front Range Mechanical is a synthetic small-to-mid-sized mechanical services company used for FORGE 001: AI Control Baseline.

The purpose of this scenario is to model how an enterprise might introduce an AI assistant into real operational workflows, then identify the governance, security, identity, data, authorization, evidence, and oversight controls required to keep that system accountable.

This scenario is synthetic. It is designed for portfolio, training, governance design, control mapping, and AI Control Engineering demonstration purposes.

## Company Profile

Front Range Mechanical provides HVAC, mechanical maintenance, and field-service support to commercial and light industrial customers across Northern Colorado.

The company has approximately 85 employees, including office staff, dispatchers, service managers, field technicians, sales personnel, and executive leadership.

The company uses Microsoft 365 for email, document storage, Teams collaboration, SharePoint sites, customer documentation, service forms, and internal procedures.

## AI Use Case

Front Range Mechanical is piloting an AI-assisted service operations tool called the Service Operations Assistant.

The assistant is intended to help office staff and service managers retrieve operational information, summarize service history, draft customer communications, prepare work-order notes, and support dispatch decision-making.

The assistant is not initially allowed to independently approve purchases, modify billing records, issue refunds, terminate employees, change customer contracts, or dispatch technicians without human review.

## Primary AI Functions

The Service Operations Assistant may perform the following functions:

1. Retrieve internal service procedures.
2. Summarize customer service history.
3. Draft customer emails.
4. Prepare internal work-order notes.
5. Suggest likely parts or follow-up tasks.
6. Help managers review technician notes.
7. Identify missing information in service documentation.
8. Support basic reporting on service trends.

## Data Sources

The assistant may interact with or reference the following data sources:

- SharePoint service procedure documents
- Microsoft Teams channel content
- Customer service records
- Work-order notes
- Technician reports
- Email drafts
- Internal policy documents
- Vendor and parts documentation
- Basic service metrics

## Sensitive Data Categories

The environment may contain:

- Customer names and contact information
- Customer addresses
- Building access details
- Service history
- Technician notes
- Internal pricing or quote information
- Employee names and schedules
- Vendor information
- Potentially sensitive operational details

## Initial Control Concerns

The company is concerned about the following risks:

- AI accessing more customer information than necessary
- AI drafting inaccurate customer communications
- AI exposing internal notes to the wrong audience
- AI making recommendations based on outdated procedures
- AI creating operational dependency without review
- Weak evidence showing why an AI recommendation was made
- Lack of clear ownership over the AI system
- Unclear boundaries between suggestion, preparation, and action

## Control Baseline Objective

FORGE 001 will create an AI Control Baseline for this scenario.

The baseline will document:

- What the AI system is
- Who owns it
- What data it uses
- What actions it can perform
- What actions it cannot perform
- What human approvals are required
- What evidence must be retained
- What risks exist
- What controls should be implemented
- How the system should be reviewed over time

## FORGE 001 Deliverables

The project will produce:

1. AI System Inventory
2. AI Risk Register
3. AI Control Matrix
4. AI Evidence Map
5. Executive Baseline Report

## Operating Principle

The core principle of this scenario is:

An enterprise AI system should not be trusted merely because it is useful. It should be bounded, observed, reviewed, evidenced, and controlled.

