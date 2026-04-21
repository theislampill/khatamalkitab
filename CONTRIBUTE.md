# Contribute

## Who This Is For
This project welcomes pull requests from people who:

- have written their own paper, article, or project on Muhammad in the Bible
- noticed a passage, objection, or cluster missing from the current tree
- want to improve a verse page, combined page, or higher-order argument page
- want to strengthen the methodological honesty of the repository

## Core Contribution Rule
Do not use the repository as a dump of source transcriptions.

Contributions should distill, classify, and cross-link. They should not paste large raw excerpts from working corpus material into repo pages.

## What A Good Contribution Looks Like
### If you add or expand a verse-level finding
You should:

- add or update the relevant atomic verse page
- add or update the local combined range page if the verse depends on nearby context
- add or update the argument-cluster page if the claim only makes sense cumulatively

### If you add a new argument cluster
You should:

- create or update the `arguments/<slug>/summary.md` page
- explicitly list the passage pages it depends on
- distinguish the main claim from objections and alternate readings

### If you add a new finding from another corpus
You should:

- place it in the Bible spine at the narrowest justified verse or range
- update `KHALAS.md`
- update `BIBLE_ARGUMENT_INDEX.md`
- update `SORTING_AUDIT.md` if your contribution changes the corpus-sorting picture materially

## Per-Verse Requirement
If a passage is promoted as a real repository finding, each individual verse in the promoted range must have its own `summary.md`.

Do not stop at a chapter page or a broad range page if the verses are being asked to do distinct argumentative work.

## Required Pull Request Updates
Every substantive PR should review whether it needs changes in:

- `bible/...` verse pages
- local combined passage pages
- `arguments/...` cluster pages
- `KHALAS.md`
- `BIBLE_ARGUMENT_INDEX.md`
- `PROJECT_THESIS_AND_STRUCTURE.md`
- `METHOD.md`

## What To Avoid
- raw corpus quotation dumps
- argument pages that merely restate one source's wording
- forcing a multi-verse argument into one atomic verse page
- assigning a verse more weight than the passage can reasonably bear
- hiding speculative claims inside confident prose
- adding source provenance chains to public-facing repo pages

## Suggested PR Checklist
- The claim is placed at the narrowest justified verse or range.
- Every promoted verse in the range has its own page.
- The combined page exists where local context is necessary.
- The cross-passage page exists where cumulative reasoning is necessary.
- `KHALAS.md` reflects the new or revised finding.
- `BIBLE_ARGUMENT_INDEX.md` routes to the new pages.
- The contribution does not copy working-material files into the repo.

## Review Standard
The best PRs make the repository easier to audit.

That means a reviewer should be able to answer, quickly:

- what passage is doing the work
- what kind of work it is doing
- what other pages it depends on
- how strong or tentative the current claim is
