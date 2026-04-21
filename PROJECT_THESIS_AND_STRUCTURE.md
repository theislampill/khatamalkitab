# Project Thesis and Structure

## Thesis
This repository is organized for collaborative research on the claim that biblical passages can be read as anticipations of the Prophet Muhammad. The repo is not a source dump. Its job is to break the thesis into reusable passage nodes and higher-order argument nodes so collaborators can refine, compare, and challenge claims without rewriting the whole case each time.

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
### Atomic passage pages
Use an atomic page when a single verse has standalone argumentative value and can be reused in more than one cluster.

Examples in this patch:

- `bible/ot/deuteronomy/ch18/v18/summary.md`
- `bible/ot/genesis/ch17/v20/summary.md`
- `bible/nt/john/ch16/v7/summary.md`

### Local combined passage pages
Use a combined page when a nearby verse range forms one coherent local argument and should not be split into duplicate mini-essays.

Promoted combined ranges should also have individual verse pages for each verse inside the range.

Examples in this patch:

- `bible/ot/deuteronomy/ch18/v18-19/summary.md`
- `bible/ot/isaiah/ch21/v13-17/summary.md`
- `bible/nt/john/ch16/v7-13/summary.md`

### Higher-order cross-passage argument pages
Use argument pages when the reasoning depends on multiple passages, often across books or across testaments. These pages synthesize a cluster and point back to the smaller passage nodes instead of swallowing them.

Examples in this patch:

- `arguments/prophet-like-moses/summary.md`
- `arguments/paraclete/summary.md`
- `arguments/paran-and-arabia/summary.md`

## Working-Material Rule
The files under `input/` are local working material only. They are used for classification, synthesis, and routing, but they are not repository deliverables.

That means:

- do not quote-dump `input/*.md` into the repo
- do not build public-facing citation apparatus from those files
- do not treat those files as canonical sources inside the repo
- do not move those files into the Bible spine

Repo pages should distill arguments, record uncertainties, and link related nodes. They should not mirror raw transcription text.

## Editorial Rules
- Prefer the narrowest justified passage assignment.
- Use combined range pages when the argument genuinely needs the range.
- Use argument-cluster pages when the reasoning crosses books or non-adjacent passages.
- Keep claim, objections, and related pages visibly separate.
- Reuse by linking instead of repeating the same content in multiple places.
- Mark uncertain assignments as tentative instead of forcing them into a stronger bucket.

## Current Initial Clusters
The reviewed working corpus most strongly converges on these families:

- Deuteronomy 18 and its reuse in John 1 and Acts 3
- John 14-16 as Paraclete material
- Isaiah 42 as the servant / Kedar cluster
- Isaiah 21, Deuteronomy 33, Habakkuk 3, and Genesis 21 as the Paran / Arabia cluster
- Genesis 16, Genesis 17, Genesis 21, and Ezekiel 27 as the Ishmaelite / Kedar identification cluster
- Isaiah 29 as an unlettered-prophet argument that needs more careful review than the core passages

This patch establishes those routes without pretending the structure is finished.

## Working Governance Files
- `METHOD.md` explains the research method used for promotion, convergence, and probability language.
- `KHALAS.md` records the current findings ledger and status of the main passage clusters.
