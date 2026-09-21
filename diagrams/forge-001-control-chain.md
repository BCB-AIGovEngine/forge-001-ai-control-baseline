# FORGE 001 - Control Chain Diagram

## Purpose

This diagram shows the core AI control-engineering chain for FORGE 001.

It illustrates how the synthetic Service Operations Assistant moves from inventory and risk identification into controls, evidence, testing, and executive reporting.

## Mermaid Diagram

~~~mermaid
flowchart LR
    A[AI System Inventory<br/>data/ai-system-inventory.csv]
    B[Risk Register<br/>data/risk-register.csv]
    C[Control Matrix<br/>data/ai-control-matrix.csv]
    D[Evidence Map<br/>data/evidence-map.csv]
    E[Evidence Files<br/>evidence/*.md]
    F[Prohibited-Action Test Set<br/>evidence/prohibited-action-test-set.md]
    G[Baseline Summary<br/>docs/forge-001-baseline-summary.md]
    H[Executive Baseline Report<br/>reports/forge-001-executive-baseline-report.md]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> H
    A --> G
    B --> G
    C --> G
    D --> G
    G --> H
~~~

## Control Logic

The FORGE 001 control chain follows this sequence:

1. **Inventory the AI system**
2. **Identify and classify risks**
3. **Define controls**
4. **Map required evidence**
5. **Create or retain evidence artifacts**
6. **Test prohibited or restricted actions**
7. **Translate results into executive findings**

## Practical Interpretation

This diagram represents the operating logic of FORGE 001:

**System -> Risks -> Controls -> Evidence -> Tests -> Executive Findings**

Useful AI is not automatically safe AI.

Enterprise AI must be inventoried, bounded, controlled, evidenced, tested, and reviewed before it earns greater authority.
