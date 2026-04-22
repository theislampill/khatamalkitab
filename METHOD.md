# Method

## Purpose
This repository does not treat "Muhammad in the Bible" as one undifferentiated claim. It breaks the topic into verse-level, range-level, cluster-level, convergence-level, and cumulative units so that each page can do the kind of argumentative work appropriate to its level.

The method is disciplined, but its public-facing goal is constructive presentation. A reader should be able to see what each page contributes, why it contributes it, and how it strengthens the larger thesis.

## Non-Negotiable Commitments
### 1. Build the case from the smallest justified unit
A verse should do verse work. A local range should do passage work. A cluster should do cluster work. A convergence should do genuinely convergent work. The final synthesis should gather force rather than rehearse fragments.

### 2. Present positive force before objections
Every public-facing page should lead with what the passage, cluster, or convergence contributes. Objection notes remain important, but they are secondary and should clarify limits rather than govern the page.

### 3. Preserve rank
The method distinguishes:

- direct anchors
- supporting constraints
- control nodes
- dependent syntheses
- corroborative lines

This prevents weak or review-heavy material from silently taking the place of stronger lines.

### 4. Prefer convergence over isolated proof-texting
The repository is strongest when different lines add different constraints. Repetition does not count as convergence. A later page should answer a specific question the earlier page could not answer by itself.

### 5. Keep inference boundaries visible without making them the voice
The repository still uses source-status markers:

- `[anchored]`
- `[synthesis]`
- `[inference]`
- `[speculative]`
- `[control]`

These markers discipline the argument. They do not replace argument paragraphs.

## Page Architecture
### Verse Atoms
Use an atomic page when a single verse has standalone argumentative value or functions as a reusable control node.

An atom page should cover:

- the thesis-relevant claim
- the local reasoning
- the verse's local significance
- the verse's networked significance
- an optional brief objection note
- the contribution summary

An atom should not try to settle the whole thesis.

### Local Combined Passages
Use a combined page when nearby verses make one local movement that should be understood together before being promoted.

A combined page should show:

- why the passage belongs together
- what additional force appears at range level
- what the local movement establishes
- how the passage feeds higher-order clustering

### Cluster Pages
Use a cluster page when multiple passages do the same inferential job.

A cluster page should show:

- the cluster claim
- why the members belong together
- what distinct force the cluster adds
- how it differs from adjacent clusters
- how it supports convergence and cumulative synthesis

### Convergence Pages
Use a convergence page when distinct clusters reinforce one another.

A convergence page should show:

- the lines being combined
- the new force created by their combination
- why this is not redundancy
- what objections weaken at the convergent level

### Cumulative Synthesis
Use a cumulative page when the ranked architecture itself becomes the argument.

A cumulative page should show:

- the order of force
- the load-bearing versus corroborative distinction
- how the case accumulates
- why weaker lines do not govern the conclusion

## Constructive Order
Public-facing argument pages should normally follow this order:

1. thesis-relevant claim
2. reasoning
3. local significance
4. networked significance
5. optional objection note
6. contribution summary

This order may be adapted for control pages, but the page must still explain positively why the control matters.

## Passage Classification
Each thesis-relevant biblical passage can still be classified into one or more working roles:

- direct
- support
- control
- tentative

These roles guide rank. They do not determine tone.

## Probability Tiers
The repo continues to use research-style probability language:

- high-convergence
- medium-convergence
- tentative
- control

These labels describe current strength. They should not turn public pages into defensive summaries.

## Promotion Workflow
### 1. Extract
Identify every thesis-relevant biblical reference from working material.

### 2. Normalize
Normalize canon, book, chapter, and verse or range.

### 3. Classify
Assign roles such as direct, support, control, or tentative.

### 4. Promote narrowly
Create:

- the individual verse page
- the local combined page if needed
- the cluster page if the claim crosses passages
- the convergence page if another cluster adds a distinct constraint

### 5. Record
Update:

- `BIBLE_ARGUMENT_INDEX.md`
- `KHALAS.md`
- `PROJECT_THESIS_AND_STRUCTURE.md` or `METHOD.md` where the architecture changes materially
- `SORTING_AUDIT.md` when the corpus-routing picture changes materially

### 6. Place objections at the right level
Objection handling should match the level of the claim:

- local-context objections at verse or passage level
- cluster rival readings at cluster level
- redundancy versus reinforcement at convergence level
- whole-case rival synthesis at cumulative level

## Corpus Integration Rule
The local corpus under `input/` is working material only.

Its job is to supply discovery, classification, comparison, and routing pressure.

It is not:

- public repo content
- a quote dump
- a provenance apparatus
- a substitute for structured passage pages

The repository should present source-neutral argument structure and disciplined prose, not raw extraction.

## Contributor Standard
A contribution is method-complete when it:

- promotes the narrowest justified verse pages
- adds the needed combined passage page where local coherence matters
- adds or updates the required cluster page
- adds or updates the required convergence page where distinct lines reinforce each other
- updates `KHALAS.md`
- updates `BIBLE_ARGUMENT_INDEX.md`
- keeps the prose constructive, developed, and thesis-serving
- does not copy working material into the repo
