# FSP Public Vocabulary

Public terminology for discussing FSP without publishing its private control logic.

This vocabulary explains public concepts, not mechanisms. It does not define execution order, authority precedence, decision thresholds, state-machine rules, validation grammar, runner syntax, adapters, dispatch behavior, retry behavior, or enforcement logic.

`FSP` is used as a project label here. No acronym expansion is asserted.

## Core terms

### FSP

The Sigil Systems project label for structured validation and bounded-state control work. It is not a certification, a public implementation specification, or a claim of platform-native enforcement.

### Bounded

Limited to a declared object, scope, evidence set, and decision.

### Object

The specific item, record, task, artifact, or system condition that a claim concerns.

### Scope

The declared boundary around an object and the action being considered. A scope says what is included and what remains outside the claim.

### Claim

A statement about an object, action, state, or outcome that may require evidence before it can be accepted.

### Evidence

An inspectable record tied to a claim. Evidence may support a claim without proving anything beyond the record's stated boundary.

### Evidence-backed

Supported by identified evidence rather than narrative alone.

### State

The recorded condition of an object at an identified point in time.

### State transition

A recorded change from one state to another. This term does not disclose which transitions are permitted or how they are evaluated.

### Authority

Evidence that an actor or system is permitted to act within a stated scope. Public use of this term does not reveal private authority ordering or approval rules.

### Authentication

Evidence concerning the identity of an actor or system.

### Authorization

Evidence that an identified actor or system may take the action in scope.

### Validation

The act of checking whether a bounded claim is supported by the evidence available to the evaluator.

### Recovery validation

A structured evaluation of whether a bounded recovery claim can be accepted, rejected, or left undecided based on the evidence available.

### Trigger

A recorded condition that prompts an evaluation or recovery attempt.

### Outcome

The reported result of a bounded validation. Public FSP materials use three outcome labels.

- **Pass:** the declared check succeeded within its stated scope.
- **Fail:** available evidence establishes that the declared check did not succeed.
- **Blocked:** the available evidence is not sufficient or reliable enough to decide safely.

An outcome applies only to the named object, check, evidence set, and time. It is not a whole-system certification.

### Recovery

A bounded attempt to return an object or process to a valid operating state after interruption, failure, or loss of reliable state.

### Residue

An unresolved condition that remains after an attempted action or recovery. Residue may limit what can be claimed about the resulting state.

### Drift

A meaningful difference between an expected condition and an observed condition.

### Completion claim

A statement that required work has finished. In public FSP framing, a completion claim is distinct from progress, readiness, or a model's narrative assertion.

### Projection

A declared level of commitment in an output. Exact projection modes and their treatment remain private.

### Observability

The ability to inspect the records needed to evaluate a bounded claim.

### Integrity evidence

Evidence used to assess whether a record remained identifiable, consistent, and reliable.

### Time ordering

Evidence showing the relevant sequence of recorded events.

### Trace or correlation

A documented link among records belonging to the same evaluated activity.

### Fail closed

Refusing to convert missing or unreliable evidence into a positive claim.

### Public proof surface

A curated set of evidence intended for inspection. It is not the full implementation, private archive, or internal control system.

## Disclosure boundary

This file does not publish or authorize publication of:

- private prompts, boots, rule banks, or control packages
- exact transition or completion conditions
- authority hierarchy or precedence
- scoring, weighting, or decision thresholds
- internal schemas, identifiers, hashes, paths, ports, or credentials
- dispatch, retry, recovery, or enforcement mechanics
- internal status commands, activation labels, adapters, or service names
- source code or production configuration

These definitions are explanatory only. They are not an executable specification, activation artifact, authority record, validation receipt, or claim of production readiness.
