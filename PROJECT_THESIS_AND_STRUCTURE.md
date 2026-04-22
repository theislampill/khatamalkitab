# Project Thesis and Structure

## Thesis
This repository is organized for collaborative research on the claim that the Prophet ﷺ fulfills the biblical prophetic expectation. The structure is designed to let a reader move from verse, to local passage, to cross-passage cluster, to cumulative synthesis without treating the repository as a transcription archive.

The project conclusion is cumulative: individual verses are not forced to carry the whole thesis. Strong claims must arise through classified convergence across promoted passage nodes.

## Governing Epistemic Method
The repository follows the daee-epistemics protocol for public-facing claims:

- mark source status: `[anchored]`, `[synthesis]`, `[inference]`, or `[speculative]`
- distinguish evidence, interpretation, synthesis, and rhetorical framing
- prefer multi-passage convergence over isolated proof texts
- keep alternate readings visible
- downgrade weak or lexical claims instead of inflating them
- record failure modes where an argument can be overused

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
Use an atomic page when a single verse has standalone argumentative value or functions as a reusable control.

Each atomic page should include:

- what is being argued
- epistemic classification
- anchored findings
- synthesis role
- inference boundary
- alternate readings
- dependency links
- failure modes

### Local Combined Passage Pages
Use a combined page when nearby verses form one coherent local argument and should not be duplicated inside every atomic page.

Promoted combined ranges must also have individual verse pages for each verse inside the range.

### Higher-Order Cross-Passage Argument Pages
Use argument pages when reasoning depends on multiple passages, especially across books or testaments.

Each argument page should include:

- central thesis
- anchored passages
- supporting passages
- dependency graph
- competing interpretations
- inference boundary
- failure modes
- epistemic strength summary

## Routing Rules
- Use the smallest justified passage unit first.
- Promote a combined page only when adjacent verses function together.
- Promote a cross-passage cluster only after convergence is confirmed.
- Keep control passages distinct from direct prophecy claims.
- Mark uncertain claims as tentative or not promoted.
- Do not treat prior page existence as proof that the route is valid.

## Working-Material Rule
The files under `input/` are local working material only. They are used for classification, synthesis, and routing, but they are not repository deliverables.

That means:

- do not quote-dump `input/*.md` into the repo
- do not build public-facing citation apparatus from those files
- do not treat those files as canonical sources inside the repo
- do not move those files into the Bible spine

Repo pages should distill arguments, record uncertainties, and link related nodes. They should not mirror raw transcription text.

## Current Cluster Families
The full corpus sweep currently supports these promoted families:

- [Prophet Like Moses](arguments/prophet-like-moses/summary.md)
- [Paraclete](arguments/paraclete/summary.md)
- [Paraclete And Subordination](arguments/paraclete-and-subordination/summary.md)
- [Prophet Like Moses And Paraclete](arguments/prophet-like-moses-and-paraclete/summary.md)
- [Messenger Before Arrival](arguments/messenger-before-arrival/summary.md)
- [Live Prophetic Expectation](arguments/live-prophetic-expectation/summary.md)
- [Law Continuity Control](arguments/law-continuity-control/summary.md)
- [Ishmaelite Line And Brethren](arguments/ishmaelite-line-and-brethren/summary.md)
- [Paran And Arabia](arguments/paran-and-arabia/summary.md)
- [Arabian Servant And Kedar](arguments/arabian-servant-and-kedar/summary.md)
- [Unlettered Prophet](arguments/unlettered-prophet/summary.md)
- [Baca And Pilgrimage](arguments/baca-and-pilgrimage/summary.md)
- [Mahmad And Praised-One](arguments/mahmad-and-praised-one/summary.md)
- [Kingdom Transfer](arguments/kingdom-transfer/summary.md)

## Governance Files
- `METHOD.md` explains the research method used for promotion, convergence, and probability language.
- `KHALAS.md` records the current findings ledger and cumulative synthesis.
- `SORTING_AUDIT.md` records how the working corpus was sorted.
- `BIBLE_ARGUMENT_INDEX.md` routes passage pages and argument pages.

