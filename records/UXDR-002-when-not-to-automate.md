# UXDR-002: Preserving Human Judgment by Not Automating

## Decision
Explicitly avoid automating certain user-facing decisions where human judgment is essential to trust, fairness, or contextual accuracy.

## Context
As systems scale, pressure often arises to automate judgment-heavy processes in the name of efficiency, consistency, or cost reduction. Automation is frequently framed as neutral or objective, even when applied to domains involving ambiguity, lived experience, or unequal power dynamics.

Once automated, these decisions become harder to question, appeal, or contextualize.

## Problem Statement
Automating judgment too early or too broadly can:
- obscure accountability
- amplify existing bias
- reduce users’ ability to explain their circumstances
- create false certainty where ambiguity is inherent

The problem is not automation itself, but automation applied without regard for epistemic limits.

## Options Considered
**Option 1: Fully automate decisions once rules are defined**  
Benefits: speed, consistency, scalability  
Limitations: brittle outcomes; reduced legitimacy

**Option 2: Hybrid automation with human review thresholds**  
Benefits: partial efficiency with oversight  
Limitations: review often becomes performative under load

**Option 3: Preserve human judgment for specific decision classes**  
Benefits: contextual accuracy; sustained trust  
Limitations: higher operational cost; slower throughput

## Decision Rationale
Preserving human judgment was selected for decision classes where:
- user context materially affects outcomes
- errors disproportionately harm vulnerable users
- appeals or explanations are integral to perceived fairness

This decision prioritizes legitimacy and trust over throughput.

## Expected Impact
- Greater user willingness to engage honestly
- Improved perception of procedural fairness
- Slower but more defensible decision-making
- Clearer accountability pathways

## Risks and Mitigations
**Risk:** Operational cost increases  
**Mitigation:** Narrow scope to high-impact decisions only

**Risk:** Inconsistency across human decisions  
**Mitigation:** Shared principles and decision support, not rigid rules

## Review and Revisit Criteria
Revisit if:
- decision volume exceeds sustainable human capacity
- new evidence demonstrates automation improves equity
- appeal rates or user harm indicators change materially

## Status
Accepted

## Date
2025-07-15
