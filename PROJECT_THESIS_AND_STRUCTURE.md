# Project Thesis and Structure

## Thesis
This repository is organized to present, test, and develop the cumulative case that the Prophet (peace be upon him) fulfills the biblical prophetic expectation. Its public-facing pages are meant to help a reader move from local passage force, to coherent passage groups, to higher-order clusters, to true convergence, and finally to cumulative judgment.

The project therefore does not ask one verse to carry the entire thesis. It builds a ranked case in which direct profile, candidate-field narrowing, convergence, and cumulative synthesis each do their own kind of work, and in which `KHALAS.md` serves as the capstone public essay that gathers those layers into one continuous argument.

## Governing Epistemic Method
The repository follows a disciplined but constructive method:

- preserve source-status markers such as `[anchored]`, `[synthesis]`, `[inference]`, `[speculative]`, and `[control]`
- distinguish direct anchors, supporting constraints, control material, dependent syntheses, and corroborative lines
- present the positive argument before any objection note
- prefer convergence of distinct constraints over isolated proof-texting
- keep objections visible but subordinate
- downgrade thin or lexical material instead of inflating it
- preserve rank so that primary lines, secondary lines, controls, and corroborative lines are not silently mixed

## Bible Spine
The base structure follows the canon/book/chapter/verse spine:

- `bible/ot/`
- `bible/nt/`
- `bible/apoc/`

Within each canon, use normalized lowercase book slugs and chapter / verse folders:

- `bible/<canon>/<book>/`
- `bible/<canon>/<book>/ch<chapter>/`
- `bible/<canon>/<book>/ch<chapter>/v<verse>/`
- `bible/<canon>/<book>/ch<chapter>/v<start>-<end>/`

Examples:

- `bible/nt/john/ch14/v26/summary.md`
- `bible/nt/john/ch16/v7-13/summary.md`
- `bible/ot/deuteronomy/ch18/v18-19/summary.md`

## Page Types
### Atomic Passage Pages
Use an atomic page when a single verse has reusable argumentative value, whether as a direct anchor, a supporting constraint, or a control node.

Each atomic page should explain:

- what the verse contributes to the thesis
- why that inference is warranted at verse level
- what the verse establishes locally
- how the verse strengthens a linked passage, cluster, or convergence
- where a brief objection note is useful
- how the verse strengthens the larger case without pretending to settle it by itself

### Local Combined Passage Pages
Use a combined page when nearby verses form one coherent local movement and should be read together before the argument is promoted upward.

Each combined page should explain:

- why the range belongs together as one local unit
- what additional force the grouped passage has beyond the separate atoms
- how that local movement feeds the next argumentative layer
- what objection note matters at passage level rather than atom level

### Higher-Order Cluster Pages
Use cluster pages when multiple passages perform the same inferential job and need to be read as one argumentative family.

Each cluster page should explain:

- the cluster claim
- why those passages belong together
- what distinct constraint the cluster adds
- how the cluster differs from adjacent clusters
- how it supports convergence and cumulative synthesis
- what objection note matters at cluster level

### Convergence Pages
Use convergence pages when distinct clusters reinforce one another and create a stronger result together than any one cluster could create alone.

Each convergence page should explain:

- which lines are being converged
- what new force emerges from their combination
- why this is convergence rather than redundancy
- which objections weaken only when the combined structure is seen
- how the convergence advances the cumulative case

### Cumulative Synthesis Pages
Use cumulative pages when several convergences and ranked clusters must be gathered into one reader-facing argument.

Each cumulative page should explain:

- the order of argument force
- the load-bearing versus corroborative distinction
- how the case accumulates across levels
- why accumulation matters here
- what remaining objections are real but subordinate
- how the total structure supports the final thesis

## Constructive Order
Public-facing argument pages should normally follow this order:

1. thesis-relevant claim
2. reasoning
3. local significance
4. networked significance
5. limited objection note where useful
6. contribution summary

This order keeps the thesis visible while preserving discipline.

## Routing Rules
- Use the smallest justified passage unit first.
- Promote a combined page only when adjacent verses function together.
- Promote a cluster only when the grouped passages do the same inferential work.
- Promote a convergence only when another cluster adds a distinct constraint.
- Keep control passages distinct from direct prophecy claims.
- Mark uncertain claims as tentative or not promoted.
- Do not treat prior page existence as proof that the route is valid.

## Working-Material Rule
The files under `input/md/` are local working material only. They are used for classification, synthesis, and routing, but they are not repository deliverables.

That means:

- do not quote-dump `input/md/*.md` into the repo
- do not build public-facing citation apparatus from those files
- do not treat those files as canonical sources inside the repo
- do not move those files into the Bible spine

Repo pages should present source-neutral argument structure, not raw corpus transcription.

## Current Architecture Families
The current repo is organized around:

- primary profile clusters
- candidate-field narrowing clusters
- anti-closure and control clusters
- dependent bridge clusters
- convergence pages
- cumulative synthesis pages

The strongest current cluster families include:

- [Prophet Like Moses](arguments/prophet-like-moses/summary.md)
- [Paraclete](arguments/paraclete/summary.md)
- [Arabian Servant And Kedar](arguments/arabian-servant-and-kedar/summary.md)
- [Ishmaelite Line And Brethren](arguments/ishmaelite-line-and-brethren/summary.md)
- [Paran And Arabia](arguments/paran-and-arabia/summary.md)
- [Live Prophetic Expectation](arguments/live-prophetic-expectation/summary.md)
- [Law Continuity Control](arguments/law-continuity-control/summary.md)

## Governance Files
- `METHOD.md` explains the research method used for promotion, clustering, convergence, and cumulative synthesis.
- `KHALAS.md` presents the integrative cumulative case and final thesis judgment.
- `SORTING_AUDIT.md` records how the working corpus was sorted.
- `BIBLE_ARGUMENT_INDEX.md` routes passage pages, cluster pages, and convergence pages.
