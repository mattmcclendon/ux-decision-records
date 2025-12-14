# UX Decision Records

## Purpose
This repository documents consequential user experience and system design decisions using a structured, written format.

The goal is not to showcase polished artifacts. The goal is to make reasoning visible, including tradeoffs, constraints, and rejected alternatives.

Design decisions shape behavior long after interfaces ship. This repository treats those decisions as first-class system components.

## Context
In mature systems, the most impactful UX work happens upstream:
- framing problems
- defining constraints
- choosing which users to prioritize
- deciding what *not* to optimize

These decisions are often implicit, undocumented, or lost to time. UX Decision Records exist to preserve institutional memory and accountability.

This approach is inspired by Architecture Decision Records, adapted for design, data, and human-centered systems.

## What Is a UX Decision Record
A UX Decision Record (UXDR) is a short, structured document that captures:
- the decision being made
- the context in which it occurred
- the alternatives considered
- the rationale behind the final choice
- the anticipated impact on users and the system

Each record reflects a moment where judgment mattered.

## Structure
/records/     Individual UX Decision Records (markdown)
/templates/   Canonical UXDR template
/references/  Supporting material and citations

Records are numbered sequentially to emphasize continuity over recency.

## When to Create a Record
A UX Decision Record is appropriate when:
- the decision has irreversible or long-term consequences
- tradeoffs meaningfully affect different user groups
- constraints are imposed by policy, data, or infrastructure
- future teams will ask “why did we do it this way?”

Not every decision deserves a record. Important ones do.

## What This Is Not
This repository is not:
- a design portfolio
- a collection of case studies
- a retrospective justification exercise

Records may age. Decisions may be revisited. The documentation remains useful regardless.

## What I Would Do Next
With broader adoption, this approach could support:
- design governance in large organizations
- cross-functional alignment between UX, policy, and engineering
- post-incident analysis when trust or usability breaks down

## Related Work
This repository is part of a broader line of inquiry into signal integrity and institutional trust.

- **Signal and Trust Notes**  
  https://github.com/mattmcclendon/signal-and-trust-notes

That repository explores the systemic consequences of design and policy decisions documented here.

## Status
Active reference and working archive.

Records are added selectively and intentionally.
