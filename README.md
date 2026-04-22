# khatamalkitab: The Prophet (peace be upon him) Fulfilled the Biblical Expectation

> Collaborative research presenting the cumulative case that the Prophet (peace be upon him) fulfills the biblical prophetic expectation through verse pages, passage pages, cluster pages, convergence pages, and cumulative synthesis.

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
The repository remains actively in progress. That status concerns coverage, routing, and editorial refinement. It does not retreat from the governing thesis. Instead, it means the project is being shaped into a clearer and more persuasive architecture so contributors can strengthen the case at the right level.

## Corpus Integration
The local corpus is integrated into the repository by distillation, classification, and routing, not by republication.

In practice that means:

- working materials are read from local `input/` files
- thesis-relevant findings are normalized into `bible/<canon>/<book>/ch<chapter>/v<verse>/`
- adjacent verses that function together also receive local combined pages
- recurring inferential families are routed into `arguments/`
- distinct reinforcing families are promoted into `convergences/`
- cumulative synthesis is gathered in `KHALAS.md`

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
- `KHALAS.md`: cumulative findings ledger and final synthesis
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

1. primary profile clusters such as Prophet Like Moses and Paraclete
2. candidate-field narrowing clusters such as Arabian Servant And Kedar, Ishmaelite Line And Brethren, and Paran And Arabia
3. anti-closure and control clusters such as Live Prophetic Expectation and Law Continuity Control
4. convergence pages that show how distinct lines reinforce one another
5. `KHALAS.md` as the cumulative synthesis

This lets the reader move from local argument to broader force without flattening the case into one proof text or one summary page.

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
