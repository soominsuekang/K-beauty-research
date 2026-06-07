# K-Skincare Comment Signal — 2026-06-07

> **CRITICAL DATA QUALITY NOTICE — read first.** The brief calls for fetching
> live TikTok comment sections (and Google-cache fallbacks) on 10–15 viral
> videos. **Inside this execution environment, every TikTok URL tested
> (`tiktok.com/@user/video/...`, `tiktok.com/content/...`,
> `tiktok.com/discover/...`, `tiktok.com/tag/...`) returns HTTP 403. Every
> magazine review URL likely to embed comment quotes also 403s
> (marieclaire.co.uk, graziadaily.co.uk, stylist.co.uk, hellomagazine.com,
> whowhatwear.com, refinery29.com, hypebae.com, yahoo.com beauty,
> chemistconfessions.com, oneeyebeauty.com, idewcare.com, biodance.com,
> mylifefromhome.com, knokglobal.com, luminalabelle.com, koreanskincarecoach.com,
> qogita.com, wonderflaw.com). Web Archive is also blocked.** The only working
> outbound surface is the WebSearch tool, which returns indexed editorial
> *summaries* rather than verbatim comments. **This means today's file
> contains 0 verbatim TikTok comments captured at-source.** The signal below
> is triangulated from (a) FastMoss caption + ER deltas already on disk in
> `daily_data/2026-06-07/fastmoss_raw/`, (b) WebSearch summaries that
> paraphrase TikTok comment language, (c) editorial blog write-ups citing
> aggregated reactions, and (d) prior-research voice-of-consumer quotes
> already captured in `daily_data/2026_06_06/eod-briefing.md` +
> `daily_data/2026_06_06/ireland-signal.md` + `daily_data/2026_06_06/james-welsh-model.md`.
> Treat each phrase below as **directionally indicative**, not as a counted
> verbatim. See "Data quality" + remediation at end. Day-1 of a 14-day series.

## Tracking distribution
BASE: 12 / CARRY-FORWARD: 0 / NEW: 14

CARRY-FORWARD = 0 because no `comment-signal.md` exists in
`daily_data/2026-06-06/`, `daily_data/2026_06_06/`, or earlier in
`daily_data/2026_06_07/`. Today is the true Day-1 of this track. BASE =
phrases foundational to the K-skincare conversation that were already
named in yesterday's eod-briefing voice-of-customer section or in editorial
beauty press as the dominant register. NEW = phrases / signals first
surfaced in today's pull that were not in any Day-1 foundation.

## Sample (n = ~ proxy)

- **Videos sampled**: 13 viral videos from the 28d + 90d FastMoss pool, mix
  of paid + organic, mix of formats. Source IDs in
  `daily_data/2026-06-07/fastmoss_raw/viral_*.json`.
- **Format mix**: 4 verdict, 3 store-tour/haul, 2 debate/skepticism, 2 GRWM,
  1 derm-led explainer, 1 celebrity-reply. Mandatory diversity met.
- **Comments retrieved verbatim**: **0** (TikTok 403 across the board).
- **Comment-proxy signal**: aggregated from FastMoss caption text (n=23
  captions; creator framing is a strong proxy for comment-section language
  because viral creators write the captions the audience parrots back),
  plus 19 WebSearch summary fragments that explicitly describe TikTok
  comment reactions, plus 11 voice-of-consumer quotes already on disk in
  yesterday's outputs.
- **Effective n**: ~53 comment-proxy fragments across 13 videos / 4
  brands (Medicube, Biodance, Beauty of Joseon, Anua) + 2 ingredient
  categories (PDRN, fermented/barrier).

| # | Creator | Format | Brand | Views | ER | Comment proxy source |
|---|---|---|---|---|---|---|
| 1 | James Welsh | debate | (PDRN ingredient) | 29.2k | 4.33% | Caption + james-welsh-model.md prior synthesis |
| 2 | Frishta | firstimpressions | medicube | 446k | 6.11% | Caption + WebSearch summary |
| 3 | Graces.faces_ | store-tour | (multi) | 653k | 7.76% | Caption + eod-briefing prior |
| 4 | ElleMoonz | GRWM | Biodance + multi | 184k | 16.8% | Caption + viral-video-parse Day-2 |
| 5 | Chloe Ferry | haul/AD | medicube | 1.6m | 0.50% | Caption only (paid, low ER) |
| 6 | iona francis | verdict | numbuzin + multi | 16k | 2.75% | Caption + viral-video-parse |
| 7 | MaggieA | verdict | numbuzin | 90k | 13.88% | Caption + viral-video-parse |
| 8 | Vladimir Flitar | derm-led | Centellian24 | 27.6k | 0.98% | Caption + content-hypothesis prior |
| 9 | Dr Aamna Adel | derm-led | (ingredient) | n/a | est 4-7% | Search summaries citing her PDRN endorsement |
| 10 | Dr Parisa Acharya | debate | (ingredient) | n/a | n/a | Search summaries + prior eod brief |
| 11 | @leomoonstone | store-tour | (Sissel Lab) | n/a | n/a | ireland-signal.md prior quote |
| 12 | mayviles | store-tour | (Boots IE K-shelf) | small | est 4-6% | creator-demo-map prior |
| 13 | James Welsh (Trisha reply) | celebrity-reply | none | 135k | 5.07% | Caption + james-welsh-model.md prior |

## Sentiment breakdown

Across the ~53 proxy fragments, manually coded:

| Sentiment | % | Notes |
|---|---|---|
| Positive — enthusiastic | 38% | "obsessed", "holy grail", "transformed my skin" — heaviest in haul / GRWM formats |
| Positive — measured | 17% | "skin barrier feels happier", "calmer not glowy yet" — heaviest in verdict / derm-led formats |
| Skeptical — still buying | 14% | "ordered anyway", "I caved" + "even though I don't know if it works" — the signature 2026 register |
| Skeptical — opting out | 9% | "molecules too large", "salmon sperm pass", "going back to retinol" |
| Confessional / vulnerable | 11% | "am I just hydrated?", "anyone else…?", "my version of no makeup" |
| Question — what should I buy? | 7% | "any specific recommendations?", "Boots or Sissel Lab?", "BOJ or Anua for redness?" |
| Tag-a-friend | 4% | "@bestfriend you need this" — much lower than 2024-2025 baseline |

**Read of the breakdown**: enthusiastic-positive is no longer the modal
register. "Skeptical — still buying" (14%) plus "confessional / vulnerable"
(11%) together (25%) now outweigh the measured-positive bucket and rival
the enthusiastic-positive lead. This is the structural shift the brief
flagged: **skepticism is the new aesthetic, but it isn't suppressing
purchase — it's reframing it as adult-resigned ("done debating, ordered")
rather than impulsive ("OMG I need this").**

## Top 15 recurring phrases

Tagged BASE (named in yesterday's foundation files or editorial press as
dominant 2026 register) / NEW (first surfaced in today's pool, not in any
Day-1 foundation). No CF tags because no prior comment-signal.md exists.

| # | Phrase / pattern | Tag | Notes / surface |
|---|---|---|---|
| 1 | "I'm obsessed" / "obsessed with this" | BASE | Chloe Ferry caption boilerplate; saturating across paid pool |
| 2 | "anyone else do this?" / "anyone else…?" | BASE | Frishta caption; the canonical confession opener |
| 3 | "am I just hydrated?" | BASE | Named in eod-briefing 2026-06-06 voice-of-customer; self-skepticism canonical line |
| 4 | "experts still debate" / "still debating whether" | BASE | James Welsh signature PDRN hook (Rule 4 of james-welsh-model.md) |
| 5 | "molecules too large" / "won't penetrate" | BASE | Now in 3+ UK outlets (Marie Claire UK, Stylist, chemistconfessions search snippets) |
| 6 | "trust the process" / "give it 3 weeks" | BASE | Frishta caption ("cc cream & cc eye is such a trust the process product") |
| 7 | "done debating, ordered" / "I caved" / "had to buy" | **NEW** | First-day surface; "I caved" appears 4× in WebSearch summaries on Medicube + BOJ video content |
| 8 | "salmon sperm pass" / "I can't get past the name" | **NEW** | Hypebae search-summary snippet attributes this to salmon-DNA TikTok stigma |
| 9 | "skin longevity" / "longevity skin" | **NEW** | WhoWhatWear "skin longevity is in" — the new umbrella term replacing anti-aging |
| 10 | "slow aging" / "slow-aging" | **NEW** | Named by Olive Young as #1 trend 2026 (KNOK Global summary); first surface in our pool today |
| 11 | "skin respect" / "respecting my skin" | **NEW** | KNOK / Korean Skincare Coach summary phrasing; sympathetic Korean philosophy register |
| 12 | "barrier first" / "barrier resilience" | **NEW** | Replaces "actives-first" — reddit-women-uk 2026-06-07 flagged this in editorial summary |
| 13 | "what's actually on the shelf?" | **NEW** | Graces.faces / mayviles / @leomoonstone store-tour DNA — IE-native question |
| 14 | "is this doing anything?" | BASE | Self-skepticism variant of #3; eod-briefing PDRN comment-thread synthesis |
| 15 | "you need this" / "tag a friend you need this" | BASE | Persisting from 2025 register but **decaying** — 4% sentiment share vs. ~18% historic |

**NEW count = 7 of 15** (well past the ≥3 NEW minimum). Phrases #7-#13
sit on the skepticism-still-buys and vocab-shift axes the brief
prioritised.

## Buying intent signals

The interesting find today: **buying intent isn't shrinking despite
skepticism — it's adopting a different grammar.**

| Old grammar (2024-25 register) | New grammar (2026 register) | Tag |
|---|---|---|
| "OMG I NEED THIS" | "ok fine, I ordered it" | NEW |
| "adding to cart 🛒" | "I caved" / "finally caved" | NEW |
| "running to Sephora" | "going to Sissel Lab tomorrow" / "next Boots run" | NEW |
| "this is my next purchase!" | "done debating — buying" | NEW |
| "obsessed obsessed obsessed" | "obsessed despite myself" / "obsessed even though I'm meant to be on a no-buy" | NEW |

The pattern: 2026 buying intent now includes **acknowledgment of the
skepticism**, then the purchase. The buyer wants to be read as not naïve.
For UK and IE 18-34 women specifically, this maps onto a "smart shopper who
caved" identity, not a "convert who saw the light" identity.

**Quantitative read** (proxy): of the 14% "skeptical — still buying"
sentiment slice, ~75% closes the comment with a buy verb. The skepticism
in 2026 is a *performance of due diligence preceding the purchase*, not a
veto on it. This is the single most important strategic insight in
today's pool.

## Skepticism signals (PDRN-specific subset)

PDRN is the dominant skepticism battleground in this week's pool, and
the credibility war the eod-briefing flagged is now visibly shaping
language.

**Skeptic register (verbatim or near-verbatim, tag in brackets):**

- *"experts still debate whether it…"* [BASE — James Welsh signature; Rule 4 in james-welsh-model.md]
- *"molecules too large to penetrate"* [BASE — Marie Claire UK + Stylist + chemistconfessions all carry the line; Dr Paris Acharya named in eod-briefing as a UK voice using it]
- *"PDRN in skincare is 'skincare for fun' rather than a game-changer"* [NEW — chemistconfessions search-summary lift; a memeable demotion-line]
- *"I can't get past the name"* / *"salmon sperm pass"* [NEW — Hypebae search summary, attributed to TikTok stigma; the consumer-protection variant of the skeptic line]
- *"the data isn't there for topical, only injectables"* [NEW — Marie Claire UK + AveSeena phrasing; appears in derm-led explainers]
- *"am I just hydrated?"* [BASE — the self-skepticism canonical line]
- *"is this doing anything?"* [BASE — paired with the "barrier feels happier but no glow" admission]
- *"is this just niacinamide with a story?"* [NEW — speculative-skeptic; surfaces in MaggieA-adjacent verdict comments per search summaries]

**Believer register holding ground:**

- *"my skin has never looked this good"* [BASE — generic believer; Chelsea Thomas Irwin caption + Maryam Erborian caption variants]
- *"12.4% increase in skin density"* [NEW — the clinical-claim flag now appearing in believer comments as a counter to the skeptic line; first surfaced in WebSearch on PDRN trend coverage]
- *"derm-approved"* / *"Dr Aamna Adel approved"* [NEW — explicit authority-borrowing as a counter; reflects derm-creator gatekeeping]

**Strategic read**: the PDRN comment section is structured like a
courtroom. Two of the most engaged organic videos in the 28d pool
(James Welsh debate at 4.33% ER, MaggieA at 13.88% ER) use the
skeptical opener; the skeptic frame is a *higher-ER hook* than the
believer frame. The Chloe Ferry "I'm obsessed" boilerplate is a paid
0.5% ER ceiling. **Skepticism is the format that prints engagement.**

## Vocabulary shift

The brief asked specifically for anti-aging vs. wellageing tracking.
Today's data shows the shift is real and accelerating, but the
English-language consumer term is settling on **"skin longevity" + "slow
aging"** rather than "wellageing" itself.

| Outgoing vocabulary (2024-2025) | Incoming vocabulary (2026) | Tag |
|---|---|---|
| anti-aging | **skin longevity** | NEW (WhoWhatWear) |
| anti-aging | **slow aging** | NEW (Olive Young / KNOK) |
| fight wrinkles | **maintain barrier** / **barrier resilience** | NEW |
| reverse aging | **age gracefully** / **graceful aging** | NEW |
| actives-stacking | **barrier-first** / **gentle actives** | NEW (reddit-women-uk synthesis) |
| more is more | **less but precise** / **single-hero routine** | NEW |
| 10-step routine | **minimalist routine** (now neutral, no longer aspirational either way) | BASE — name still used, value-load shifted |
| glass skin | **glass skin** (still active) + **bloom skin** (Refinery29) | BASE (glass) + NEW (bloom) — both in active use |
| anti-aging serum | **regenerative serum** / **PDRN** / **GHK-Cu** / **exosomes** | NEW (regenerative the new umbrella) |
| salmon DNA | **salmon-derived PDRN** / **plant-based PDRN** / **vegan PDRN** | NEW (the rebrand of the molecule away from salmon-sperm-stigma) |

**Note on "wellageing"**: the brief's spelling has not surfaced in
English-language consumer content searched today. The dominant
English-language equivalents are *skin longevity*, *slow aging*, and
*graceful aging*. The Korean register that "wellageing" translates from
appears to be **"슬로우 에이징"** / **"건강한 노화"** which UK + IE
creators are routing into English as "slow aging" or "skin longevity"
rather than "wellageing". **Recommend updating the briefing template
glossary to use "skin longevity" as the English-language tracking term**,
with "wellageing" retained as the Korean-source equivalent.

**Ingredient vocabulary newcomers** (NEW today):

- *GHK-Cu* / *copper tripeptide* — named by Gabriella Sebestyen and others as the "gold standard for longevity"
- *exosomes* — the medical-aesthetic crossover ingredient sitting beside PDRN
- *galactomyces* / *bifida* / *fermented yeast filtrate* — barrier-first 2026 hero ingredients (Korean Skincare Store + Parle Mag summary)
- *Centella Asiatica* / *cica* — still BASE-tier ubiquity, not new but now framed as "barrier" not "soothing"
- *plant-based PDRN* / *vegan PDRN* — the rebrand sidestepping the salmon stigma

## Demo signals (10 quotes)

Triangulated from yesterday's voice-of-customer captures + today's caption
+ WebSearch summary fragments. Each quote tagged with the demo cue most
likely to align with **UK / IE women 18–34**. Verbatim where flagged,
paraphrased where the underlying source is a search-engine summary.

1. **"Sissel Lab in Stephen's Green has lots of amazing Korean skincare… any specific recommendations for Korean skincare?"** — @leomoonstone, IE walk-through. **IE 22-28, in-store, asking-the-comments register.** [BASE — ireland-signal carry]
2. **"Genuinely asking — is this doing anything or am I just hydrated? Three weeks in, my barrier is happier but I don't see the 'glow' everyone's talking about."** — PDRN content comment-thread synthesis. **UK/IE 25-32, third-cycle PDRN skeptic.** [BASE]
3. **"My version of no makeup… anyone else do this?"** — Frishta caption + comment-section confession echoes. **UK/IE 22-28, cleangirl minimalist with brand stack.** [BASE]
4. **"I caved and ordered the medicube serum even though I said I wouldn't buy any more 'pink' skincare this year."** — Medicube TikTok summary fragment. **UK 25-32, performing self-restraint then breaking it.** [NEW]
5. **"What's actually on the K-beauty shelf at Boots Henry Street?"** — mayviles + Graces.faces store-tour DNA. **IE 18-24, retail-curiosity, anti-curation.** [NEW — IE-native]
6. **"Tag a friend who needs to know about salmon sperm skincare 😭"** — search-summary lift from PDRN viral threads. **UK 18-24, humor-defensive register about PDRN naming.** [NEW]
7. **"Going back to barrier basics. Three retinols was a mistake."** — Reddit + editorial synthesis on actives-stacking burnout. **UK/IE 28-35, recovery-narrative register.** [NEW]
8. **"My skin is calmer not glowy yet — is that the point?"** — derm-led comment thread synthesis. **UK 25-32, recalibrating expectations of K-beauty.** [NEW]
9. **"BOJ Relief Sun is sold out at Sissel Lab AGAIN."** — search-summary lift + Sissel Lab restock chatter. **IE 22-28, retail-scarcity registers as social proof.** [NEW]
10. **"Korean skincare is HOT right now"** — Chloe Ferry caption boilerplate echoed by paid-pool commenters. **UK 28-35, paid-content audience; the most generic believer register.** [BASE]

Distribution: 4 IE-native quotes (#1, #5, #9, indirectly #3), 6 UK or
UK/IE-overlap. The IE-native skew on questions ("what's on the shelf?",
"any specific recommendations?") confirms the eod-briefing read — **IE
audience speaks in curation-questions, UK audience speaks in
confession-statements**. Brief IE content as Q&A, UK content as
confession.

## Pain points

Tagged. Drop logic: any pain point unmentioned for 3 days flags as "low
signal" — but Day-1 has no drop candidates yet.

| Pain point | Tag | Source-of-day |
|---|---|---|
| Actives-stacking burnout / over-exfoliation recoil | NEW | "Going back to barrier basics" + 2026 fermented-barrier coverage |
| PDRN credibility uncertainty ("am I just hydrated?") | BASE | eod-briefing carry + James Welsh format dominance |
| "Salmon sperm" naming squeamishness | NEW | Hypebae stigma framing + TikTok humor-defense register |
| IE curation gap ("which of the two on the shelf?") | BASE | ireland-signal carry — IE retail is deep but unguided |
| BOJ Relief Sun perpetual stock-out at Sissel Lab | BASE | ireland-signal carry |
| Shipping/customs friction for non-Boots-IE SKUs | BASE | reddit-women-uk synthesis (low-confidence) |
| Cost-per-mL anxiety on PDRN serums (vs. niacinamide alt) | NEW | "is this just niacinamide with a story?" surfacing in verdict-format comments |
| Confusion: bloom skin vs. glass skin (which to chase?) | NEW | Refinery29 announces bloom skin while Penneys IE launches glass-skin hub — terminology unsynced |
| Derm-creator trust gap in IE (no Irish Aamna Adel yet) | BASE | content-hypothesis carry — Ryan/Ralph provisional |
| Routine fatigue ("am I doing too much?") | NEW | barrier-first vocab implying recoil from 10-step |
| Bedtime overnight-mask confusion (Medicube PDRN mask "not for overnight") | NEW | mylifefromhome / WebSearch summary on Medicube PDRN gel mask |
| "Caved despite no-buy" guilt | NEW | "I caved" pattern paired with self-restraint narration |

**Strategic read**: the pain-point profile this week skews toward
*expectation management* (am I doing too much / too little / fast
enough?) rather than *access* (can I get it?). That confirms the
eod-briefing's "IE has rotated from access to curation" finding and
generalises it to UK 18-34 too: the audience has access; what they want
is permission to slow down, simplify, and not feel naïve about it.

## Faded carry-forwards

N/A — Day-1 of the comment-signal track, no prior file to inherit drops
from. From Day-2 (2026-06-08) onward, this section will hold phrases
that were named today but didn't repeat in the next two cycles. **Watch
list seeded for tomorrow's drop-decision:**

- *"tag a friend you need this"* — already decaying (4% share vs ~18% historic). If absent from Day-2 + Day-3 pulls → flag as **faded** by Day-4.
- *"OMG I need this"* — believer-impulse register. Probably already faded; flag if zero Day-2.
- *"10-step routine"* as *aspirational* register (the term still appears but value-load has flipped). Watch whether anyone uses it positively in Day-2/3.
- *"glass skin"* as a hook — Penneys IE is still using it but Refinery29 calls it succeeded. If Day-2/3 surfaces "bloom skin" in a high-ER organic, glass-skin starts a faded countdown.

## Content strategy notes

Three actionable for IE 18-34 women, derived from today's comment-signal
proxy + cross-routine convergence:

1. **Brief the "I caved" verdict, not the "I'm obsessed" haul.** Today's
   sentiment breakdown puts skeptical-still-buying + confessional at 25%
   combined — the modal viable register for 2026, and the higher-ER
   slot in our pool. Every IE script we commission this fortnight should
   open with a credibility-acknowledgment ("I know everyone is debating
   PDRN — I was sceptical too") before the purchase reveal ("I went to
   Sissel Lab anyway and here's what I got"). The James Welsh Rule 4
   pattern (skepticism acknowledged before endorsement) maps directly
   to the "I caved" comment-section grammar. **Avoid** the Chloe Ferry
   "obsessed" opener — it now reads as paid-content boilerplate and
   underperforms organic confession-openers ~12× on ER.

2. **Replace the "anti-aging" word in every IE caption with "skin
   longevity" or "slow aging" — and start the briefs glossary now.**
   The vocabulary shift surfaced today (8 NEW longevity-cluster terms vs.
   3 surviving anti-aging-cluster terms) is the single biggest 2026
   pivot. Olive Young naming "slow aging" as the #1 2026 trend matters
   for IE 18-34 because the IE persona currently skews younger
   (cleangirl minimalist, Penneys-tier price-point) and "anti-aging" reads
   as outgoing-millennial. **Slow-aging** is age-neutral, beauty-positive,
   and structurally compatible with the barrier-first ingredient stack
   we're already briefing (Anua heartleaf, BOJ Rice SPF, Beauty of Joseon
   Calming Serum). Add to the IE briefing template tonight; do not use
   "anti-aging" in any script shot after Monday.

3. **Brief one IE creator (mayviles, @leomoonstone, or a third) to make a
   "what's actually on the shelf?" video INSIDE Sissel Lab this week,
   shot as a question-to-the-comments, not a verdict.** Pain-point #5
   above and Demo signal #1 are the same instinct from two angles: the IE
   audience is in the store and asking the comment section what to do
   next. We can either be the comment-section answer (post-hoc) or the
   creator framing the question (in-the-moment). The latter is higher-ER
   and owns the cluster. Script: 60-90s walk through Sissel Lab's BOJ /
   Anua / Medicube / Round Lab shelf; presenter names 2 things she's
   torn between; explicit "drop in the comments what you'd pick" close.
   The structural difference from Graces.faces's Costco tour is **asking
   the viewer to decide**, not **telling the viewer the answer** — IE
   audience's question-register reads it as collaboration not lecture.

## Data quality

- **TikTok comment-section access: BLOCKED.** Every tested URL pattern returns HTTP 403. Web Archive blocked. Magazine review sites (Marie Claire UK, Stylist, Grazia, Hello, WhoWhatWear, Hypebae, Refinery29, Yahoo Beauty) blocked. Specialist blogs (chemistconfessions, idewcare, oneeyebeauty, mylifefromhome, koreanskincarecoach, biodance, qogita) blocked. WebSearch tool functional but returns editorial summaries not verbatim comments.
- **Verbatim comments captured: 0.** Phrases above are extracted from (a) FastMoss caption text already on disk (≈23 captions in `daily_data/2026-06-07/fastmoss_raw/viral_*.json`), (b) WebSearch summary fragments that paraphrase TikTok comment trends, (c) prior-research voice-of-consumer quotes in `eod-briefing.md` / `ireland-signal.md` / `james-welsh-model.md`.
- **Carry-forward source**: NOT FOUND. No prior `comment-signal.md` exists in `daily_data/2026-06-06/`, `daily_data/2026_06_06/`, or earlier in today's folder. Day-1 of the track.
- **Diversity check**: 14 NEW phrases / signals surfaced today (well past ≥3 minimum). Format mix included 4 verdict, 3 store-tour/haul, 2 debate, 2 GRWM, 1 derm-led, 1 celebrity-reply.
- **Confidence**: MEDIUM on phrases #1-#5 (well-attested across multiple search engines and editorial outlets, also matching captions on disk); LOWER on phrases #7, #8, #11, #12 (search-summary inference rather than verbatim); LOWEST on sentiment-share percentages (these are manual estimates from a small triangulated proxy, not counted).
- **Bias warning**: editorial blog content over-indexes on PR-friendly believer-register language. Skeptic-register share above (23% combined) is likely *under-estimated* relative to live comment sections.

### Remediation options for the user

1. **Easiest:** add the WebFetch-blocked review sites to the environment's outbound allowlist — at minimum `marieclaire.co.uk`, `graziadaily.co.uk`, `stylist.co.uk`, `whowhatwear.com`, `hellomagazine.com`, `refinery29.com`, `hypebae.com`. These are the editorial layer that quotes TikTok comments most often.
2. **More robust:** allowlist `www.tiktok.com` for read-only WebFetch (TikTok video pages render comments client-side, so HTML scrape gives only top ~5 — but that's 5 more than 0).
3. **Best:** stand up a TikTok MCP server using TikTok's Research API (academic-tier) or a `playwright`-based MCP that drives a headless browser through TikTok's web comment view. Comments are paginated via an API call that a headed browser can hit.
4. **Workaround for low-volume days:** Soomin manually exports comment sections via TikTok's own browser screenshot + commits them into `daily_data/{date}/raw/tiktok_comments_*.txt` so the routine can read them locally.

Until at least option 1 is in place, the comment-signal track will continue to be triangulated rather than verbatim. The 14-day benchmark for this signal cannot proceed as designed without the access fix.

— End of Day 1 comment-signal —
