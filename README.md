# khatamalkitab: The Prophet ﷺ Fulfilled the Biblical Expectation

> Collaborative research presenting the cumulative, decisive case that the Prophet ﷺ fulfills the Biblical prophetic expectation, organised by canon, book, chapter, verse, and argument cluster.

## Table of Contents
- [Overview](#overview)
- [Project Status](#project-status)
- [Corpus Integration](#corpus-integration)
- [Repository Structure](#repository-structure)
- [Method](#method)
- [Current Findings](#current-findings)
- [Working Material Policy](#working-material-policy)
- [Contributing](#contributing)

## Overview
This repository is for collaborative research on the Prophet ﷺ in the Bible. Its governing conclusion is that the Prophet ﷺ fulfilled the Biblical prophetic expectation, and that this conclusion is properly known, conclusive, and decisive when the passage families are read cumulatively.

The repository is structured so contributors can work at verse level, local passage level, and higher-order argument-cluster level without flattening the thesis into one document.

The repo is intentionally not a transcription archive. It is a structured research workspace.

## Project Status
This project is vibe-coded and actively in progress. Treat the current structure and findings as reviewable scaffolding, not final editorial authority.

That status concerns the repository's organization, coverage, and presentation. It is not a retreat from the governing thesis that the Prophet ﷺ decisively fulfills the Biblical expectation.

Contributors and maintainers are welcome, especially people who can improve passage routing, tighten argument clusters, review methodology, or bring careful prior research into the per-verse structure.

## Corpus Integration
The local corpus is integrated into the repository by distillation, classification, and routing, not by republication.

In practice that means:

- working materials are read from local `input/` files
- thesis-relevant findings are normalized into `bible/<canon>/<book>/ch<chapter>/v<verse>/`
- adjacent verses that function together also get local combined pages
- multi-passage claims are routed into `arguments/`
- findings status and methodological notes are tracked in top-level docs

The repository exposes the substance of corpus integration through the page structure itself:

- verse pages for atomic discussion
- range pages for local coherence
- argument pages for cumulative reasoning
- `KHALAS.md` for the current findings ledger
- `METHOD.md` for the governing research method

This keeps the project transparent for collaborators while avoiding source-dump behavior. Explicit citations of corpus working materials should not be presented in public-facing pages; contributors should preserve the substance through structured routing and synthesis.

## Repository Structure
- `bible/ot/`, `bible/nt/`, `bible/apoc/`: canon spine
- `bible/<canon>/<book>/ch<chapter>/v<verse>/summary.md`: atomic verse pages
- `bible/<canon>/<book>/ch<chapter>/v<start>-<end>/summary.md`: local combined passage pages
- `arguments/`: higher-order cross-passage synthesis pages
- `BIBLE_ARGUMENT_INDEX.md`: routing index of current page nodes
- `PROJECT_THESIS_AND_STRUCTURE.md`: project thesis and structure
- `SORTING_AUDIT.md`: corpus sorting audit
- `KHALAS.md`: current findings ledger
- `METHOD.md`: methodological framework
- `CONTRIBUTE.md`: pull request expectations

## Method
The working method is described in [METHOD.md](METHOD.md).

In short:

- diagnose the role of a passage before promoting it
- promote the narrowest justified verse or range
- keep direct claims, support claims, and control passages distinct
- use convergence rather than isolated proof-texting
- mark inference boundaries honestly
- preserve serious alternate readings and failure modes

## Current Findings
The current findings ledger is in [KHALAS.md](KHALAS.md).

The present repository structure includes verse-level pages, combined local range pages, and argument-cluster pages for:

- Prophet Like Moses
- Paraclete
- Messenger Before Arrival
- Ishmaelite Line And Brethren
- Paran And Arabia
- Arabian Servant And Kedar
- Live Prophetic Expectation
- Law Continuity Control
- Kingdom Transfer
- Unlettered Prophet
- Baca And Pilgrimage
- Mahmad And Praised-One
- related control and synthesis clusters

## Working Material Policy
Files under `input/` are working material only.

They are used to:

- identify passages
- compare argument patterns
- decide routing
- expand or narrow the repository structure

They are not repository deliverables and should not be copied into the public repo structure as raw transcription content.

## Contributing
Contribution expectations are in [CONTRIBUTE.md](CONTRIBUTE.md).

If you are opening a PR based on your own paper, notes, reading, or missing passages you noticed in another corpus, start there first.

