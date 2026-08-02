# Dylan Fratangeli | Sigil Systems Public Proof

Public proof repository for selected work by Dylan Fratangeli under Sigil Systems.

This repository preserves bounded product evidence, validation and recovery records, conceptual observations, and external review materials without publishing private source code or internal control systems.

Each record is presented with its own scope, provenance, classification, and proof limits.

The current lead proof object is the live Sigil One web app.

## Proof areas

- [Sigil One product proof](#current-proof-object)
- [Conceptual observations](#conceptual-observations)
- [Validation and recovery records](#earlier-public-validation-artifacts)
- External review evidence

## Current proof object

**Sigil One** is a live web application at https://sigil-one.com.

It helps someone estimate likely crypto tax exposure before selling, preserve the scenario as a decision record, and export a CPA-ready handoff bundle.

The product is focused on one clear moment:

understanding the likely tax consequence before a crypto sale happens.

## What Sigil One does

Sigil One is a before-you-sell crypto tax exposure tool.

It is decision-support and recordkeeping support, not tax filing software. The user provides the figures. The app helps organize the assumptions, estimate the likely exposure, preserve the scenario, and export a clean handoff that an accountant can review.

The goal is consequence clarity before action, not blind automation.

## Current workflow

1. Estimate the exposure
2. Save the snapshot
3. Export the handoff bundle
4. Verify the record later

## Source-review intake

Manual input and CSV-assisted intake are intentional.

Sigil One does not connect to wallets or exchanges in this version. The user reviews and confirms the source data before it becomes part of the working record.

This keeps the workflow close to the actual decision:

- What am I about to sell?
- What assumptions am I using?
- What is the likely tax exposure?
- What can I hand to a CPA afterward?

## Paid artifact

The paid export is a CPA-ready handoff bundle built from the saved snapshot and its assumptions.

Current handoff artifacts include:

- Tax Handoff PDF
- Tax Handoff CSV
- Proof Archive

The handoff is designed to make the scenario reviewable, structured, and easier to verify later.

## Current product proof themes

Recent app work has focused on:

- CSV intake as staged source evidence
- review flags, filters, and confirmation before source rows affect records
- saved snapshots as decision records
- export-time verification persistence
- UTC snapshot timestamp standardization
- report-type export entitlement windows
- CPA disposal report path and eligibility checks
- durable manual disposal records
- projected and realized exposure separation
- tutorial, settings, About, legal, and onboarding surfaces
- dashboard and holdings loading improvements
- landing page copy and proof visuals rebuilt around the paid handoff artifact

## Public-safe technology overview

Sigil One is a private source code application with a public product surface.

The current app has been built with:

- Next.js
- TypeScript
- React
- Vercel
- Prisma and PostgreSQL
- Supabase
- Stripe
- CSV parsing
- PDF and archive generation
- automated smoke tests across core flows

This repository does not publish the app source code.

## Boundaries

Sigil One is:

- decision-support for a possible crypto sale
- recordkeeping support
- a CPA handoff preparation tool
- a source-review workflow
- a live product under active development

Sigil One is not:

- tax filing software
- official tax advice
- a wallet connection product
- an exchange connection product
- a trading bot
- a market price feed
- a claim to know what the user owes

Exposure estimates are based on the values and assumptions the user enters and confirms.

## Conceptual observations

This repository includes narrowly scoped conceptual observations from external practitioners where publication permission, context, attribution, and classification boundaries have been preserved.

These records are not presented as testimonials, technical validation, evidence of effectiveness, endorsements, or recommendations unless the record explicitly states otherwise.

### Jozsef Fodor — Answer-Layer Admissibility Boundary

The approved record is stored at:

`conceptual_observations/jozsef-fodor-answer-layer-admissibility/`

It presents a bounded conceptual observation concerning Dylan Fratangeli’s answer-layer framing and the distinction between an upstream admissibility boundary and later agent or action governance.

The observation remains attached to its disclaimer and record context. It is classified only as a conceptual observation based on public framing and direct exchange.

## Included files

### `README.md`

The front door for this public proof repository.

It should be read first because it explains the current lead product proof object, the wider proof areas, and how earlier public artifacts fit into the repository.

### `Sigil_One_Public_Repo_Update.txt`

A public build log for Sigil One.

It tracks product scope, shipped updates, product clarity decisions, and lessons from building the live app.

### `PUBLIC_PROOF_NOTE.md`

A public note explaining why this proof repository exists.

It describes the repository as a curated public proof surface, not a full release of private internals.

### `RECOVERY_VALIDATION_PUBLIC.md`

A public-safe architecture note about recovery validation.

It shows one earlier validation artifact and explains how a claimed recovery action can be evaluated using evidence, authority, internal consistency, and state safety.

### `Recovery_Validator_Core_v1_Package.txt`

A compact public validator artifact.

It includes the recovery validation short brief, one-page spec, outcome contract, high-level rule surface, minimal procedure, and evidence minimum.

### `conceptual_observations/`

Repository records for approved conceptual observations.

Each record should preserve:

- exact or materially approved wording
- attribution
- basis and authorized placement
- disclaimer
- classification boundary
- publication scope
- public-safe provenance notes

Private permission screenshots and direct-message records should not be published unless separately authorized.

## Earlier public validation artifacts

This repository also preserves earlier public validation work related to GoldenState, FSP, and recovery validation.

Those artifacts are kept here as labeled public proof, not as the current Sigil One app source code and not as a full release of the private control layer.

They are useful for showing that the work behind Sigil Systems includes structured thinking around validation, recovery, evidence, bounded execution, and public proof packaging.

They should be read as earlier public proof artifacts.

The current Sigil One web app remains the lead product proof object.

## What is intentionally not published here

This repository does not publish:

- the private Sigil One app source code
- private startup and runtime boot surfaces
- the full private control grammar
- exact authority ordering
- exact validator dispatch surfaces
- exact transition logic
- exact completion thresholds
- exact drift and recovery control details
- private permission messages unless separately authorized
- secrets, environment variables, customer data, or production data

The objective is public proof, not uncontrolled disclosure.

## Public links

- Live product: https://sigil-one.com
- Public proof repo: https://github.com/SigilLegacy/sigil-systems-public-proof
- GoldenState: https://sigillegacy.gumroad.com/l/goldenstate
- Legacy Sigil One Excel version: https://sigillegacy.gumroad.com/l/sigil-one
- LinkedIn: https://www.linkedin.com/in/dylanfratangeli
- X: https://x.com/SigilLegacy

## How to read this repository

Recommended reading order:

1. `README.md`
2. `Sigil_One_Public_Repo_Update.txt`
3. `conceptual_observations/`
4. `PUBLIC_PROOF_NOTE.md`
5. `RECOVERY_VALIDATION_PUBLIC.md`
6. `Recovery_Validator_Core_v1_Package.txt`

## Search and identity context

This proof repository is part of the public association layer for:

- Dylan Fratangeli
- Sigil Systems
- Sigil One
- GoldenState
- FSP

It is intended to strengthen the link between public identity and bounded public evidence while keeping private implementation details protected.

## About

Built by Dylan Fratangeli under Sigil Systems.

Sigil Systems is a veteran-owned software company focused on decision support, record preservation, evidence-aware validation, and practical financial clarity.
