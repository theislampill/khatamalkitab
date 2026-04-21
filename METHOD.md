# Method

## Purpose
This repository does not treat "Muhammad in the Bible" as one undifferentiated claim. It breaks the topic into verse-level, range-level, and cross-passage units so each argument can be reviewed at the smallest justified scale.

## Epistemic Grounding
This method is informed by the local epistemic framework in `input/daee-epistemics/SKILL.md`, especially its emphasis on:

- diagnose before rebutting
- keep the claim-type clean
- prefer convergence over isolated proof-fragments
- mark where inference begins
- audit coverage instead of assuming it

In repo terms, that means we do not simply collect proof texts. We classify what kind of claim a passage is carrying, how much inferential weight it can bear, and what other passages it depends on.

This file is grounded against the daee-epistemics skill, but it is not a duplicate of it. The skill is a general epistemic and diagnostic architecture. This repository method adapts those principles to a collaborative text-research workflow around biblical passages, prophetic argument clusters, and corpus-level convergence.

## Non-Negotiable Commitments
### 1. Diagnose before promoting
A passage is not promoted into the repo merely because it appears in a source text. We first ask:

- is it being used as a direct prophecy claim?
- as a supporting identity or geography claim?
- as a control passage against an objection or alternate reading?
- or only as incidental quotation noise?

Only then do we route it into the Bible tree.

### 2. Use the narrowest justified unit
If one verse carries reusable argumentative value, it gets its own page.

If a local range is required to make sense of the claim, the range gets its own combined page.

If the claim only becomes persuasive when multiple distant passages are read together, it gets an argument-cluster page under `arguments/`.

### 3. Every promoted verse gets its own page
If a passage is promoted into the repository as a real finding, each individual verse in the promoted range must have its own `summary.md`.

This avoids two common failures:

- hiding difficult verses inside broad chapter summaries
- forcing collaborators to edit only at the range level

### 4. Convergence matters more than proof-text isolation
Following the convergence discipline reflected in the daee-epistemics material, the repository privileges non-collusive convergence:

- repeated appearance across multiple corpus works
- recurrence across multiple argument clusters
- agreement between direct claim passages and supporting geography / lineage / reception passages
- stable fit without excessive lexical rescue or forced reassignment

### 5. Inference boundaries must stay visible
The repository distinguishes four source-status levels, adapted from the skill's inference-boundary discipline:

- `[anchored]`: directly promoted from corpus findings into a passage or range page
- `[synthesis]`: requires combining multiple promoted pages without adding a new thesis
- `[inference]`: a reasoned extension beyond what any one passage page states
- `[speculative]`: interesting but too thin or too unstable to govern the project

These markers do not need to appear in every verse page, but they govern `KHALAS.md`, argument clusters, and contributor decisions.

## Passage Classification
Each thesis-relevant biblical passage is classified into one of four working roles.

### Direct
The passage is used as a candidate prophecy, announcement, or strong anticipatory description.

Examples:

- Deuteronomy 18:15-22
- John 16:7-15
- Isaiah 42:1-21

### Support
The passage does not by itself identify Muhammad, but it stabilizes lineage, geography, law, nationhood, or scope.

Examples:

- Genesis 17:20
- Genesis 25:13
- Ezekiel 27:21

### Control
The passage is used to test or challenge a competing reading.

Examples:

- Deuteronomy 34:10
- John 7:39
- John 20:22
- 1 John 4:1-6

### Tentative
The passage appears in the corpus and may matter, but its current assignment is thin, highly lexical, or still too disputed to carry major project weight on its own.

## Probability Tiers
The repo uses probability language in a research sense, not as a mathematical theorem.

### High-convergence
Use this when:

- the passage recurs across multiple working files
- its role is stable across those files
- it connects cleanly to other promoted passages
- it does not rely mainly on a fragile lexical or geographic leap

### Medium-convergence
Use this when:

- the passage is clearly thesis-relevant
- but it depends more heavily on a supporting chain
- or is concentrated in fewer works
- or carries a larger interpretive step

### Tentative
Use this when:

- the passage is real corpus material
- but verse assignment, lexical argument, or claimed fulfillment remains unstable

### Control
Use this when the verse helps govern objections, alternate readings, or internal consistency tests rather than serving as the main prophecy claim.

## Promotion Workflow
### 1. Extract
Identify every thesis-relevant biblical reference from the working corpus.

### 2. Normalize
Normalize canon, book slug, chapter, and verse or range.

### 3. Classify
Assign the passage one or more roles: direct, support, control, tentative.

### 4. Promote narrowly
Create:

- the individual verse page
- the local combined page if needed
- the higher-order argument page if the claim crosses passages

### 5. Record
Update:

- `BIBLE_ARGUMENT_INDEX.md`
- `KHALAS.md`
- `SORTING_AUDIT.md` when the corpus-routing picture changes materially

### 6. State objections
Every major combined or argument page should distinguish:

- what the passage is being used to argue
- what the main alternate readings are
- what related clusters it depends on

## Corpus Integration Rule
The local corpus under `input/` is working material only.

Its job is to supply discovery, classification, comparison, and routing pressure.

It is not:

- public repo content
- a quote dump
- a provenance apparatus
- a substitute for structured passage pages

The repository should show the distilled argumentative structure that the corpus points toward, not the raw corpus itself.

## Contributor Standard
A contribution is method-complete when it:

- promotes the narrowest justified verse pages
- adds or updates the needed combined range page
- adds or updates any required argument cluster
- updates `KHALAS.md`
- updates `BIBLE_ARGUMENT_INDEX.md`
- does not dump raw source corpus into the repo
