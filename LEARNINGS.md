# Key Learnings

Durable, load-bearing facts about media businesses — the things that should shape decisions
across the whole project. Every entry cites what backs it.

An entry earns a place here only if it matters beyond a single phase. Phase-specific findings
belong in the relevant `research/` file. Keep this skimmable; prune when it isn't.

**Confidence** reflects both the strength of the evidence and how many *independent* sources
support it. A single source, however credible, is rarely `high`.

_Status: 15 resources studied. Nothing here is final — several entries have real counter-evidence,
which is noted rather than smoothed over._

---

## The niche decides the economics

### L1 — Revenue per audience member varies ~100x by niche, and that dwarfs the effect of audience size
The single most decision-relevant pattern in the research.

| | Audience | Revenue | Per member/yr |
|---|---|---|---|
| Kyle Poyar (B2B SaaS) | 85,000 | ~$1.5M | **~$17.50** |
| Morning Brew (consumer) | 4,000,000 | ~$70M | **~$17.50** |
| Imran (personal finance, short-form) | 1,700,000 | ~$250k | **~$0.15** |

beehiiv's platform data says the same thing at scale: an identical 5,000-subscriber list earns
**~$13,600/yr in investing** or **~$1,260/yr in travel** — **11x**, same size, same effort. Median
price is **$27/mo investing vs $7/mo travel**, and **list size barely affects price at all** (a 500-
subscriber publication charges roughly what a 100,000-subscriber one does).

**Source:** [beehiiv benchmarks](resources/summaries/beehiiv-state-of-paid-newsletters-2026.md) ·
[Poyar](resources/summaries/kyle-poyar-growth-unhinged-1-5m-solo.md) ·
[Imran](resources/summaries/imran-finance-engineer-shorts-250k.md) ·
[Morning Brew](resources/summaries/morning-brew-case-study.md) · **Confidence: high**

### L2 — ⚠️ The variable is commercial intent, not "B2B"
It's tempting to read L1 as "do B2B." The data doesn't quite say that. What actually predicts high
revenue per reader is **whether the reader can turn the content into money, and whether an advertiser
wants to reach them at the moment they can.**

- **Investing** is the top-earning vertical and is largely *consumer*, not B2B — a reader can tie one
  stock tip directly to a financial outcome.
- **Sports** converts at 1.93% median, 3x the platform average, on tribal loyalty rather than ROI.
  *Extra Points* — the business of college sports — does **$200k+/yr from 2,000 paying readers.**
- **Technology has the *lowest* top-decile conversion (5.55%)** of any vertical measured, despite
  being thoroughly B2B.
- Senra's framing of why his audience listens: *"they're building machines where they literally can
  turn knowledge into profit... one idea gives a 10% improvement on his company — it's a $10 million
  idea."*

**The useful test is not "is this B2B" but "does my reader make or save money because of this, and
who wants to sell to them."** Freight logistics, SaaS pricing, and college-sports business all pass.
General tech news passes much less well than it looks.

**Source:** [beehiiv](resources/summaries/beehiiv-state-of-paid-newsletters-2026.md) ·
[Senra](resources/summaries/david-senra-founders-acquired.md) ·
[Fuller](resources/summaries/craig-fuller-freightwaves-media-arbitrage.md) · **Confidence: medium-high**

### L3 — Consumer is a volume business; professional is a margin business
Morning Brew needed **4M subscribers** to reach ~$70M, took **two years of manual work to reach
10,000**, and ended up with ~230 employees. Its **B2B division grew from <$5M (2020) to ~$25M (2024)
and was expected to surpass the consumer flagship in 2025** — and it installed a B2B media operator
as CEO. The most successful consumer newsletter of its generation migrated toward professional
economics as it matured.

**Source:** [Morning Brew](resources/summaries/morning-brew-case-study.md) ·
[The Hustle](resources/summaries/sam-parr-hustle-growth-in-reverse.md) · **Confidence: high**

---

## How these businesses actually make money

### L4 — For a professional audience, the advertiser will always outbid the reader
The clearest statement, from Ben Gilbert on Acquired:

> "You could never ask someone to pay you in membership what they are worth to the most valuable
> advertiser for that slot... you'd have to charge **$2,000-$5,000 a year** to match what you'd get
> from opening that same slot to advertisers."

Their rule of thumb: **~50% direct monetization, ~50% advertising.** Corroborated everywhere —
Poyar's ads run **5-6x** his subscriptions; Imran is **70% brand deals**; The Hustle and Morning Brew
are ~all advertising, and Austin Rief rejected subscriptions as a goal outright.

**⚠️ The strongest single confirmation:** Lenny Rachitsky is *the* paid-newsletter success story —
~18,000 paid subscribers, ~$2M/year — and **his ad-supported podcast outearns it.**

**⚠️ The one dissenting source is beehiiv, which sells subscription software** — and its claim that
subscriptions are ~85% of creator revenue is almost certainly a measurement artifact, since beehiiv
can only see money that flows through beehiiv.

**Source:** [Senra/Acquired](resources/summaries/david-senra-founders-acquired.md) ·
[Poyar](resources/summaries/kyle-poyar-growth-unhinged-1-5m-solo.md) ·
[Imran](resources/summaries/imran-finance-engineer-shorts-250k.md) ·
[Morning Brew](resources/summaries/morning-brew-case-study.md) ·
[The Hustle](resources/summaries/sam-parr-hustle-growth-in-reverse.md) · **Confidence: high**

### L5 — Price advertising on the advertiser's ROI, not on impressions
In a niche B2B audience, CPM and cost-per-click *"is so underpriced relative to the value."* If one
advertiser closes a $100k deal, the impression count is irrelevant. Poyar sells **quarterly packages**
including **category exclusivity** and ad copy written in his own voice, deliberately constrains
inventory to one slot per issue, sells out, and only then raises prices — an explicit airline-yield
model. He still thinks he underpriced by ~50%.

**⚠️ Counterweight:** Dwarkesh calculates **"close to a day+ of work per ad"** once you include
selling, vetting, scripting, recording, and re-recording — and argues that time would be better spent
making paid content. **Both are true: ad economics depend on how you package the offer, not just on
audience size.** Poyar sells few, expensive, standardized packages; Dwarkesh does bespoke work per ad.

**Source:** [Poyar](resources/summaries/kyle-poyar-growth-unhinged-1-5m-solo.md) ·
[Dwarkesh](resources/summaries/dwarkesh-patel-progress-update.md) · **Confidence: medium-high**

### L6 — The real money is often in adjacent businesses, not the media itself
Fuller's "negative CAC": media revenue pays for the audience, then you sell that audience high-value
adjacent products — he built a fly-in property development (land at $2,400/acre, lots at $150,000),
an aircraft marketplace, and a financing business bought for ~$140k that hit a ~$1M run rate in six
months. **Morning Brew reached the same place from the consumer side: only ~3 of ~12 B2B ad products
are newsletter placements** — the rest is lead gen, webinars, events. Stebbings converted a podcast
into a VC fund. Poyar splits his time 50/50 with consulting.

**Source:** [Fuller](resources/summaries/craig-fuller-freightwaves-media-arbitrage.md) ·
[Morning Brew](resources/summaries/morning-brew-case-study.md) ·
[Poyar](resources/summaries/kyle-poyar-growth-unhinged-1-5m-solo.md) ·
[Stebbings (notes)](resources/summaries/harry-stebbings-media-playbook-notus.md) · **Confidence: high**

### L7 — Own the audience; rent only the attention
Six independent routes to the same conclusion. Fuller buys magazines *for* their audiences; Imran
started a newsletter after a TikTok ban; Sam Parr **built his own email service provider** rather
than depend on Mailchimp; Poyar treats LinkedIn as top-of-funnel and the newsletter as the asset;
BuzzFeed and Vice collapsed when Facebook cut referral traffic.

The cleanest frame is from the Stebbings notes: **Attention → Retention → Monetization.** Attention
is rented and algorithmic (LinkedIn, X, TikTok). Retention is owned (newsletter, podcast, community).
Monetization happens against the retained layer, never the rented one.

**Source:** [Fuller](resources/summaries/craig-fuller-freightwaves-media-arbitrage.md) ·
[Imran](resources/summaries/imran-finance-engineer-shorts-250k.md) ·
[The Hustle](resources/summaries/sam-parr-hustle-growth-in-reverse.md) ·
[Poyar](resources/summaries/kyle-poyar-growth-unhinged-1-5m-solo.md) ·
[Stebbings (notes)](resources/summaries/harry-stebbings-media-playbook-notus.md) · **Confidence: high**

---

## What actually differentiates

### L8 — Expertise lets you monetize a small audience; without it you need a very large one
The apparent contradiction between the expert-led cases and Morning Brew resolves cleanly. Poyar
(85k) and Morning Brew (4M) earn nearly the same **per subscriber** — but one is reachable by a
person working evenings and the other took a decade, ~230 staff, an ambassador program and a referral
engine. **Not needing expertise makes Morning Brew sound more accessible. It is the opposite.**

Practitioner-sourced content recurs everywhere: Lenny's newsletter is mostly guest posts from people
who did the work; Fuller's breakout came from writing hurricane logistics from direct FEMA
experience; Poyar consults alongside writing (*"it's like I'm in the room with my readers"*).

**A cheaper substitute for expertise exists: being your own audience.** Lieberman was a finance
senior writing for finance students.

**Source:** [Morning Brew](resources/summaries/morning-brew-case-study.md) ·
[Poyar](resources/summaries/kyle-poyar-growth-unhinged-1-5m-solo.md) ·
[Lenny](resources/summaries/lenny-rachitsky-behind-the-scenes-interview.md) ·
[Fuller](resources/summaries/craig-fuller-freightwaves-media-arbitrage.md) · **Confidence: high**

### L9 — Preparation is the one moat that can be built from nothing
Every other advantage in this research is inherited — Poyar's VC network, Lenny's Airbnb career,
Fuller's capital, Morning Brew's two full-time founders. **Depth of preparation is the exception.**
Senra read 300 founder biographies alone, unpaid, for years. Dwarkesh spends **two weeks preparing
per guest** and picks guests by *"whether I would learn a lot by spending two weeks preparing"* —
his most popular guest was an obscure historian, and episodes with friends beat famous CEOs. Bill
Gurley's claim, quoted by Senra: **two years of intense study makes you a domain expert.**

It costs the one thing our capacity budget limits. But unlike a network or a career, it can be
started from zero.

**Source:** [Senra](resources/summaries/david-senra-founders-acquired.md) ·
[Dwarkesh](resources/summaries/dwarkesh-patel-progress-update.md) · **Confidence: medium-high**

### L10 — Depth compounds; volume resets — but only for knowledge businesses
Poyar writes deliberately dense canonical guides people save and re-share for months, so the writing
compounds instead of restarting weekly. Lenny does **~50 iterations per post** plus an editor, copy
editor and designer. beehiiv finds top-decile performers differentiate on depth, not frequency.
Senra's back catalogue is permanently referenced; Acquired retro-fits ads into old episodes, making
an evergreen archive into sellable inventory.

**⚠️ Real counter-evidence:** Sam Parr published **10 articles a week**; Morning Brew publishes daily.
Both worked. **The distinction is L8** — distribution businesses need volume, knowledge businesses
need depth. Pick the model first, then the cadence.

**⚠️ The sharpest operating principle in the research resolves the cadence-vs-depth tension:**
**Lenny's two biggest research projects drove 50% of his entire first-year subscriber growth** — one
added ~2,000 subscribers when he had only 2,800. His motto: **"Keep writing great stuff every week,
and work on something epic in the background."** Weekly cadence is maintenance; the occasional deep
artifact is what compounds. **They are different jobs, not competing strategies.**

**Source:** [Poyar](resources/summaries/kyle-poyar-growth-unhinged-1-5m-solo.md) ·
[Lenny (mechanics)](resources/summaries/lenny-rachitsky-business-mechanics.md) ·
[beehiiv](resources/summaries/beehiiv-state-of-paid-newsletters-2026.md) ·
[Senra](resources/summaries/david-senra-founders-acquired.md) · **Confidence: high**

---

## Sobering base rates

### L11 — Median free-to-paid conversion is 0.62%
About **six paying subscribers per thousand.** Every operator in this research is a top-decile
outcome. Top-decile finance and investing hit 18-20%; a realistic long-term target is **2-5%**.
And the denominator is already flattering — beehiiv only measures publications that *chose* to launch
a paid tier.

**Source:** [beehiiv](resources/summaries/beehiiv-state-of-paid-newsletters-2026.md) · **Confidence: medium-high**

### L12 — ⚠️ The AI vertical has among the worst subscription retention measured
**13.33% monthly churn → ~7.5 month subscriber lifetime**, because free alternatives appear
constantly and erode the paid proposition. For reference, 5% monthly churn means ~54% survive a year;
17% means ~11% do. Rowan Cheung's Rundown (~2M subs) is consistent with this — **he doesn't sell
subscriptions at all.** Free newsletter, advertising, adjacent education.

**Directly relevant to the domain edge under consideration: an AI-adjacent publication should
probably not lean on paid subscriptions.**

**Source:** [beehiiv](resources/summaries/beehiiv-state-of-paid-newsletters-2026.md) ·
[Rowan Cheung](resources/summaries/rowan-cheung-rundown-ai.md) · **Confidence: medium-high**

### L13 — The start is slow in every single case, without exception
Poyar: **18 months to 5,000 subscribers**, "glacial." Morning Brew: **two years to 10,000**, pitching
lecture halls and collecting emails on paper. Lenny: **four years before anyone recognized him.**
Imran: **three years to replace his salary**, year one at $75k against a $250k Amazon comp. Senra
**paid to make the show for years.** Dwarkesh was **two months from quitting, for two years** — and
his first backer called the grant a regret.

**No case in this research grew quickly at the start.** Any plan should assume years, not months.

**Source:** [Poyar](resources/summaries/kyle-poyar-growth-unhinged-1-5m-solo.md) ·
[Morning Brew](resources/summaries/morning-brew-case-study.md) ·
[Lenny](resources/summaries/lenny-rachitsky-behind-the-scenes-interview.md) ·
[Imran](resources/summaries/imran-finance-engineer-shorts-250k.md) ·
[Senra](resources/summaries/david-senra-founders-acquired.md) ·
[Dwarkesh](resources/summaries/dwarkesh-patel-progress-update.md) · **Confidence: high**

### L14 — ⚠️ Every single success we've studied had an unpriced advantage, and none of them foreground it
Poyar: four years as a VC operating partner — his advertisers were **already asking to buy before he
had anything to sell.** Lenny: seven years at Airbnb, a startup acquired *by* Airbnb, and a first post
Brian Chesky shared company-wide. Imran: severance, savings, no kids, spousal health insurance, an
engineering résumé to fall back on. Dwarkesh: grants, living with his parents at zero expenses.
Senra: savings, supporting a family through years of loss. Sam Parr: a prior exit plus a $250k raise.
Fuller: a successful company and millions in capital.

**The playbooks are real. The starting positions are not replicable, and the retrospectives never
price them in.**

**Source:** all case studies · **Confidence: high**

### L15 — Roughly half of production time goes to distribution, not to the product
Tom Alder splits time **50/50 between social content and newsletter articles**. Poyar independently:
*"you've got to treat the audience and the content on essentially equal footing"* — not 80% content
and hope. Dwarkesh, working full-time, found **less than half his to-do list was reading or writing**;
the rest was ad sales, edit management, logistics — what he calls "flying monkeys."

**At 5-10 hrs/week this halves the effective writing budget, and any format should be judged on its
overhead-to-craft ratio. Podcasts look worst on this measure.**

**Source:** [Tom Alder (notes)](resources/summaries/tom-alder-newsletter-operations.md) ·
[Poyar](resources/summaries/kyle-poyar-growth-unhinged-1-5m-solo.md) ·
[Dwarkesh](resources/summaries/dwarkesh-patel-progress-update.md) · **Confidence: medium**

---

### L16 — Cold outreach is how people without networks acquire access
Four independent cases. **Stebbings** found Guy Kawasaki's email in his website's source code and sent
four lines citing a specific page of his book; he emailed **Marc Benioff 53 times** with a different
esoteric PS each time. **Sam Parr** cold-called and cold-emailed founders repeatedly to get free
conference speakers, and cold-DM'd Steph Smith off a blog post. **Dwarkesh** cold-emails scholars —
and regrets the ones he didn't reach before they died. **Molly O'Shea:** *"cold outreaching to people
you admire can truly benefit you more than anything else."*

The repeating structure: **short, demonstrated proof of work, one clear ask, and persistence past the
point most people stop.**

**Source:** [Stebbings](resources/summaries/harry-stebbings-20vc-business.md) ·
[The Hustle](resources/summaries/sam-parr-hustle-growth-in-reverse.md) ·
[Dwarkesh](resources/summaries/dwarkesh-patel-progress-update.md) ·
[Sourcery](resources/summaries/molly-oshea-sourcery.md) · **Confidence: high**

### L17 — For professional audiences, add a tier for people whose employer pays
Lenny runs an **"I Can Expense It" tier at $300** alongside his $150/yr standard. Molly O'Shea kept an
**"expense it" tier** for fund managers even while cutting her headline price 70%. Same product,
different willingness to pay, no extra production cost. **Two sources, both in high-commercial-intent
niches.**

**Source:** [Lenny (mechanics)](resources/summaries/lenny-rachitsky-business-mechanics.md) ·
[Sourcery](resources/summaries/molly-oshea-sourcery.md) · **Confidence: medium**

---

### L18 — Cold starts are won by borrowing audiences and by a few outsized artifacts, never by engagement volume
**No case in this project grew primarily by replying to other accounts.** What actually produced the
first thousand, in every documented case, was one of two things:

- **Borrowing an audience that already exists.** Lenny's first 1,000 came from **two guest posts** on
  other people's sites; Doomberg ran **~100 podcast appearances a year**; Sam Parr asked his speakers
  to share the posts he'd written *about them* and gave 50 tickets to influencers; Lenny tags every
  contributor so they amplify. **You engage with other accounts by featuring them, not by commenting
  on them** — a feature gives them a reason to broadcast you, a reply gives them nothing.
- **One outsized artifact.** Lenny's **two research projects drove ~50% of his entire first-year
  growth** — one added ~2,000 subscribers when he had 2,800, another 5,000+ in two weeks.

⚠️ **The contrary evidence is vendor marketing.** A 2026-09-05 search for evidence supporting the
reply-and-engage strategy returned only pages published by sellers of reply-automation tools, with
unattributed figures and no methodology. **The mechanic with the loudest evidence base has the
weakest one.**

**Source:** [07-early-stage-marketing.md](research/07-early-stage-marketing.md) ·
[Lenny (mechanics)](resources/summaries/lenny-rachitsky-business-mechanics.md) ·
[Doomberg](resources/summaries/doomberg-cold-start.md) ·
[The Hustle](resources/summaries/sam-parr-hustle-growth-in-reverse.md) ·
[L16](#l16--cold-outreach-is-how-people-without-networks-acquire-access) · **Confidence: high for the
positive claim, high for the absence of good evidence on the negative**

### L19 — ⚠️ The rented platform taxes the handoff to the owned one
[L7](#l7--own-the-audience-rent-only-the-attention) says convert rented attention into owned
retention. **The platforms charge for that conversion.** X is reported to cut reach on posts carrying
external links by **50-90%** (conservative estimates 30-50%), with "link in the first reply" the
standard workaround. In **August 2023 Doomberg — then the leading finance publication on Substack,
built entirely on X — quit the platform over it**, stating that *"the mere mention of 'Substack' in a
tweet leads to substantial de-boosting."*

**This makes platform choice a business decision, not a preference**, and it means growth and
list-capture are in direct tension on X specifically.

⚠️ **And the escape is another landlord.** Doomberg moved to Substack Notes; Substack's own network
reportedly now drives ~50% of new subscriptions platform-wide, echoing the Recommendations
discontinuity that took Lenny from 111,000 to 377,000 in under a year. **An aligned platform is still
a rented one.**

⚠️ **Trust: low-medium.** The platform figures come from search summaries of SEO/social-tooling blogs
and an interested publisher; **no primary source was reachable.** Doomberg's read is from 2023 and
needs re-checking before it drives a decision.

**Source:** [07-early-stage-marketing.md](research/07-early-stage-marketing.md) ·
[Doomberg](resources/summaries/doomberg-cold-start.md) · **Confidence: low-medium — flagged for
re-verification**

---

## Open contradictions — do not treat as settled

### C1 — When to start charging: four sources, four incompatible answers
**6 weeks** (beehiiv median, and beehiiv sells subscription software) · **9 months** (Lenny, and only
because covid threatened his Airbnb stock) · **~3 years** (Imran's paid community) · **4.5 years**
(Poyar, who monetized nothing until he went solo). Nothing resolves this yet.

### C2 — Cadence: weekly discipline vs. depth at low frequency
Weekly cadence was Poyar's single biggest growth inflection and Lenny's non-negotiable commitment.
But Henry Shi claims **12,000 subscribers in 6 months at 1-2 posts a month** (⚠️ unverified, LinkedIn
inaccessible, and he had an existing following). **Serialization may reconcile these** — The
Generalist ran one 18-month research project as four weekly parts.

### C3 — Does original reporting matter?
Fuller praises Morning Brew for *not* doing original reporting, calling the derivative product more
profitable than the source. But he also argues firsthand expertise is the durable moat. Morning
Brew's editorial cost structure remains unstudied — **this is the crux of whether "summarize others"
is a real model or just a cheap start.**

### C4 — ⚠️ PARTLY RESOLVED: it can be done alongside a job, and the timeline is years
Two cases now built real media assets while employed full-time, and they agree closely:
- **Kyle Poyar:** 4.5 years alongside a demanding VC job, monetization contractually forbidden
  throughout. Went solo and was at a $1.5M run-rate within ~10 months.
- **Molly O'Shea (Sourcery):** ~6,000 subscribers over ~4 years at **4:30am around a full-time
  investing job**, then 2x subscribers and 4.5M impressions in year five.

**O'Shea is the more instructive case because she reached the go-full-time decision and declined**,
naming her reasons: *"I am not rich & need real income," "my personal risk tolerance isn't there yet,"
and "I just love investing too much."* She also states the core difficulty plainly — *"as one person,
to constantly pump out thoughtful, well-researched pieces... with a full time investing job, it's
just overall very difficult to manage."*

**Reading: the constraint is survivable, the timeline is ~4 years to a small but valuable audience,
and staying part-time is a legitimate end state rather than a failure to commit.** Everyone else
studied was full-time (Imran 20-50 hrs/week, Rowan 80).

### C5 — ⚠️ NEW: narrow hard, or stay broad? Two major cases say opposite things
**Harry Stebbings:** *"Biggest mistake: trying to be too much to too many people."* For **two years he
interviewed only seed investors in San Francisco.** His instruction is **"narrow until it hurts"** —
narrow focus gives a clear guest profile, an obvious sponsorship model, and a thousand true fans.

**Lenny Rachitsky:** *"If I followed the classic advice of picking a narrow niche, I'd have focused on
just product management. **But I don't care about product management that much.**"* He credits staying
broad with still publishing six years later.

**A possible reconciliation, flagged as inference rather than finding:** *narrow to start, broaden to
sustain.* Stebbings narrowed for two years then widened; Lenny began with Airbnb-specific growth and
marketplace research before widening. **Narrow buys traction and a sellable proposition when you have
no leverage; breadth buys the will to keep going.** Note this sits directly on top of
[D1](DECISIONS.md) — which survives either way, because commercial intent is a different axis from
topical breadth.

### C6 — ⚠️ NEW: is "weak competition" a better filter than market size?
Three sources now argue the absence of good incumbents *is* the opportunity: Stebbings' European
arbitrage (*"can't name five good Series A funds"*), Rowan Cheung's *"verticalized content is blue
ocean — nobody's doing AI-for-law content,"* and Fuller being told by every VC that freight was
"a boring niche." **More actionable than market size, but untested — and all three are describing
markets they entered years ago.**
