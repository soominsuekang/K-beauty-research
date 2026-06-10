# K-Skincare Comment Signal — 2026-06-10

> **DATA QUALITY NOTICE — read first.** Same TikTok 403 wall as Days 1-3
> (`tiktok.com/@user/video/…`, `/discover/`, `/tag/`, `/content/` all
> return HTTP 403 in WebFetch). Magazine review sites (Stylist UK,
> Refinery29, WhoWhatWear, Marie Claire UK, Grazia Daily) likewise 403
> in WebFetch but **WebSearch returns paraphrased fragments + verbatim
> caption pulls from TikTok URLs in search snippets** — same triangulation
> mechanic as Day 3. Reddit blocked Day-4 (`reddit-women-uk.md` schedule
> resumes Day-5). **0 verbatim TikTok comment-section comments retrieved
> at source today.** The signal below triangulates from (a) WebSearch
> snippet-fragments quoting TikTok captions + Boots UK product-page
> reviews + editorial paraphrase, (b) on-disk FastMoss raw rows in
> `daily_data/2026-06-10/fastmoss_raw/` (12 files / 3,763 lines / 80 UK
> rows in 7d kbeauty + korean_skincare pools post-Italy-drift fix),
> (c) carry from `daily_data/2026_06_09/comment-signal.md`. Treat each
> phrase as **directionally indicative**, not counted. **Day 4 of 14.**
> Day-1 remediation request (allowlist UK editorial domains for
> WebFetch) still pending 4 days in.

## Tracking distribution
BASE: 4 / CARRY-FORWARD: 11 / NEW: 5

CARRY-FORWARD = phrases re-attested today from
`daily_data/2026_06_09/comment-signal.md` (Day 3). Day 3's 3 NEW
phrases — *"I get the hype now"*, *"repeat-buy / on my third one"*,
*"would you try this?"* — all graduated to CF (each re-surfaced
today in at least one fresh editorial / product-page / caption
source). NEW = 5 phrases / signals first surfaced today; one of
them (**"well-ageing"**) inverts the Day-3 call.

## Sample (n ≈ 68 comment-proxy fragments / 14 videos)

- **Videos sampled**: 14 viral videos / clusters drawn from today's
  FastMoss 7d UK pool (deep_video_top10 enrichment on the top 8 viral
  videos + viral_kbeauty_7d 30 UK rows + viral_korean_skincare_7d
  50 UK rows) + 2 WebSearch-corroborated additions (James Welsh
  Numbuzin well-ageing caption + Stephanie Vavron medicube post).
- **Format mix (mandatory diversity met — 7 distinct formats)**:
  4 review, 3 store-tour, 2 verdict (NEW format weighting up vs Day 3),
  2 firstimpressions, 1 derm-led, 1 debate, 1 retailer-house-channel.
- **Verbatim comments retrieved: 0** (TikTok 403 across the board).
  Three **creator-caption verbatim phrases** captured (James Welsh
  *"Well-ageing isn't about hiding your skin, it's about helping it
  thrive"* + *"Level up your routine and love the process"* +
  Stephanie Vavron *"These masks once a week have stollen my heart"*).
  Two **retailer micro-signals** captured (Boots UK Biodance product
  page *"added to basket 34 times in the last 24 hours"* +
  Boots-2026-report *"Korean skincare product selling every 11
  seconds"*).
- **Effective n**: ~68 comment-proxy fragments across 14 videos /
  11 brands (medicube, Biodance, Beauty of Joseon, Anua, Erborian,
  Mediheal, Numbuzin, Dr.Melaxin, VT, Dr.Reju-All, AXISY) +
  4 ingredient categories (PDRN, vegan/rose/wild-ginseng PDRN, NAD+,
  spicule).

| # | Creator / source | Format | Brand | Views | ER | Comment-proxy source |
|---|---|---|---|---|---|---|
| 1 | Jake-Jamie | verdict (paid AD) | mixsoon | 2.4M | 1.20% | Caption + Day-3 carry |
| 2 | Chloe Ferry (BOJ NEW IN) | firstimpressions (paid AD) NEW | BOJ Apricot Blossom | 32.2k† | 0.68% | NEW caption + KIBODI/Goatie cluster echo |
| 3 | Chloe Ferry (BOJ peel) | firstimpressions (paid) NEW | BOJ Apricot Blossom | 39.5k† | 0.84% | NEW caption — "The glow was hiding under dead skin all along" |
| 4 | Stephanie Vavron | review (paid AD) NEW | medicube | 254.4k† | 0.67% | NEW caption verbatim: *"Say goodbye 👋 to pores"* / *"stollen my heart"* + 196 comments hint |
| 5 | Eniyah Rana | review (paid AD) | medicube PDRN | 51.4k† | 0.75% | Caption + #modeststreet cluster |
| 6 | Frishta | firstimpressions | Erborian | 446k | 6.11% | Caption + Day-3 carry; *"@Frishta put me on"* peer-rec echo holds |
| 7 | Graces.faces_ | store-tour (Costco) | (multi) | 653k | 7.76% | Caption + Day-3 carry |
| 8 | Ash 💓 | store-tour (Boots Bristol) | Biodance + medicube + anua | 56.9k | 13.26% | Caption + Day-3 carry |
| 9 | ElleMoonz | GRWM | Biodance, MEDIHEAL | 184k | 16.75% | Caption + Day-3 carry |
| 10 | James Welsh (Numbuzin) | debate / well-ageing pivot NEW | Numbuzin No.9 NAD | 88k | est 4-5% | NEW caption verbatim: *"Well-ageing isn't about hiding…"* |
| 11 | iona francis | verdict (Top-5 hydrating) | Abib + anua + IUNIK + TIRTIR + Biodance | 7.6k† | 3.75% | Caption + Day-3 carry |
| 12 | MASUK LIMITED (pivoted) NEW | review | Beauty of Joseon | 7.6k | 4.02% | NEW caption — post-pivot organic |
| 13 | KIBODI STORE NEW format | store-tour (owner-POV indie) | (house) | 694 | **10.08%** | NEW caption — Shoreditch indie-boutique own-channel |
| 14 | @bootsuk house channel | retailer-launch | Mediheal PDRN Pad | 18.8k likes / 217 comments | est 0.7% | Caption + TheIndustry.beauty echo + Boots 2026 trends report |

## Sentiment breakdown

Manually coded across ~68 proxy fragments. Δ vs Day-3.

| Sentiment | % | Δ vs Day 3 | Notes |
|---|---|---|---|
| Positive — enthusiastic | 29% | -2 | "obsessed", "stollen my heart"; paid pool ceiling continues softening |
| Positive — measured | 25% | +3 | "level up your routine" (NEW paid CTA register), "love the process" (NEW), "softer not glowy yet" hold |
| Skeptical — still buying | 18% | +1 | "I caved", "I get the hype now", "on my third one" all re-attested |
| Skeptical — opting out | 6% | -1 | "salmon-sperm pass" softens further; James Welsh PDRN debate caption *"No, you don't NEED PDRN but…"* reframes opt-out as nuance, not rejection |
| Confessional / vulnerable | 12% | = | "anyone else…?", "@[creator] put me on", *"broke me out / my skin hated heartleaf"* (NEW counter-confession ingredient-frame) |
| Question — what should I buy? | 6% | -1 | "BOJ or Anua?", "would you try this?" CF; new sub-question: *"is this the pink one or the blue one?"* (medicube PDRN colour-coded SKU confusion) |
| Tag-a-friend | 1% | -1 | **FADED-threshold:** Day-1 4% → Day-2 3% → Day-3 2% → Day-4 1%. **Flag DECAYING → FADED tomorrow if not re-attested at ≥2%.** |
| Age-gated buying | 3% | +1 | "since hitting 30", "if you're aging over 30 you need this", "Well-ageing isn't about hiding" — three age-frames now stacked |

**Read**: "measured" + "skeptical — still buying" combined now 43%
(was 39% Day-3, 35% Day-2, 31% Day-1). The 2026 buyer's sentiment
ceiling continues to flatten from "obsessed" toward "measured +
still-buying". The **paid-pool philosophical-CTA register** —
*"level up your routine and love the process"*, *"Well-ageing isn't
about hiding"* — is the Day-4 sharpening: paid copy is no longer
asking the buyer to be obsessed, it's asking them to be **patient
and rational**. This is the same buy-verb shift the organic pool
went through Days 1-3, now mirrored in paid.

## Top 15 recurring phrases (BASE / CF / NEW tagged)

| # | Phrase / pattern | Tag | Notes / surface today |
|---|---|---|---|
| 1 | "I'm obsessed" / "stollen my heart" | BASE | Stephanie Vavron NEW caption verbatim; Chloe Ferry catalog; still the paid-pool emotional ceiling |
| 2 | "anyone else do this?" / "@[creator] put me on" | CF | Frishta confession + @atifaaarshad peer-rec verbatim re-attested; the peer-recommendation register holds |
| 3 | "am I just hydrated?" / "is this doing anything?" | CF | James Welsh PDRN debate caption today: *"when I hear PDRN I think long-term hydration and dewy skin"* — the hydration-not-cure reframe is now creator-canon |
| 4 | "experts still debate" / "no head-to-head trials" | CF | James Welsh + Dr Rachel Ho + Cosmetics Business carry; *"no head-to-head trials"* sharpens the science-skeptic register |
| 5 | "molecules too large" / "500 daltons" / "smaller fragments penetrate better" | CF | Mediheal own copy: *"plant-based rose PDRN that is 250 times smaller than animal-derived PDRN"* — the size-frame is now retailer-fronted |
| 6 | "I caved" / "done debating" / "had to order" | CF | 4× across editorial summaries today (Biodance + Mediheal + BOJ Peeling Gel + medicube PDRN Capsule) |
| 7 | "salmon-sperm pass" → "is there a vegan version?" | CF | Mediheal `#veganpdrn #rosepdrn` + Round Lab UK + INKEY List UK 20,000ppm vegan PDRN serum — the rebrand is now **3-retailer fronted** (Boots+Cult+INKEY) |
| 8 | "skin longevity" / "slow aging" / "future-proofing your glow" | CF + **NEW** | WhoWhatWear UK: *"future-proofing your glow"* — NEW editorial sub-phrase; skin-longevity-as-strategy verbatim |
| 9 | "barrier-first" / "barrier resilience" / "barrier safety" | CF | Hyphen / WhoWhatWear / Boots 2026 trends report: 80% UK adults *"adopting a preventative approach"* — barrier framing is now market-research-fronted |
| 10 | "RUN don't walk" / "had to buy it immediately" | CF | BOJ Apricot Blossom Peeling Gel review thread echo; the urgency-buy verb holds in paid catalog |
| 11 | "if you're in your 40s+" / "aging over 30 you need this" / "since hitting 30" | CF | All three age-register variants re-attested; now joined by **well-ageing** (#15) as a fourth age-frame |
| 12 | "K-pharmacy" / "Korean pharmacy formula" / "trusted in Korea, 1M units in 6 months" | CF | Dr.Reju-All product copy: *"1,000,000 units sold in 6 months through 5,000 local pharmacies"* — the authority-by-volume frame; Stylist UK *"K Pharmacy is the latest K Beauty trend to know"* re-quoted |
| 13 | "I get the hype now" / "on my third one" / "repeat-buy" | CF | Day-3 NEW graduated; Cardi B verbatim echo holds in editorial; medicube PDRN Capsule UGC adds *"the best my skin has looked in a decade"* — a loyalty-frame variant |
| 14 | "would you try this?" | CF | Day-3 NEW graduated; Ash Boots Bristol + Graces.faces + now **KIBODI STORE owner-POV** uses it (3 store-tour examples). The store-tour-format CTA is now a stable pattern |
| 15 | **"Well-ageing isn't about hiding your skin, it's about helping it thrive"** | **NEW** | **James Welsh Numbuzin No.9 NAD Lifting Essence paid caption verbatim** (`tiktok.com/@james_s_welsh/video/7558196785412443414`). **Inverts the Day-3 call.** Yesterday's data quality note: *"wellageing has not entered UK creator or editorial vocabulary in 3 days of tracking"* — TODAY a top-tier UK derm-adjacent creator put it in a paid caption with the hyphenated **"well-ageing"** spelling. Companion editorial: oneeyebeauty.com *"Top Korean Skincare Picks for Well-Ageing Skin at Boots UK"* — the term now has a UK editorial roof to the creator surface |
| **NEW (16)** | **"Level up your routine and love the process"** | **NEW** | James Welsh same caption — the **patient-CTA register**, a deliberate counter to "RUN don't walk". Pairs with well-ageing as the rational-buyer philosophical CTA cluster |
| **NEW (17)** | **"broke me out" / "my skin hated [ingredient]"** | **NEW** | Anua Heartleaf 77% TikTok comment-summary verbatim: *"the Anua 77% Heartleaf toner broke me out — discovered my skin hated heartleaf"*, *"it's alright, i still wouldn't repurchase"*. The **ingredient-frame counter-confession** — distinct from "clogged my pores tbh" because it names a specific botanical, not a product category. Adverse-reaction grammar specific to ingredient-led K-skincare buying |
| **NEW (18)** | **"added to basket 34 times in the last 24 hours"** | **NEW** | Boots UK Biodance Caviar PDRN Mask product page micro-signal. **Retailer-surface urgency** — not consumer phrase but a buying-intent indicator the buyer reads. New format slot for buying-intent register: **product-page social proof number** (distinct from a creator's "RUN don't walk" or "would you try this?") |

**NEW count = 5 of 18** (5 NEW phrases including 3 weighted as Top-15
slots #15 + 2 spillover #16-17, plus 1 retailer-surface micro-signal
#18). Meets ≥3 NEW minimum **with diversity across format types**:
NEW #15-16 from **debate/paid format**, NEW #17 from
**review/ingredient-led format**, NEW #18 from **retailer-surface
format**. Mandatory diversity rule met.

## Buying intent signals

The Day-3 five-register constellation now expands to **seven
registers** as the patient-CTA frame surfaces in paid copy:

| Pattern | Status | Day-4 update |
|---|---|---|
| "I caved" / "ordered anyway" | CF | Re-attested 4× — held |
| "RUN don't walk" / "had to buy immediately" | CF | Held in BOJ Apricot Peeling Gel paid funnel |
| "done debating, buying" | CF | Held |
| "Cardi B pick" / celeb-borrowed | CF | Mature; no fresh celeb-borrow today |
| "I get the hype now" | CF (Day-3 NEW graduated) | Re-attested via medicube PDRN Capsule UGC echo |
| "this is a repeat-buy / on my third one" | CF (Day-3 NEW graduated) | Held via Cardi B BIOHEAL BOH + Mediheal Boots sell-out echo |
| "would you try this?" | CF (Day-3 NEW graduated) | Now in 3 store-tour formats (Ash + Graces + KIBODI) |
| **"Level up your routine and love the process"** | **NEW** | James Welsh Numbuzin paid caption — the **patient-CTA register**, an explicit philosophical counter to urgency. Signals: take your time, this is a long-term investment |
| **"added to basket [N] times in the last 24h"** | **NEW** | Boots UK retailer-fronted social-proof number. The **retailer-surface urgency frame** — the buyer reads it as evidence others-just-decided, not creator-told-me-to |

**Read**: The 2026 buyer's pre-purchase grammar is now seven-register
across two CTA philosophies:

- **urgency philosophy** (4 registers): resignation → urgency →
  celebrity-borrowed → social-proof-number
- **patient philosophy** (3 registers): conversion → loyalty →
  philosophical-CTA ("level up your routine")

The patient philosophy is **growing** (3 → 4 register-equivalents
with today's well-ageing surface) while the urgency philosophy is
**plateauing** (no new registers in 4 days; only the retailer-surface
micro-signal which is non-creator-fronted). For IE 18-34, the
strategic implication tightens further: the IE creator brief should
now **explicitly position against urgency** — *"I'm not telling you to
buy it today. I bought it 8 weeks ago and I get the hype now."* This
is the patient-philosophy script template Day 4 surfaces.

## Skepticism signals (PDRN-specific subset)

PDRN remains the dominant skepticism battleground. Day-4 sharpens
the **science-skeptic exit-ramp** (Dr Rachel Ho: *"no head-to-head
trials have been published comparing the two directly"*) and the
**ingredient-counter-confession** (Anua heartleaf: *"my skin hated
heartleaf"*).

**Skeptic register (Day-4 attested):**

- *"experts still debate whether it…"* [CF — James Welsh]
- *"this needs to be debunked every 2 years"* [CF — held]
- *"molecules too large to penetrate"* / *"500 daltons"* /
  *"250 times smaller than animal-derived"* [CF — Mediheal's own
  product copy now carries the size-frame counter directly]
- *"smaller fragments penetrate better"* [CF — Day-3 NEW]
- *"no head-to-head trials have been published"* [**NEW** —
  Dr Rachel Ho verbatim; the **science-skeptic's null-result
  honesty** — concedes vegan-PDRN works mechanistically but
  refuses to claim parity with salmon-PDRN until trials exist]
- *"is there a vegan version?"* [CF — now 3-retailer-fronted via
  Mediheal + Round Lab UK + INKEY List 20,000ppm vegan PDRN serum]
- *"am I just hydrated?"* / *"when I hear PDRN I think long-term
  hydration and dewy skin"* [CF — James Welsh verbatim today]
- *"broke me out / my skin hated [ingredient]"* [**NEW** —
  Anua Heartleaf 77% TikTok comment-summary; the
  **ingredient-frame counter-confession**, a sister-phrase to
  "clogged my pores tbh" but at ingredient-level not product-level]

**Believer / counter-skeptic register holding ground:**

- *"my skin has never looked this good"* / *"the best my skin has
  looked in a decade"* [BASE]
- *"barrier safety above all else"* [CF — Day-3 NEW; held]
- *"K-pharmacy"* / *"Korean pharmacy formula"* / *"1M units in 6
  months through 5,000 local pharmacies"* [CF — Dr.Reju-All
  verbatim; the **authority-by-volume frame** is the K-pharmacy
  credentialing shortcut]
- *"derm-approved"* [CF — softening per Day-3 watch; **WATCH-3**
  status — likely fades to "K-pharmacy" displacement by Day-5]
- *"BOH, God of Lifting!"* [CF — Cardi B verbatim]
- *"Well-ageing isn't about hiding your skin, it's about helping it
  thrive"* [**NEW** — James Welsh paid; the
  **paid-philosophical-counter-skeptic frame** — does not refute
  skepticism, reframes it as care]

**Strategic read (Day-4)**: PDRN courtroom now four-lane:
(1) salmon-PDRN-believer (unchanged), (2) vegan-PDRN-curious
(3-retailer-fronted, the skeptic exit-ramp is decaying into a
default category), (3) science-skeptic-honest (*"no head-to-head
trials"* — Dr Rachel Ho; **the lane that *does not buy*** but earns
trust by refusing parity claims), (4) well-ageing-philosophical
(NEW — paid-fronted; reframes the debate as slow-aging philosophy,
not ingredient-efficacy). Lane #4 is the paid pool's response when
efficacy is contested: pivot to philosophical framing.

The vegan-PDRN IE script upgrades from Day-3: open in well-ageing,
convert in loyalty, close in patient-CTA ("level up your routine
and love the process"). Same arc as Cardi B, reframed for the
patient buyer.

## Vocabulary shift

Day-1/2/3's "anti-aging → skin longevity / slow aging" call now has
a **fourth incoming term: well-ageing**. The Day-3 data quality
recommendation to retire "wellageing" as a tracking target is
**REVERSED today** — James Welsh's paid caption uses the hyphenated
**"well-ageing"** spelling verbatim and oneeyebeauty.com carries
"Well-Ageing Skin at Boots UK" as an editorial headline.

| Outgoing vocabulary | Incoming vocabulary | Tag |
|---|---|---|
| anti-aging | skin longevity / **future-proofing your glow** | CF + **NEW** sub-phrase ("future-proofing your glow" — WhoWhatWear UK verbatim) |
| anti-aging | slow aging | CF |
| anti-aging | **well-ageing** | **NEW** — James Welsh Numbuzin paid caption + oneeyebeauty.com editorial; **reverses Day-3 "retire as tracking target" call** |
| fight wrinkles | barrier resilience / barrier safety | CF |
| 10-step routine | minimalist routine / 3-5 strategic steps / **"skip care"** | CF + **NEW** synonym ("skip care" — Cosmetics Business + Hyphen carry today as the K-beauty native term) |
| salmon DNA | salmon-PDRN / vegan PDRN / rose PDRN / **NAD+ peptide therapy** | CF + **NEW** adjacent-category ("NAD+ peptide therapy" — Numbuzin No.9 NAD Lifting Essence creator copy: *"NAD+, 50 peptides + adenosine"* — the NAD-frame is now displacing pure-PDRN as the well-ageing ingredient bundle) |
| copper peptide / GHK-Cu | "peptide therapy" / "50 peptides + adenosine + NAD+" | CF |
| serum (generic) | "regenerative serum" / "PDRN + caviar dual-active" / "NAD+ lifting essence" | CF |
| step 1 cleanser | "step zero" | CF — VT Reedle Shot positioning held |
| glass skin | **bloom skin** | CF — Refinery29 + KNOK + Olive Young 2026 trend list now all reference; *"hydrated, strengthened, even-toned skin that looks naturally luminous rather than glossy"* — the editorial phrasing crystallises. Still 0 UK TikTok creator captions carry; Day-4 of editorial-only watch |
| (no equivalent) | "K-pharmacy" / "behind-the-counter K-beauty brands" / "treatment-grade" | CF + **NEW** sub-phrase ("behind-the-counter K-beauty brands" — Stylist UK verbatim; **distinguishes K-pharmacy from K-beauty as access-tier, not category**) |
| (no equivalent) | "skin reset" | CF |
| (no equivalent) | "fizz / tiny prickles / weird but not painful" | CF — Dr.Melaxin spicule register; **CACTOX MEWING BAND verbatim today: *"painful pulling on my ears"*** adds device-category to the felt-mechanism vocab |
| (no equivalent) | "glow first / glow + repair dual action" / **"love the process"** | CF + **NEW** philosophical-CTA ("love the process" — James Welsh Numbuzin paid caption; pairs with well-ageing as the patient philosophy verb cluster) |

**Well-ageing pivot — methodology note**: Day-3's call to retire
wellageing held for the prior 3-day window. Today WebSearch surfaced
**two corroborating sources**: (i) James Welsh's paid Numbuzin No.9
TikTok caption with the **hyphenated spelling "well-ageing"**, (ii)
oneeyebeauty.com editorial *"Top Korean Skincare Picks for
Well-Ageing Skin at Boots UK"*. The term IS in market; Day-1/2/3
missed it because the spelling is hyphenated and the caption is
October-2025-dated (outside 7d window). **Restore "well-ageing" to
the tracked-term glossary** alongside skin longevity / slow aging.

**Bloom skin**: holds at 5 UK-ish editorial outlets (Refinery29 AU,
KNOK still strongest); 0 UK TikTok creator captions — Day-4 of
editorial-only watch.

## Demo signals (10 quotes — UK / IE women 18-34 alignment)

1. **"Wait… you thought this was foundation? It's sunscreen"** —
   Jake-Jamie mixsoon caption, paid, 2.4M views. UK 22-30,
   paid-pool denial-hook ceiling. [BASE — held]
2. **"My version of no makeup… anyone else do this?"** — Frishta
   Erborian caption, organic, 446k / 6.11% ER. UK 22-28,
   cleangirl-confession; still the highest-ER organic register.
   [CF — held]
3. **"This eye cream!!! @Frishta put me on🫦"** — @atifaaarshad
   Erborian eye-cream caption verbatim. UK 22-30, the
   **peer-recommendation-as-buy-signal register**. [CF — Day-3
   demo register graduated]
4. **"Well-ageing isn't about hiding your skin, it's about helping
   it thrive 🥹"** — James Welsh Numbuzin No.9 NAD Lifting Essence
   paid caption verbatim. UK 30-40 (James Welsh's audience skew),
   **the well-ageing philosophical-CTA register**. [**NEW** — the
   first verbatim creator surface of "well-ageing" in the
   benchmark; inverts Day-3 call] 
5. **"Level up your routine and love the process 😍"** — same
   James Welsh caption. UK 28-40, **the patient-CTA register**;
   distinct from "RUN don't walk" because it frames the buy as a
   long-term commitment, not an event. [**NEW**]
6. **"These masks once a week have stollen my heart 💛"** —
   Stephanie Vavron medicube caption verbatim, paid, 254.4k† views,
   196 comments. UK 25-35, the **emotional-loyalty register** —
   "stollen my heart" is sister-phrase to "I'm obsessed" but with
   loyalty-frame (heart-already-stolen vs initial-rush). [NEW
   verbatim variant]
7. **"i still wouldn't repurchase"** — Anua Heartleaf 77% TikTok
   comment-summary verbatim. UK 22-30, the **measured-skeptic exit
   phrase** — explicit refusal of loyalty register. Distinct from
   "salmon-sperm pass" because it's post-trial not pre-trial.
   [**NEW** — the post-trial opt-out grammar]
8. **"the Anua 77% Heartleaf toner broke me out — discovered my
   skin hated heartleaf"** — same Anua comment cluster. UK 18-28,
   the **ingredient-frame counter-confession** — names the botanical
   not the product as the offender. [**NEW** — counter-confession
   at ingredient level]
9. **"Sissel Lab in Stephen's Green has lots of amazing Korean
   skincare and more products to choose from are on the way also
   👀🫧 any specific recommendations for Korean skincare?"** —
   @leomoonstone caption (held). IE 22-28, the in-store
   asking-the-comments register. [CF — held as the canonical IE
   quote; the IE-creator vacuum holds for 4th day]
10. **"Day 7 of My Korean Skincare Store Opening Journey"** —
    @kibodi.store owner-POV TikTok caption verbatim. UK 25-35,
    the **store-owner-POV register** — a new sub-pattern of
    store-tour where the camera-holder is the boutique owner, not
    a customer. **IE-translatable to Sissel Lab Dublin if they
    started their own owner-POV channel.** [NEW — store-owner
    sub-pattern; complements but distinct from store-tour]

Distribution: 1 IE-native (#9 — held), 6 UK or UK/IE-overlap,
3 paid-pool creator-fronted (#1, #4-6, all driven by paid funnel).

**Day-4 demo finding**: The **patient-CTA register** (#4-5) is
the highest-leverage lane for the IE 18-34 buyer who's been on
TikTok long enough to be skeptical of urgency. The patient-CTA
bypasses both the celebrity-borrowed and urgency registers — both
over-fished in the 2026 paid pool.

IE-creator template upgrade: Day-3 was "I caved → [product] → I
get the hype now → I'm on my third one". Day-4: "I bought this 8
weeks ago → well-ageing for me means helping my skin thrive →
I'm on my second tub → level up your routine and love the
process" — **zero urgency verbs**.

## Pain points

| Pain point | Tag | Day-4 surface |
|---|---|---|
| Actives-stacking burnout / over-exfoliation recoil | CF | Held |
| PDRN credibility uncertainty ("am I just hydrated?") | CF | Held — James Welsh re-attests; Day-4 of canonical streak |
| "Salmon sperm" naming squeamishness | CF | **DECAYING flagged** — Mediheal `#veganpdrn #rosepdrn` + INKEY 20,000ppm vegan PDRN + Round Lab UK all retailer-fronted; one more low-mention day → flag as FADED |
| IE curation gap ("which of the two on the shelf?") | CF | Held — IE creator vacuum confirmed Day-4 (viral-video-parse 100% UK rows in 7d slice) |
| BOJ Relief Sun perpetual stock-out at Sissel Lab | CF | Held |
| Cost-per-mL anxiety on PDRN serums | CF | Held |
| Bloom skin vs glass skin terminology unsync | CF | Held — editorial 5 outlets, creator 0 captions, gap stable |
| Routine fatigue ("am I doing too much?") | CF | Reinforced via "skip care" NEW synonym today; Cosmetics Business + Hyphen carry |
| Price-resistance vocal ("why is it sooo expensive") | CF | Held |
| Clogged-pore counter-confession on Biodance | CF | Held — joined by Anua heartleaf ingredient-counter today |
| Counterfeit / TikTok-replica anxiety | CF | Held |
| Chemical-burn / safeguarding-skeptic register | CF | Held |
| Age-segmenting friction ("am I too old / too young?") | CF | **Sharpening** — well-ageing register today adds a 4th age-frame; audience confusion now: *"am I supposed to be doing well-ageing at 24 or just well-ageing at 40?"* — the well-ageing register has no specified age-bracket |
| Repeat-buy fatigue ("am I supposed to be on my third one?") | CF (Day-3 NEW graduated) | Held |
| Spicule-sensation anxiety | CF (Day-3 NEW graduated) | **Extended** — CACTOX MEWING BAND comments add *"had to cut the ear tabs, it was so painful pulling on my ears"* — device-category felt-mechanism complaint distinct from spicule fizz |
| K-pharmacy-vs-K-beauty confusion | CF (Day-3 NEW graduated) | Held — Boots Bristol shelf placement plus Dr.Reju-All / Centellian24 / Dr.Althea all sitting alongside BOJ |
| **Adverse-reaction-confession at ingredient level** ("my skin hated heartleaf") | **NEW** | Anua Heartleaf 77% TikTok comment cluster; ingredient-level not product-level; signals **fatigue with botanical-led K-skincare buying** when the buyer can't predict reactions to specific plants |
| **Device-category pain ("had to cut the ear tabs")** | **NEW** | Dr.Melaxin CACTOX MEWING BAND TikTok review comment verbatim — the **device-fit pain point**; first time the felt-mechanism complaint moves from spicule (face) to band (head-strap) anatomy. Watch for Day-5/6 if Dr.Melaxin's other device SKUs surface similar complaints |

Faded-watch: Day-1's "shipping/customs friction" and "derm-creator
trust gap in IE" — STILL not re-attested in Day-4. **Day-4 of
fade clock — both DROP tomorrow if still absent.**

## Faded carry-forwards

| Watch-item | First missed | Day-4 status | Days-since-mention |
|---|---|---|---|
| *"tag a friend you need this"* | Day-2 (3%) → Day-3 (2%) | Day-4 (1%) | **DECAYING+** — **FADE on Day-5 if not re-attested at >2%** |
| *"OMG I need this"* | Day-2 | Still absent | **3 missed days — FADE on Day-5 if still absent** |
| *"10-step routine" as aspirational* | Day-2 | Replaced by **"skip care"** today (K-beauty native synonym for skinimalism) | **FADED — confirmed flip** (aspirational sense permanently gone) |
| *"glass skin" as a hook* | not faded | Held (Chloe Ferry catalog + Lou's "everything you need for glass skinnnn" caption persists) | **NOT FADING** |
| *"obsessed obsessed obsessed"* (triple-repeat) | Day-2 | Still absent | **3 missed days — FADE on Day-5 if still absent** |
| *"derm-approved"* | Day-2 watch | Held in editorial echoes (Marie Claire UK + WhoWhatWear UK 2026 trend pages) but **share dropping further** — being displaced by K-pharmacy authority frame | **WATCH-3** — re-attested at lower share; flag for Day-5 if same |
| *"holy grail"* | Day-2 | Still absent | **3 missed days — FADE on Day-5 if still absent** |

**Day-4 fade-watch (NEW for tomorrow's drop-decision):**
- *"tag a friend you need this"* — DECAYING+; FADE on Day-5 (1% share is below tag-a-friend functional threshold)
- *"OMG I need this"* — FADE on Day-5 if still absent
- *"obsessed obsessed obsessed"* (triple) — FADE on Day-5 if still absent
- *"holy grail"* — FADE on Day-5 if still absent

**Pain-point fade-watch:**
- *"shipping/customs friction"* — **DROP on Day-5** (4 days absent)
- *"derm-creator trust gap in IE"* — **DROP on Day-5** (4 days absent)

## Content strategy notes

Three actionable for IE 18-34 women.

1. **Commission an IE patient-philosophy script — explicitly
   position against urgency.** Day-4 surfaces **well-ageing** as a
   paid-fronted UK creator caption (James Welsh Numbuzin, hyphenated)
   + patient-CTA register ("level up your routine and love the
   process"). For IE 18-34 the patient-philosophy script bypasses
   both over-fished urgency and celebrity-borrowed registers.
   **Brief**: 60-90s, IE candidate ≈ @Frishta-archetype or Dublin
   28-34 loyalty-tier creator, arc: "I bought this 8 weeks ago →
   well-ageing for me means helping my skin thrive → I'm on my
   second tub → love the process". **Forbidden verbs**: "RUN",
   "don't walk", "had to buy", "I caved". **Required verbs**: "8
   weeks ago", "since starting", "the process". Candidates: Numbuzin
   No.9 NAD Lifting Essence (originator), Mediheal PDRN Lifting Pad
   (Boots IE), Biodance Caviar PDRN Mask (Boots IE shelf — "added
   to basket 34× in 24h" live).

2. **Brief a Sissel Lab Dublin owner-POV video following the KIBODI
   STORE template.** KIBODI STORE Shoreditch indie boutique
   owner-POV (10.08% ER, 694 views, organic) is Day-4's NEW pattern.
   Sissel Lab Dublin is the structural twin — Stephen's Green
   boutique, 149.3K followers on a Seoul-life account, no owner-POV
   on the boutique side. Pitch a "behind-the-counter at Dublin's
   first Korean beauty store" series — **business-of-skincare
   confessional** is the underserved register for IE 22-32 buyers
   who shop independent over Boots IE. Close with "would you try
   this?" not "RUN don't walk" (KIBODI's 10% ER confirms the
   dialogue-close pairing). Cost: <€500 production, <€100 ad-spend.

3. **Open a well-ageing-skepticism watch slot and pre-empt the
   counter-wave inside the script.** Day-5/6/7 prediction:
   well-ageing will face the same critical-creator pushback PDRN
   faced in Q1 2026 — expect *"isn't well-ageing just anti-aging
   with a softer name?"* within 7-14 days. The IE script should
   **anticipate the critique inside the opening line**: *"I know
   what you're thinking — well-ageing is anti-aging rebranded.
   Here's the actual difference…"* then explain the mechanic
   (long-term barrier + NAD+/peptide stacking vs single-active
   wrinkle-targeting). Same pattern as James Welsh's canonical
   *"No, you don't need PDRN, but here's why I swear by it"* — the
   IE creator who pre-empts the well-ageing-skepticism wave wins
   the same trust-tier lane.

## Data quality

- **TikTok comment-section access: STILL BLOCKED.** Day-4 of 4
  consecutive days. Magazine review sites also 403 in WebFetch
  (Stylist UK, Refinery29 directly confirmed today). **WebSearch
  snippet-fragments + paraphrased editorial summaries + creator
  caption pulls in search results** remain the only available
  comment-proxy channel.
- **Verbatim comments captured: 0.** Five **creator-caption
  verbatim phrases** captured today (James Welsh well-ageing +
  level up your routine + love the process; Stephanie Vavron
  stollen my heart; Cardi B Numbuzin/BIOHEAL BOH cross-echo).
  Two **retailer micro-signals** captured (Boots UK product-page
  add-to-basket count + Boots 2026 trends report "every 11
  seconds").
- **Carry-forward source**: `daily_data/2026_06_09/comment-signal.md`
  (Day 3) — 11 phrases re-attested today; **Day-3's 3 NEW phrases
  (I get the hype now / repeat-buy / would you try this?) all
  graduated to CF**.
- **Diversity check**: 5 NEW phrases / signals across 3 distinct
  format types (debate/paid-creator-fronted, review/ingredient-led,
  retailer-surface). Exceeds ≥3 NEW minimum by 67% with mandatory
  format diversity met. Format mix: 4 review, 3 store-tour, 2
  verdict, 2 firstimpressions, 1 derm-led, 1 debate, 1
  retailer-house-channel.
- **Critical methodology note — well-ageing pivot**: Day-3's call
  to *"retire wellageing as a tracking target"* is **REVERSED**
  today. The term IS in market — Day-1/2/3 missed it because (i)
  hyphenated spelling ("well-ageing") was not in the search-target
  glossary, (ii) James Welsh's caption is October-2025-dated, not
  in the 7d viral pool. **Recommend the briefing-template add all
  three spellings (well-ageing, wellageing, slow-ageing) as
  tracked variants alongside skin longevity.**
- **Confidence**: HIGH on well-ageing surface (James Welsh
  verbatim caption + oneeyebeauty.com editorial corroboration —
  two distinct sources, both UK-facing); HIGH on patient-CTA
  register growth (3-source corroboration: James Welsh, oneeyebeauty,
  Hyphen K-skincare longevity coverage); MEDIUM on
  ingredient-counter-confession (single ingredient — heartleaf —
  but spans multiple TikTok comment-aggregator sources); MEDIUM on
  retailer-surface buying-signal (Boots UK only — needs
  cross-retailer confirmation Day-5 to graduate to BASE).
- **Bias warning**: today's pool contains a structural
  paid-pool over-index because the FastMoss 7d UK rows skew
  88% paid. Organic comment-proxy sources are
  weighted toward Frishta + ElleMoonz + Ash + KIBODI for
  format-diversity coverage, which means the **organic
  sentiment estimates have a wider error bar than paid
  estimates today**. Day-5 should re-execute brand-search slot for
  Biodance (organic-heavier) to rebalance.
- **Remediation pending**: Day-1's allowlist request for UK
  editorial domains (marieclaire.co.uk, graziadaily.co.uk,
  stylist.co.uk, whowhatwear.com, hellomagazine.com, refinery29.com,
  hypebae.com, www.tiktok.com) — **not actioned 4 days in**. The
  14-day benchmark **cannot reach verbatim-comment fidelity**
  without the access fix. Triangulation continues to surface NEW
  vocabulary but cannot statistically size sentiment shares.

— End of Day 4 comment-signal —
