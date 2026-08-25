# Decisions

Decisions made **as a result of research** — where something we learned changed what we're
going to do. Each entry names the learning that drove it.

This is not for project setup or scope choices (those live in [PROJECT.md](PROJECT.md)) or
file/workflow conventions (those live in [CLAUDE.md](CLAUDE.md)). If a decision could have
been made on day one without reading anything, it doesn't belong here.

Append-only. Superseding a decision means adding a new entry that references the old one and
marking the old one **Superseded** — never edit or delete history.

Kept short by design; read at the start of every session.

---

_No research-derived decisions yet — research hasn't started._

---

## Format

```markdown
## D<n> — <Short, declarative statement of what we're doing>
**Date:** <YYYY-MM-DD> · **Status:** Active | Superseded by D<n>

<What was decided, in a line or two. Concrete enough to act on.>

**Driven by:** <The specific finding that prompted this, linked to
[LEARNINGS.md](LEARNINGS.md) or the research/summary file that backs it.>

**Rejected alternative:** <What we're not doing, and what it would have cost or gained.>

**Would change our mind:** <The observation or evidence that would reopen this.>
```

`Driven by` is the field that matters. A decision here without a finding behind it is a scope
choice in the wrong file.
