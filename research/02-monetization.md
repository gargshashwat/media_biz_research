# Monetization Research

Revenue models, the audience size and quality each requires, and realistic revenue math at each stage.

**Status:** Sponsorship and advertising pass done **2026-08-30**, scoped to the chosen theme
([D7](../DECISIONS.md) — investment research for professional investors). Subscription economics were
already settled in [L18](../LEARNINGS.md) and [05-strategy](05-strategy.md); this file covers the
**ad and sponsor side**, which [L4](../LEARNINGS.md) and L18 both make the *first* revenue.

---

## ⚠️ Read this before using any number below

**This pass was run with web search only. Page fetching was blocked for the entire session** —
Substack's leaderboard, Paved's marketplace listings, publisher media kits and Citrini's own site all
returned `EGRESS_BLOCKED`. **Every figure here comes from search-result summaries of secondary pages,
not from reading a primary source.**

That matters more than usual, because the material has a specific and severe bias:

- **Almost every CPM page found is content marketing published by a newsletter-ad-tech vendor** —
  sponsorship marketplaces, rate-card calculators, ad networks. They are selling the thing they are
  benchmarking. This is exactly the [CLAUDE.md](../CLAUDE.md) warning about creator-economy material
  being marketing, and it applies to nearly the whole corpus.
- **The numbers disagree wildly** — see the table below. A range that runs from $40 to $1,500 for the
  "same" vertical is not a benchmark; it is a sales pitch with a wide bracket.
- **No publisher rate card was obtained.** Exec Sum's and The Daily Upside's are not public; the
  search result for Exec Sum returned only a contact email.

**Treat everything below as a map of the territory, not a price list.** The verification list is at
the end and it is not optional before pricing anything.

---

## 1. What finance newsletter advertising is reportedly worth

**⚠️ Low trust, vendor-sourced, wide disagreement. Recorded as a spread, not a figure.**

| Source | Claimed CPM for finance/investing |
|---|---|
| [Newsletrix](https://newsletrix.com/blog/newsletter-sponsorship-pricing-guide) | $50-120 |
| [InboxBanner](https://www.inboxbanner.com/blog/niche-newsletter-monetization-best-verticals-premium-ad-revenue-2026) | $40-80 |
| [Dupple](https://dupple.com/learn/cpm-benchmarks-b2b-newsletters) | $90-140 direct · $30-50 programmatic |
| [SenderCircle](https://sendercircle.com/guides/finance-newsletter-advertising-rates) | $70-180 |
| [InfluencersKit](https://www.influencerskit.com/blog/newsletter-ad-rates-cpm-revenue-examples-2026) — by tier | Personal finance/FIRE **$100-300** · **Professional investing $200-500** · **"elite/institutional" $500-1,500+** |

**What survives the disagreement — three claims that every source makes independently:**
1. **Finance is at or near the top of the CPM table across every list found.** This corroborates
   [L1](../LEARNINGS.md) from the advertising side, where beehiiv only measured subscriptions.
2. **The premium is driven by audience composition, not size** — high-income, decision-making,
   financially-engaged readers. Same mechanism as [L1](../LEARNINGS.md)/[L5](../LEARNINGS.md).
3. **Impressions means opens, not sends.** Pricing is therefore hostage to open rate, and open rate is
   the number an advertiser will actually check.

**⚠️ The "elite/institutional $500-1,500 CPM" tier is the single least trustworthy number in this
file** — it is the top of one vendor's ladder, unsourced, and it is exactly the number a rate-card
calculator wants a prospective seller to believe. **Do not plan on it.** It is recorded only because
it is directionally consistent with [L5](../LEARNINGS.md) (price on the advertiser's ROI) and with
Poyar's first deal being over $100,000.

### What this implies at realistic scale
Using the **conservative** end ($50-120 CPM) and a 40% open rate — deliberately not the vendor
ladder:

| List size | Opens/send | Revenue per placement @ $50-120 CPM |
|---|---|---|
| 5,000 | 2,000 | **$100-240** |
| 10,000 | 4,000 | **$200-480** |
| 25,000 | 10,000 | **$500-1,200** |

**⚠️ This is sobering against [05-strategy](05-strategy.md)'s Inversion 1**, which assumed a sponsor
worth **$2,000/month** at ~5,000 subscribers. On CPM logic that is roughly **8-20x** the mechanical
rate. **Inversion 1 is not thereby wrong** — it is the [L5](../LEARNINGS.md) argument that a niche
professional slot is sold on the advertiser's ROI and not on impressions, and Poyar is the proof.
**But the gap between the two methods is now explicit, and it is the crux of the whole ad business:**

> **CPM pricing at 5,000 subscribers is a few hundred dollars a send. ROI pricing at 5,000 of the
> right subscribers is thousands. The entire question is whether you can sell the second one.**

Nothing in the research resolves this, and it is now the highest-value thing to test with a real
advertiser conversation.

---

## 2. ⚠️ The finding that changes how ads have to be sold in this vertical

**Financial advertisers are compliance-constrained in a way the advertisers in Themes 1 and 2 were
not.** Broker-dealers and registered firms advertising in the US fall under **FINRA Rule 2210**:
communications must be fair and balanced with risk disclosure, records must be retained (reportedly
three years from last use), and **influencer or third-party posts must be clearly identified as
advertisements and carry the firm's name and required disclosures**. Testimonials carry their own
disclosure regime — relationship, compensation, conflicts.

**Why this is decision-relevant, and it is the most useful thing this pass found:**

- **[L5](../LEARNINGS.md)'s highest-margin tactic partially breaks here.** Poyar's model is
  *"ad copy written in his own voice"* — a regulated advertiser generally **cannot** hand copy control
  to a publisher, because the firm carries the compliance liability. Expect **approved copy, review
  cycles, and slower turnarounds** from exactly the advertisers with the biggest budgets.
- **It re-ranks the advertiser list.** Unregulated advertisers — data and analytics tools, research
  platforms, conferences, recruiters, education — are **easier to sell and faster to close** than
  brokers, ETF issuers and alternative-investment platforms, even though the latter have deeper
  pockets. **Start with the unregulated tier.**
- **It is a second regulatory surface on top of the publishing one** already recorded in
  [06](06-theme3-investment-research.md). Different rules, different party carrying the risk, but it
  lands on the same publication.

⚠️ **General background from search summaries, not legal advice, and US-centric.** The
[jurisdiction question](../DECISIONS.md) is still unanswered and governs this too.

---

## 3. Who actually buys — the advertiser map for an investing publication

Themes 1 and 2 both got an advertiser map in [04-niches](04-niches.md); this is Theme 3's, which
[D7](../DECISIONS.md) recorded as missing. **Tiered by how hard the sale is, which is the ranking
§2 says actually matters** — not by budget.

### Tier 1 — unregulated, fast to close, start here
| Advertiser type | Named examples found | Why they buy |
|---|---|---|
| **Research & fundamental-data tools** | **Koyfin**, **Fiscal.ai / FinChat**, **Daloopa**, **AlphaSense**, Tegus-style platforms | Their buyer *is* this reader. ✅ **Confirmed live behaviour:** FinChat reportedly sponsored **Compounding Quality (~150k subs)** in March 2026 |
| **Charting / terminal alternatives** | TradingView-class tools | Direct-response, measurable, high LTV |
| **Conferences and events** | Institutional and thematic-investing conferences | Seasonal, budget-flush, low compliance load |
| **Recruitment** | eFinancialCareers-class, headhunters | ⚠️ Untested here, but the audience is exactly their product |
| **Professional education** | CFA/quant training, courses | Aligned with an expert-led publication |

### Tier 2 — deeper budgets, heavier compliance (§2)
| Advertiser type | Named examples found | Constraint |
|---|---|---|
| **Brokers / trading platforms** | Interactive Brokers, Public.com, Firstrade | ⚠️ FINRA 2210 — approved copy, disclosures, records |
| **ETF issuers** | *(none named in results — the gap below)* | ⚠️ Fund marketing rules; strong fit with **thematic** content |
| **Alternative-investment platforms** | **Masterworks**, Percent-class | Documented as prolific newsletter advertisers ⚠️ but see the note below |

**⚠️ ETF issuers are the most conspicuous absence in this scan and the most likely mispricing.** A
*thematic* publication is the natural home for *thematic ETF* marketing — the product category is
literally the same idea — and no search returned one. **That is a gap in the evidence, not evidence of
a gap:** it may simply mean the searches were wrong. **Highest-value thing to check with browser
access.**

**⚠️ Two cautions on Tier 2, and they are [D5](../DECISIONS.md)/credibility issues, not commercial
ones.** Alternative-investment and broker advertisers are the ones most associated with retail
promotion, and taking their money shapes who a publication is understood to be. The
[§17(b) paid-promotion](06-theme3-investment-research.md) exposure also lands hardest here. **A
publication positioned on institutional rigour has more to lose from a Masterworks placement than it
gains.**

### Tier 3 — the ones the research says are actually worth the most, and none were found
**Institutional-side buyers:** price reporting agencies, expert networks, prime brokers, execution
venues, alternative-data vendors, index providers. **⚠️ Nothing in this scan reached them.** They
are the natural advertisers for a professional-investor audience and they are absent from every
newsletter-marketing source found — which is itself informative: **these firms buy through
relationships and trade press, not through newsletter ad marketplaces.** If they are reachable at
all, it is by direct sale, which is the [L5](../LEARNINGS.md) model anyway.

---

## 4. ⚠️ Do the comparable publications even run ads?

The single most important structural question for this theme's ad business, and the answer is
**unclear and mildly discouraging**.

- **Citrini** — one aggregator ([reletter](https://reletter.com/publications/citrinis-newsletter))
  states it *"accepts sponsorships and partnerships."* ⚠️ **Unverified, aggregator-sourced**, and
  Citrini's own site was unreachable this session.
- **Doomberg** — appears to be **subscription-first**, free previews into paid tiers, with no
  sponsorship model evident in results.

**Neither of the two closest comparables is visibly ad-led.** ⚠️ This does *not* overturn
[L4](../LEARNINGS.md) or [L18](../LEARNINGS.md) — both are top-of-market publications with very large
lists, i.e. exactly the regime where L18 says the $999 subscription finally does pay. But it means
**the ad-led path this project recommends has no proven exemplar inside this specific niche.** The
ad-led exemplars (Poyar, Morning Brew, Exec Sum, The Daily Upside) are business/professional media,
not investment research.

**Recorded as an open contradiction, not resolved:** the strategy says sponsor first, and the two
publications this theme is modelled on appear to have done subscriptions first.

---

## 5. What to verify first when page access is available
In rough order of value:
1. **Two or three real media kits** from ad-supported finance newsletters — the only way to replace
   the vendor spread in §1 with a real number.
2. **Whether ETF issuers buy newsletter placements** (§3) — the biggest suspected gap.
3. **Whether Citrini genuinely runs sponsorships**, and in what form (§4).
4. **A marketplace listing scan** (Paved and equivalents) filtered to finance, for observed asking
   prices at 5k-25k subscribers — the scale that actually matters near-term.
5. **Open rates** for finance newsletters, since §1 shows pricing is hostage to them.

## Sources drawn on
⚠️ All accessed via **search-result summaries only**; none were read in full.
Vendor/marketing sources — [Newsletrix](https://newsletrix.com/blog/newsletter-sponsorship-pricing-guide) ·
[InfluencersKit](https://www.influencerskit.com/blog/newsletter-ad-rates-cpm-revenue-examples-2026) ·
[InboxBanner](https://www.inboxbanner.com/blog/niche-newsletter-monetization-best-verticals-premium-ad-revenue-2026) ·
[SenderCircle](https://sendercircle.com/guides/finance-newsletter-advertising-rates) ·
[Dupple](https://dupple.com/learn/cpm-benchmarks-b2b-newsletters) ·
[SponsorGap](https://sponsorgap.com/blog/top-finance-newsletter-sponsors-2026) ·
[beehiiv](https://www.beehiiv.com/blog/newsletter-sponsorship-cost).
Regulatory background — [FINRA advertising overview](https://www.finra.org/rules-guidance/key-topics/advertising-regulation-overview) ·
[FINRA social-media guidance summary](https://shufirm.com/finra-issues-new-guidance-on-social-media-communications-including-rules-on-sharing-content-and-new-types-of-advertising).
Publication facts — [reletter on Citrini](https://reletter.com/publications/citrinis-newsletter) ·
[beehiiv case study on Exec Sum](https://www.beehiiv.com/case-studies/exec-sum).
