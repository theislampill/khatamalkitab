# khatamalkitab: The Prophet (peace be upon him) Fulfilled the Biblical Expectation

> Collaborative research presenting the cumulative case that the Prophet (peace be upon him) fulfills biblical prophetic expectation; organised by verse pages, passage pages, cluster pages, convergence pages, and cumulative synthesis.

## Table of Contents
- [Overview](#overview)
- [Project Status](#project-status)
- [Corpus Integration](#corpus-integration)
- [Repository Structure](#repository-structure)
- [Method](#method)
- [Current Architecture](#current-architecture)
- [Working Material Policy](#working-material-policy)
- [Contributing](#contributing)

## Overview
This repository is a structured research workspace for presenting and refining the case that the Prophet (peace be upon him) fulfills the biblical prophetic expectation. Its argument is cumulative by design: the strongest pages do not force one verse to prove everything, but instead let local findings rise into coherent passages, clusters, convergences, and a final synthesis.

The goal is not merely to catalogue candidate texts. The goal is to show, clearly and constructively, what each passage contributes, why it matters, and how the larger case accumulates.

## Project Status
The repository's main public route is now in place and can be read as a coherent cumulative case. Remaining work is incremental: bounded coverage expansion, residue cleanup, and editorial refinement. That does not retreat from the governing thesis. It means the repo can now be used as a public-facing argument project while still allowing disciplined improvement at the right level.

## Corpus Integration
The local corpus is integrated into the repository by distillation, classification, and routing, not by republication.

In practice that means:

- working materials are read from local `input/` files
- thesis-relevant findings are normalized into `bible/<canon>/<book>/ch<chapter>/v<verse>/`
- adjacent verses that function together also receive local combined pages
- recurring inferential families are routed into `arguments/`
- distinct reinforcing families are promoted into `convergences/`
- cumulative synthesis is gathered and integrated in `KHALAS.md`

This keeps the project source-neutral and public-facing while still preserving the reasoning pressure discovered in the working corpus.

## Repository Structure
- `bible/ot/`, `bible/nt/`, `bible/apoc/`: canon spine
- `bible/<canon>/<book>/ch<chapter>/v<verse>/summary.md`: atomic verse pages
- `bible/<canon>/<book>/ch<chapter>/v<start>-<end>/summary.md`: local combined passage pages
- `arguments/`: higher-order cluster pages
- `convergences/`: higher-order convergence pages
- `BIBLE_ARGUMENT_INDEX.md`: routing index of current page nodes
- `PROJECT_THESIS_AND_STRUCTURE.md`: project thesis and architecture
- `SORTING_AUDIT.md`: corpus sorting audit
- `KHALAS.md`: integrative cumulative synthesis page
- `METHOD.md`: methodological framework
- `CONTRIBUTE.md`: contribution expectations

## Method
The working method is described in [METHOD.md](METHOD.md).

In short:

- promote the narrowest justified verse or range
- keep direct anchors, support, controls, dependent syntheses, and corroborative lines distinct
- present positive force before objections
- use convergence rather than isolated proof-texting
- preserve serious rival readings without letting them dominate framing
- keep cumulative synthesis ranked and disciplined

## Current Architecture
The repo's current architecture is strongest when read in this order:

1. `KHALAS.md` as the capstone essay that gathers the route into one continuous argument
2. primary profile clusters such as Prophet Like Moses and Paraclete
3. the expectation, narrowing, and control families that make the direct profiles historically intelligible
4. convergence pages that show how distinct lines reinforce one another
5. the Bible spine for local verse and passage support beneath those higher-order pages

This lets a reader either begin with the full thesis essay in `KHALAS.md` and drill downward into the supporting nodes, or begin with local pages and watch the case accumulate upward without flattening the argument into one proof text or one summary page.

## Working Material Policy
Files under `input/` are working material only.

They are used to:

- identify passages
- compare argument patterns
- decide routing
- refine the repo's architecture

They are not repository deliverables and should not be copied into public-facing pages as raw transcription content.

## Contributing
Contribution expectations are in [CONTRIBUTE.md](CONTRIBUTE.md).

The best contributions strengthen the constructive case at the correct level: verse, passage, cluster, convergence, or cumulative synthesis.
