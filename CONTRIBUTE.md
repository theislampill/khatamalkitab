# Contribute

## Who This Is For
This project welcomes pull requests from people who:

- have written their own paper, article, or project on Muhammad in the Bible
- noticed a passage, objection, cluster, or convergence missing from the current tree
- want to improve a verse page, combined page, cluster page, convergence page, or cumulative synthesis page
- want to strengthen the repo's clarity, routing, and constructive force

## Core Contribution Rule
Do not use the repository as a dump of source transcriptions.

Contributions should distill, classify, cross-link, and develop the argument. They should not paste large raw excerpts from working corpus material into repo pages.

## What A Good Contribution Looks Like
### If you add or expand a verse-level finding
You should:

- add or update the relevant atomic verse page
- add or update the local combined range page if the verse depends on nearby context
- add or update the linked cluster page if the claim only makes sense cumulatively

### If you add or expand a cluster
You should:

- create or update the relevant `arguments/<slug>/summary.md`
- show why the clustered passages belong together
- explain what distinct force the cluster adds
- identify any linked convergence pages it supports

### If you add or expand a convergence
You should:

- create or update the relevant `convergences/<slug>/summary.md`
- identify the distinct lines being converged
- explain what new force emerges from the combination
- make clear why the result is not redundancy

### If you add a new finding from another corpus
You should:

- place it in the Bible spine at the narrowest justified verse or range
- update `KHALAS.md`
- update `BIBLE_ARGUMENT_INDEX.md`
- update `SORTING_AUDIT.md` if your contribution changes the corpus-routing picture materially

## Per-Verse Requirement
If a passage is promoted as a real repository finding, each individual verse in the promoted range must have its own `summary.md`.

Do not stop at a chapter page or a broad range page if the verses are being asked to do distinct argumentative work.

## Required Pull Request Updates
Every substantive PR should review whether it needs changes in:

- `bible/...` verse pages
- local combined passage pages
- `arguments/...` cluster pages
- `convergences/...` convergence pages
- `KHALAS.md`
- `BIBLE_ARGUMENT_INDEX.md`
- `PROJECT_THESIS_AND_STRUCTURE.md`
- `METHOD.md`

## Writing Standard
Public-facing pages should:

- lead with the positive contribution
- explain the reasoning in full sentences
- show local and networked significance
- keep objection notes brief and subordinate
- strengthen the thesis at the page's proper level

## What To Avoid
- raw corpus quotation dumps
- argument pages that merely restate one source's wording
- fault-first framing
- pages built as metadata checklists instead of argumentative prose
- forcing a multi-verse argument into one atomic verse page
- assigning a verse more weight than the passage can reasonably bear
- hiding speculative claims inside confident prose
- adding source provenance chains to public-facing repo pages

## Suggested PR Checklist
- The claim is placed at the narrowest justified verse or range.
- Every promoted verse in the range has its own page.
- The combined page exists where local context is necessary.
- The cluster page exists where cumulative reasoning is necessary.
- The convergence page exists where distinct lines genuinely reinforce one another.
- `KHALAS.md` reflects the new or revised finding.
- `BIBLE_ARGUMENT_INDEX.md` routes to the new pages.
- The contribution strengthens the constructive case instead of sounding like a skeptical audit.
- The contribution does not copy working-material files into the repo.

## Review Standard
The best PRs make the repository easier to follow, more persuasive, and more coherent across levels.

A reviewer should be able to answer:

- what this page contributes
- why it contributes that
- what larger structure it supports
- what level of confidence the page should carry
