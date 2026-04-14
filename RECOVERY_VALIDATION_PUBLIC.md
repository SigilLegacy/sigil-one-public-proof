# Recovery Validation Public Note

## Purpose

This note presents a public-facing version of the recovery validation work behind Dylan Fratangeli's broader runtime-control and validation systems.

It is designed to show real structure without publishing the full private control layer.

## Summary

Recovery validation is the process of deciding whether a claimed recovery action should be accepted, rejected, or blocked based on evidence, authorization, internal consistency, and state safety.

The core question is simple:

**Was this recovery attempt legitimate enough to trust?**

This framing treats recovery as a bounded state transition, not a narrative assembled after the fact.

## Core principles

A valid recovery process should enforce these constraints:

- no recovery without evidence
- no recovery without authority
- no recovery that creates an impossible or unsafe state
- no completion claim without explicit proof
- no guessing when required observability is missing

## Core field model

A recovery validation evaluates a claim built from nine fields:

1. `recovery_actor`
2. `recovery_trigger`
3. `requested_action`
4. `target_status`
5. `residue_status`
6. `branch_authority_status`
7. `current_state`
8. `projection_mode`
9. `completion_claim_status`

These fields are used to evaluate whether a recovery action is authorized, evidence-backed, internally consistent, and safe to accept.

## Outcome model

A recovery validator should return one of three outcomes:

- **pass**  
  All required checks succeed.

- **fail**  
  A rule is definitively violated.

- **blocked**  
  The system lacks enough trustworthy evidence to decide.

The blocked outcome matters because it prevents missing observability from being silently replaced by guesswork.

## What recovery validation checks

At a public level, recovery validation should answer five questions:

1. **Was the actor real and authorized?**
2. **Did a real trigger justify recovery entry?**
3. **Was the requested action within allowed bounds?**
4. **Did the claimed state remain internally consistent?**
5. **Was completion proven rather than inferred?**

## High-level rule surface

A serious recovery validator typically enforces rules like these:

- required fields must be present
- status values must use approved vocabularies
- actor identity must be provable
- actor authorization must match the requested action
- the trigger must exist and be traceable
- the current state must support the claimed output mode
- blocking residue must constrain recovery claims
- completion must meet explicit evidence thresholds
- missing or unreliable evidence must prevent overclaiming

## Evidence requirements

A credible recovery review should be able to show:

- the recovery request itself
- actor authentication evidence
- authorization decision evidence
- trigger provenance
- state transition evidence
- integrity evidence
- time-ordering evidence
- trace or correlation evidence when available

This keeps recovery evaluation tied to records, not retrospective explanation.

## Why this matters

Many systems can produce a clean recovery story after the fact.

That does not mean the recovery was legitimate.

A validator is valuable because it forces recovery to be:

- auditable
- bounded
- evidence-backed
- safety-aware
- fail-closed when required evidence is missing

## What this note does not include

This public note does not publish:

- the full private runtime boot surfaces
- the full canonical control pack
- exact authority ordering
- exact runner syntax
- exact state machine details
- exact transition and completion thresholds
- internal dispatch or enforcement logic

Those materials remain private.

## Position in the broader system

This artifact is one public slice of a larger stack:

- **Sigil One** = product-facing layer
- **GoldenState** = runtime authority and execution framing layer
- **FSP** = formal validation and bounded-state control layer
- **Recovery validation** = one concrete proof surface showing how bounded validation is applied in practice

## Public use

This note is intended to serve as:

- a public proof artifact
- a repo-readable architecture note
- a search-supporting evidence surface
- a bridge between private depth and public verification

## Boundary statement

This is not the full archive.
This is not the full implementation.
This is not production code.

This is a curated public proof note designed to show substance without disclosing the full internal control grammar.
