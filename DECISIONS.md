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

## D1 — Target a high-commercial-intent vertical, not a broad consumer audience
**Date:** 2026-08-26 · **Status:** Active

Pursue a niche where **the reader can make or save money from the content, and where advertisers
want to reach them at that moment.** Reject broad consumer topics regardless of how large the
addressable audience looks.

The qualifying test is *not* "is this B2B." It is: **does my reader turn this into money, and who
wants to sell to them?** Investing is largely consumer and tops the revenue table; Technology is
thoroughly B2B and has the lowest top-decile conversion of any vertical measured. B2B is a rough
proxy, commercial intent is the actual variable.

**Driven by:** [L1](LEARNINGS.md) — revenue per audience member varies ~100x by niche, and that
dwarfs audience size. Poyar earns ~$17.50/subscriber/yr from 85,000 people; Imran earns ~$0.15 per
follower from 1.7M. beehiiv's platform data shows an identical 5,000-person list earning ~$13,600/yr
in investing or ~$1,260 in travel. Refined by [L2](LEARNINGS.md) (commercial intent, not B2B) and
[L3](LEARNINGS.md) (Morning Brew's own B2B division overtaking its consumer flagship).

**Rejected alternative:** A broad consumer niche. It can work — Morning Brew reached ~$70M — but
[L8](LEARNINGS.md) shows the price: without an expertise or ROI advantage you need millions of
subscribers, and therefore a distribution machine (campus ambassadors, referral engine, paid
acquisition, ~230 staff). **That is precisely what a 5-10 hr/week operator cannot supply**, so the
option is foreclosed by capacity, not by preference.

**Would change our mind:**
- Finding a solo operator who reached meaningful revenue in a *low*-commercial-intent niche at low
  hours — that would break the premise rather than bend it.
- Discovering the revenue-per-subscriber gap is mostly an artifact of *effort* or *tenure* rather
  than niche. The current evidence controls for this poorly.
- A deliberate decision that this is not primarily an income project, which would make the whole
  argument moot.

**Explicitly not decided here:** which vertical, which format, or how to monetize. D1 narrows the
search space; it does not pick a target. Note that two findings already constrain what comes next —
[L12](LEARNINGS.md) (AI has ~13.33% monthly churn, among the worst measured) and [L4](LEARNINGS.md)
(for professional audiences the advertiser outbids the reader) together suggest that whatever
vertical is chosen, **advertising and adjacent products should lead over paid subscriptions.**

---

## D2 — Treat the employer overlap as an open, unresolved dependency
**Date:** 2026-08-26 · **Status:** Active · **Unresolved**

The strongest niche candidates under [D1](#d1) sit close to the user's employer's business — Signal
Ocean owns Alphaliner and covers liner shipping, and the user works there. **Do not resolve this in
the research.** Keep developing the strongest options, and carry the conflict as an explicit open
dependency until the user has had the conversation internally.

**Driven by:** Not a research finding — a risk surfaced *by* the research. Scoring niches on
[L2](LEARNINGS.md) (commercial intent) and [C6](LEARNINGS.md) (weak competition) pushed the top
candidates directly into the user's professional domain, because that is exactly where their edge and
the market gap coincide.

**The specific unresolved questions:** IP and non-compete terms; whether proprietary or
non-public insight would be used; who owns an audience built while employed; whether the employer sees
it as competitive, complementary, or a recruiting/brand asset.

**Rejected alternative:** Ruling out employer-adjacent niches pre-emptively. That would discard the
user's single largest unpriced advantage ([L14](LEARNINGS.md)) on a risk that may well be clearable
with a conversation.

**Would change our mind:** The user getting sign-off (downgrade to a noted constraint), or being told
no (hard-rule the domain and re-score without it).

**⚠️ Practical rule until resolved:** anything learned from the day job informs the personal project
but does not become it. Keep [Alphaliner](resources/summaries/alphaliner-signal-group.md) — a company
asset — clearly distinct from anything the user might build personally.

---

## D3 — Shortlist to three candidates, all in the physical/industrial economy
**Date:** 2026-08-26 · **Status:** Active

Narrow the Phase 4 search to three:

1. **Industrial AI post-mortems** — what was deployed, what it cost, what it didn't do *(score 25)*
2. **Commodity & energy trading** — broadened 2026-08-26 to include rare metals and physical
   commodity supply-chain analysis, not just CTRM/ETRM software *(rescored 25)*
3. **AI × shipping/logistics** *(score 24)*

Drop the rest, including **buy-side AI compute (26)** — the highest-scoring candidate.

**Driven by:** The [full scored pass](research/04-niches.md) against the six-axis rubric. All three
survivors sit in the **asset-heavy, physical-economy world where the user has genuine domain
adjacency** ([L8](LEARNINGS.md), [L14](LEARNINGS.md)), and all three are **buy-side positions in
markets where sellers write nearly all the content** — the structural gap the research kept
surfacing.

**Rejected alternative:** Buy-side AI compute, despite topping the table at 26. It has the **worst
durability score of the top six (3)** — H100 lead times fell from 30-40 weeks to 10-14 in a year, and
the topic may normalize into ordinary cloud FinOps — and the user's edge there is no better than that
of thousands of other AI-adjacent writers. **Raw score favoured it; edge and durability did not.**
Also dropped: grid/data-centre power (edge 2), enterprise software procurement (edge 3), the PE
roll-up verticals (edge 1-2), RevOps/GTM and marine insurance (both competition 1), and EU
sustainability compliance (durability 2, regulation being rolled back).

**Would change our mind:** Reader or advertiser conversations showing no willingness to pay or no ad
budget in all three; or discovering an incumbent in CTRM/shipping bigger than the desk scan found.

**⚠️ Carries [D2](#d2) unevenly.** The employer conflict is **most acute for #3 (AI × shipping)**,
which is closest to Signal Ocean's own market; **partial for #2 (CTRM/ETRM)**, which overlaps
commodity flow; and **least for #1 (industrial AI post-mortems)**. If D2 resolves badly, the
shortlist reorders rather than collapses.

**⚠️ Known unresolved problem with #1:** a publication whose thesis is *"these deployments don't
work"* cannot comfortably be funded by the vendors selling them. Fuller's alignment argument does not
apply — he could advertise Garmin because he'd never compete with Garmin. Monetization here likely has
to come from the buy-side (reader subscriptions, consulting, buyer-commissioned research), which is a
harder business than the ad model the research otherwise favours.

---

## D4 — Two broad themes to sit with; defer the choice
**Date:** 2026-08-26 · **Status:** Active · **Supersedes [D3](#d3)**

Carry **two deliberately broad themes** rather than a narrow niche, and **do not choose yet**:

- **Theme 1 — Deep tech and science: advancements and deployments**
- **Theme 2 — Commodity supply chains, told as infotainment stories rather than news**

Each will be explored in its own dedicated session before a decision.

**Driven by:** The Phase 4 scans repeatedly found that narrowing to a defensible niche produced
options that were either crowded, employer-conflicted, or too narrow to write weekly for years. This
also aligns with **[C5](LEARNINGS.md)** and Lenny's position directly: *"If I followed the classic
advice of picking a narrow niche, I'd have focused on just product management. But I don't care about
product management that much"* — breadth is what makes a six-year run survivable.

**Rejected alternative:** The D3 shortlist (industrial AI post-mortems / commodity & energy trading /
AI × shipping). Not discarded on evidence — **deliberately widened**, because all three were narrow
enough to become a chore, and two carried direct employer conflict.

**⚠️ Known tension with [D1](#d1), recorded rather than resolved:** D1 says target high commercial
intent, which pushes toward professional audiences and narrow verticals. "Infotainment" pushes toward
a broad, entertained readership — and [L1](LEARNINGS.md) puts roughly a 100x revenue gap between
those. **The likely reconciliation is that register and persona are separable:** Odd Lots is
entertaining and its listeners are finance professionals. Entertaining writing *for operators* keeps
D1 intact; entertaining writing *for a general audience* does not. **This must be settled before
launch, not after.**

**Would change our mind:** The deep-dive sessions showing one theme is unwritable at 5-10 hrs/week, or
that its audience can't be monetized.

**Still open:** [D2](#d2) (employer overlap) applies to Theme 2 and escalated to a *direct* overlap
when the minor-bulk scan returned AXSMarine — Alphaliner's publisher, now owned by Signal Ocean — as
a top result.

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
