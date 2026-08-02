# Dylan Fratangeli | Sigil Systems Public Proof

Public proof surface for work by Dylan Fratangeli under Sigil Systems.

This repository makes the current Sigil One product easier to understand and verify in public without publishing the private application source code or the full internal validation layer.

The current lead proof object is the live Sigil One web app.

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

What am I about to sell?
What assumptions am I using?
What is the likely tax exposure?
What can I hand to a CPA afterward?

## Paid artifact

The paid export is a CPA-ready handoff bundle built from the saved snapshot and its assumptions.

Current handoff artifacts include:

* Tax Handoff PDF
* Tax Handoff CSV
* Proof Archive

The handoff is designed to make the scenario reviewable, structured, and easier to verify later.

## Current product proof themes

Recent app work has focused on:

* CSV intake as staged source evidence
* review flags, filters, and confirmation before source rows affect records
* saved snapshots as decision records
* export-time verification persistence
* UTC snapshot timestamp standardization
* report-type export entitlement windows
* CPA disposal report path and eligibility checks
* durable manual disposal records
* projected and realized exposure separation
* tutorial, settings, About, legal, and onboarding surfaces
* dashboard and holdings loading improvements
* landing page copy and proof visuals rebuilt around the paid handoff artifact

## Public-safe technology overview

Sigil One is a private source code application with a public product surface.

The current app has been built with:

* Next.js
* TypeScript
* React
* Vercel
* Prisma and PostgreSQL
* Supabase
* Stripe
* CSV parsing
* PDF and archive generation
* automated smoke tests across core flows

This repository does not publish the app source code.

## Boundaries

Sigil One is:

* decision-support for a possible crypto sale
* recordkeeping support
* a CPA handoff preparation tool
* a source-review workflow
* a live product under active development

Sigil One is not:

* tax filing software
* official tax advice
* a wallet connection product
* an exchange connection product
* a trading bot
* a market price feed
* a claim to know what the user owes

Exposure estimates are based on the values and assumptions the user enters and confirms.

## Included files

### `README.md`

The front door for this public proof surface.

It should be read first because it explains the current live Sigil One app and how the older proof artifacts fit into the repo.

### `Sigil_One_Public_Repo_Update.txt`

A public build log for Sigil One.

It tracks product scope, shipped updates, product clarity decisions, and lessons from building the live app.

### `PUBLIC_PROOF_NOTE.md`

A public note explaining why this proof surface exists.

It describes the repo as a curated public proof surface, not a full release of private internals.

### `RECOVERY_VALIDATION_PUBLIC.md`

A public-safe architecture note about recovery validation.

It shows one earlier validation artifact and explains how a claimed recovery action can be evaluated using evidence, authority, internal consistency, and state safety.

### `Recovery_Validator_Core_v1_Package.txt`

A compact public validator artifact.

It includes the recovery validation short brief, one-page spec, outcome contract, high-level rule surface, minimal procedure, and evidence minimum.

## Earlier public validation artifacts

This repository also preserves earlier public validation work related to GoldenState, FSP, and recovery validation.

Those artifacts are kept here as labeled public proof, not as the current Sigil One app source code and not as a full release of the private control layer.

They are useful for showing that the work behind Sigil Systems includes structured thinking around validation, recovery, evidence, bounded execution, and public proof packaging.

They should be read as earlier public proof artifacts.

The current Sigil One web app should be read as the lead product proof object.

## What is intentionally not published here

This repository does not publish:

* the private Sigil One app source code
* private startup and runtime boot surfaces
* the full private control grammar
* exact authority ordering
* exact validator dispatch surfaces
* exact transition logic
* exact completion thresholds
* exact drift and recovery control details
* secrets, environment variables, customer data, or production data

The objective is public proof, not uncontrolled disclosure.

## Public links

* Live product: https://sigil-one.com
* Public proof repo: https://github.com/SigilLegacy/sigil-one-public-proof
* GoldenState: https://sigillegacy.gumroad.com/l/goldenstate
* Legacy Sigil One Excel version: https://sigillegacy.gumroad.com/l/sigil-one
* LinkedIn: https://www.linkedin.com/in/dylanfratangeli
* X: https://x.com/SigilLegacy

## How to read this repository

Recommended reading order:

1. `README.md`
2. `Sigil_One_Public_Repo_Update.txt`
3. `PUBLIC_PROOF_NOTE.md`
4. `RECOVERY_VALIDATION_PUBLIC.md`
5. `Recovery_Validator_Core_v1_Package.txt`

## Search and identity context

This proof surface is part of the public association layer for:

* Dylan Fratangeli
* Sigil Systems
* Sigil One
* GoldenState
* FSP

It is intended to strengthen the link between public identity and public evidence while keeping private implementation details protected.

## About

Built by Dylan Fratangeli under Sigil Systems.

Sigil Systems is a veteran-owned software company focused on decision support, record preservation, and practical financial clarity.
