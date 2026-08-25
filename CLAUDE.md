# Media Business Research — Working Rules

Read [PROJECT.md](PROJECT.md) for what this project is and why.
Read [DECISIONS.md](DECISIONS.md) and [LEARNINGS.md](LEARNINGS.md) at the start of every
session — they are the accumulated state of the project and are kept short on purpose.

## File structure

```
.
├── PROJECT.md              # Goals, scope, phases. Changes rarely.
├── DECISIONS.md            # Research-derived decisions. Append-only log.
├── LEARNINGS.md            # Durable facts and principles worth always keeping in mind.
├── resources/
│   ├── INDEX.md            # Every resource considered or consumed. One row each.
│   └── summaries/          # One file per consumed resource: <slug>.md
└── research/               # Phase synthesis — the actual analytical output.
    ├── 01-formats.md
    ├── 02-monetization.md
    ├── 03-case-studies.md
    ├── 04-niches.md
    └── 05-strategy.md
```

Do not create new top-level directories or ad-hoc files without asking. If something
doesn't fit the structure, that's worth a conversation, not a new folder.

## The four kinds of file, and what belongs in each

**`resources/INDEX.md`** — the master list. Every resource gets a row when it's identified,
before it's read. Columns: title, author/source, type, link, status, trust, summary link,
date consumed. Status is `queued` / `consumed` / `skipped`. Trust is `high` / `medium` /
`low` with a word on why — a lot of creator-economy material is marketing for a course, and
that has to be visible at a glance.

**`resources/summaries/<slug>.md`** — one per consumed resource. The slug matches the INDEX
row exactly so the two never drift. This is where detail and specific numbers live. Do not
compress prematurely; the whole point is that the detail is recoverable later without
re-reading the source. Follow the template in the file below.

**`research/NN-*.md`** — synthesis across many resources for one phase. This is where
patterns get drawn out, sources get compared, and disagreements between sources get
resolved or noted as unresolved. Cite the summary files it draws on.

**`LEARNINGS.md`** — the small set of durable, load-bearing facts. Something earns a place
here only if it should shape decisions across the whole project. Every entry links to the
summary or research file that backs it. If an entry is only relevant inside one phase, it
belongs in that phase's research file instead.

**`DECISIONS.md`** — decisions that came *out of* the research. Every entry names the finding
that drove it. Project scope and setup choices do not belong here — those live in PROJECT.md;
file and workflow conventions live in this file. The test: if the decision could have been
made on day one without reading anything, it's in the wrong file. Never rewrite history:
superseding a decision means adding a new entry that references the old one and marking the
old one superseded.

## Conventions

- **Numbers need sources.** Any specific figure — RPM, conversion rate, subscriber count,
  revenue — carries a citation to the resource it came from. An uncited number is a guess
  and should be labeled as one.
- **Record disagreement.** When two sources conflict, say so rather than silently picking
  one. Conflicts are often the most informative part of the research.
- **Note survivorship bias.** Case studies skew heavily toward winners. When a claim rests
  only on successes, flag that the failure base rate is unknown.
- **Apply the capacity filter.** 5-10 hrs/week is a hard constraint. Flag any strategy or
  tactic that quietly assumes more.
- **Dates are absolute.** Write "March 2026", never "last month". Creator-economy data goes
  stale fast, so note how old a figure is.
- **Keep the distilled files short.** DECISIONS.md and LEARNINGS.md are read every session.
  If either stops being skimmable, prune it — push detail down into research/ or summaries/.

## Resource summary template

```markdown
# <Title>

- **Source:** <author / channel / publication>
- **Type:** <article | video | podcast | book | course | thread | interview>
- **Link:** <url>
- **Consumed:** <YYYY-MM-DD>
- **Trust:** <high | medium | low> — <why>

## What it claims
<The core argument or content, in a few lines.>

## Specific numbers and facts
<Figures worth keeping, each with any context the source gave.>

## What's useful for this project
<Direct implications. Which phase it feeds.>

## Caveats
<Bias, age of data, missing evidence, conflicts of interest, what it's selling.>
```

## Git

Commit after each meaningful unit of work — a resource summarized, a phase synthesis
advanced, a decision recorded. Commit messages should say what was learned or decided,
not just which file changed.
