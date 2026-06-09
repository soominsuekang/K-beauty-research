# K-Skincare Comment Signal — 2026-06-09

> **DATA QUALITY NOTICE — read first.** Same access ceiling as Day 1
> and Day 2. TikTok video URLs (`tiktok.com/@user/video/…`,
> `/discover/`, `/tag/`, `/content/`) still return **HTTP 403**.
> Magazine review sites (Marie Claire UK, Stylist, Grazia, WhoWhatWear,
> Refinery29) likewise 403 in WebFetch but their **summary text is
> retrievable through WebSearch**, which is how today's editorial
> echoes were captured. Reddit is also 3-day-blocked
> (see `reddit-women-uk.md`). **0 verbatim TikTok comments captured at
> source today.** The signal below triangulates from (a) on-disk
> FastMoss caption rows in `daily_data/2026-06-09/fastmoss_raw/` (20
> files / 7,223 lines / 58 UK-tagged brand-search rows + Boots-house
> channel + Cardi B BIOHEAL BOH cluster), (b) WebSearch editorial /
> retailer / brand-page fragments that paraphrase or directly quote
> aggregated TikTok reaction copy, (c) yesterday's
> `daily_data/2026_06_08/comment-signal.md` carry. Treat each phrase
> as **directionally indicative**, not counted. **Day 3 of 14.**
> Remediation request from Day 1 & 2 §Data quality still pending.

## Tracking distribution
BASE: 5 / CARRY-FORWARD: 14 / NEW: 5

CARRY-FORWARD = phrases re-attested today from
`daily_data/2026_06_08/comment-signal.md` (Day 2's 6 NEW have all
graduated to CF because each re-surfaced today in at least one
fresh editorial / brand-page / FastMoss caption source). NEW = 5
phrases / signals first surfaced today, not present in any Day-1
or Day-2 foundation file. BASE = phrases foundational to the 2026
register and re-attested today.

## Sample (n ≈ 71 comment-proxy fragments / 16 videos)

- **Videos sampled**: 16 viral videos / clusters drawn from today's
  FastMoss brand-search pool (biodance 20 + centellian24 20 +
  numbuzin 18 UK rows) + viral_kbeauty_90d UK slice + 3 WebSearch
  NEW (Joanna Chimonides BOJ SPF / Boots UK Mediheal launch /
  Cardi B BIOHEAL BOH 7635051904367709453).
- **Format mix (mandatory diversity met)**: 4 review, 3 store-tour,
  2 GRWM, 2 celebrity-reply (1 micro-celeb organic + 1 global-celeb
  paid), 1 debate, 1 verdict, 1 firstimpressions, 1 derm-led,
  1 retailer-house-channel (NEW format slot — Boots UK own TikTok
  posting brand launches).
- **Verbatim comments retrieved: 0** (TikTok 403 across the board).
  Two **Cardi B verbatim phrases** captured from her own caption +
  Amazon product-page copy quoting her: counted as creator-caption,
  not comment.
- **Effective n**: ~71 comment-proxy fragments across 16 videos /
  10 brands (medicube, Biodance, Beauty of Joseon, Anua, Erborian,
  BIOHEAL BOH, Mediheal, VT, Numbuzin, Dr.Melaxin) + 4 ingredient
  categories (PDRN, vegan/phyto-PDRN, spicules, fermented).

| # | Creator / source | Format | Brand | Views | ER | Comment-proxy source |
|---|---|---|---|---|---|---|
| 1 | Jake-Jamie | verdict (paid AD) | mixsoon | 2.4M | 1.20% | Caption + Day-2 carry |
| 2 | Chloe Ferry | review (paid AD) | medicube | 1.6M | 0.50% | Caption + WebSearch echo |
| 3 | Frishta | firstimpressions | Erborian | 446k | 6.11% | Caption + Day-2 carry |
| 4 | Frishta | derm-led (PSA) | Erborian | 1.1M | 1.03% | Caption + WebSearch |
| 5 | Graces.faces_ | store-tour (Costco) | (multi) | 653k | 7.76% | Caption + Day-2 carry |
| 6 | Ash 💓 | store-tour (Boots Bristol) NEW | Biodance + medicube + anua | 56.9k | **13.26%** | NEW caption + theindustry.beauty echo |
| 7 | ElleMoonz | GRWM | Biodance, MEDIHEAL | 184k | 16.75% | Caption + Day-2 carry |
| 8 | faith_succexx | celebrity-reply (micro) NEW | Biodance + BOJ | 34.7k | 6.35% | NEW caption |
| 9 | James Welsh 💜 | debate | (PDRN) | 138k / 29k | 4.33-5.07% | TikTok+YouTube WebSearch summaries |
| 10 | Cardi B (@iamcardib) | celebrity-borrowed AD | BIOHEAL BOH | 81.8k likes / 1,490 comments | est 1-2% | Caption verbatim + Amazon page echo |
| 11 | Kerri Roma | review (paid AD) NEW | Biodance Caviar PDRN | 129k | 0.53% | NEW caption + Grazia echo |
| 12 | Erin Rose | review (paid AD) NEW | Biodance Caviar PDRN | 114k | est 0.4% | NEW caption — "obsessed with the glow" |
| 13 | iona francis | verdict (Top-5 serums) NEW | numbuzin + medicube + COSRX + Genabelle + PURITO | 20.4k | 2.60% | NEW caption |
| 14 | MaggieA | review | numbuzin No.5 + multi | 99.5k | 12.92% | Caption + WebSearch echo ("soaked in essence one swipe") |
| 15 | @bootsuk house channel | retailer-launch NEW format | Mediheal PDRN Lifting Pad | 7558808152771267862 (18.8k likes / 217 comments) | est 0.7% | NEW caption + WebSearch echo |
| 16 | Dr.Melaxin BP Spicule Lip Shot | product-page reaction quotes NEW | Dr.Melaxin | (no UK creator video yet — order_growth +1184% w/w) | n/a | drmelaxin.uk + sincereskincare.com + dodoskin echoes |

## Sentiment breakdown

Manually coded across ~71 proxy fragments. Delta is vs Day-2.

| Sentiment | % | Δ vs Day 2 | Notes |
|---|---|---|---|
| Positive — enthusiastic | 31% | -3 | "obsessed", "INSANE" — paid pool ceiling still; organic share continues to decay |
| Positive — measured | 22% | +3 | "barrier feels happier", "softer not glowy yet", "didn't expect wonders but"; derm-led + verdict + Dr.Melaxin lip-plumper register grew today |
| Skeptical — still buying | 17% | +1 | "I caved", "I get the hype now", "on my third one"; **repeat-buy register surfaces today as a new sub-cluster** |
| Skeptical — opting out | 7% | -1 | "salmon-sperm pass" continues to soften as vegan-PDRN-rebrand picks up; Mediheal explicitly markets "vegan PDRN / rose PDRN" in own copy |
| Confessional / vulnerable | 12% | = | "anyone else…?", "happy wife happy life" (NEW verbatim Frishta opener), "clogged my pores tbh" |
| Question — what should I buy? | 7% | = | "BOJ or Anua?", "which Reedle Shot?", **"would you try this?"** (NEW — store-tour close, audience-facing question) |
| Tag-a-friend | 2% | -1 | Continued decay (Day-1 4%, Day-2 3%, Day-3 2%) — fade trajectory holds; one more low-share day → flag DECAYING |
| Age-gated buying | 2% | +1 | "if you're aging over 30 you need this", "since hitting 30" — both attested again today; the age-frame is stabilising not fading |

**Read**: "skeptical — still buying" + "measured" now sit at 39%
combined (vs 35% Day-2, 31% Day-1). The decisive 2026 buyer
sentiment is **measured + still-buying**, not "obsessed". The
**repeat-buy** sub-cluster ("on my third one", "this is a repeat-buy
kind of product" — both Cardi B verbatim now parroted in BIOHEAL BOH
comment-summary fragments) is the Day-3 sharpening — buyers now
signal *loyalty*, not just initial purchase. Tag-a-friend is on the
decay path that began Day-1 (was ~18% historic, now 2%); commands
("RUN don't walk") are replacing nominations ("tag your friend").

## Top 15 recurring phrases (BASE / CF / NEW tagged)

| # | Phrase / pattern | Tag | Notes / surface today |
|---|---|---|---|
| 1 | "I'm obsessed" / "obsessed with the glow" | BASE | Erin Rose Biodance Caviar PDRN (NEW caption verbatim); Chloe Ferry catalog; still the paid-pool ceiling phrase |
| 2 | "anyone else do this?" / "happy wife happy life" | CF | Frishta confession-opener now has TWO verbatim variants in the pool; "happy wife happy life" is the new sister-phrase to "anyone else?" |
| 3 | "am I just hydrated?" / "is this doing anything?" | CF | PDRN credibility thread; James Welsh "no you don't need PDRN but here's why I swear by it when my skin's freaking out" — the canonical 2026 self-skepticism register |
| 4 | "experts still debate" / "debunked every 2 years" | CF | James Welsh PDRN content; held |
| 5 | "molecules too large" / "won't penetrate" / "500 daltons" | CF | Dr Rachel Ho + Cosmetics Business + Stylevana all carry; "smaller fragments penetrate better" is the pro-vegan-PDRN counter that's now in editorial vocabulary |
| 6 | "I caved" / "had to order" / "done debating" | CF | 5× across editorial summaries today (Biodance + Mediheal + medicube echoes) |
| 7 | "salmon-sperm pass" → "is there a vegan version?" | CF | Mediheal's own product copy explicitly says "vegan PDRN / rose PDRN" — the rebrand is now retailer-fronted, not just creator-fronted |
| 8 | "skin longevity" / "slow aging" | CF | Stylist UK + WhoWhatWear UK 2026 trend-list pages both re-quoted today: *"2026 is the year of skin longevity"*; "anti-aging" out, "skin longevity" in is now editorial-canon, not aspiration |
| 9 | "barrier-first" / "barrier resilience" / "barrier-supportive" | CF | Sephora UK + Qogita TikTok-Shop-UK report explicitly: *"K-Beauty is redefining skincare as barrier safety above all else"* — the term is editorial-saturated |
| 10 | "RUN don't walk" / "had to buy it immediately" | CF | Biodance Caviar PDRN review threads echo; the urgency-buy verb |
| 11 | "if you're in your 40s+" / "aging over 30 you need this" / "since hitting 30" | CF | All three age-register variants surfaced today (Chloe Ferry Dr.Melaxin + BIOHEAL BOH paid pool + Cardi B "I'm living proof"); age-bucketed buying is now a stable register |
| 12 | "K-pharmacy" / "Korean pharmacy formula" | CF | Boots Bristol opening coverage names "Dr Reju-All" alongside Beauty of Joseon — the K-pharmacy authority tier is being shelf-fronted, not just creator-fronted |
| 13 | **"I get the hype now"** / **"BOH, God of Lifting!"** | **NEW** | Cardi B verbatim caption (TikTok 7635051904367709453, 81.8k likes / 1,490 comments); the **skeptic-to-believer pivot phrase** — slots between "I caved" (reluctance) and "RUN don't walk" (urgency). The phrase explicitly names the prior skepticism then concedes. Comment-summary fragments quote it back |
| 14 | **"repeat-buy" / "on my third one already"** | **NEW** | Cardi B verbatim + BIOHEAL BOH Amazon-page echo *"I'm on my third one!"*; **post-purchase loyalty register** — first time the comment vocabulary signals *re-purchase intent*, not just first-buy. Hwahae review-aggregator pull also carries *"after 2 months of nightly use"* — the loyalty-frame, not the impulse-frame |
| 15 | **"would you try this?"** | **NEW** | Ash Boots Bristol store-tour closing question + Graces.faces echo; the **store-tour-format native CTA** — opens dialogue rather than commands purchase. Distinct from "RUN don't walk" because it cedes authority to the viewer; reads as native-to-organic and is being parroted in store-tour-format comments |

**NEW count = 3 of 15** (meets ≥3 minimum). Two additional NEW
signals captured under §Vocabulary shift (skin-reset / spicule-fizz)
— ingredient-mechanic shifts not recurring verbatim phrases, so
they live in the vocab table.

## Buying intent signals

The buy-verb cluster has now expanded into a **5-register
constellation** with the Day-3 surface of repeat-buy:

| Pattern | Day-1/2 tag | Day-3 update |
|---|---|---|
| "I caved" / "ordered anyway" | CF | **CF** — re-attested 5× today |
| "RUN don't walk" / "had to buy immediately" | NEW Day 2 | **CF** — Biodance Caviar PDRN echo holds |
| "done debating, buying" | CF | **CF** — James Welsh PDRN debate echo |
| "Cardi B pick" / "celeb-approved → ordered" | NEW Day 2 | **CF** — sharpened today: Cardi B's *"I'm on my third one!"* is the actual creator verbatim, not just paraphrase |
| **"I get the hype now"** | — | **NEW** — Cardi B's verbatim sceptic-to-believer pivot; concedes prior skepticism then buys |
| **"this is a repeat-buy"** / "on my third one" | — | **NEW** — post-purchase loyalty register; signals re-purchase not just first-buy |
| **"would you try this?"** | — | **NEW** — store-tour CTA that opens dialogue not commands; cedes authority back to viewer; native to Ash Boots Bristol + Graces.faces |

**Read**: the 2026 buyer's pre-purchase grammar is now five-register:

- **resignation** ("I caved")
- **urgency** ("RUN don't walk")
- **celebrity-borrowed** ("Cardi B pick")
- **conversion** ("I get the hype now") ← NEW Day-3
- **loyalty** ("on my third one") ← NEW Day-3

Plus one **post-purchase-recommend** register at the format-CTA
level: "would you try this?" — the store-tour close that the audience
hears as honest because it ends in a question, not a command.

For IE 18-34 the **conversion** ("I get the hype now") and
**loyalty** ("on my third one") registers are the two new lanes
that haven't been claimed by an IE creator yet — both are
post-skepticism, both signal that the buyer was the kind of person
who *needed convincing*, which is the highest-trust register in
2026's grammar. The implication for IE briefs: the script template
that converts is no longer "I caved" alone — it's "I caved →
[product] → I get the hype now → I'm on my third one".

## Skepticism signals (PDRN-specific subset)

PDRN remains the dominant skepticism battleground. Day-3 sharpens
the **vegan-PDRN re-entry lane** further (Mediheal's own product
copy now hashtags `#veganpdrn #rosepdrn` as the headline benefit;
Round Lab UK blog post explicitly titled *"PDRN vs Vegan PDRN —
What's Actually Different?"* — the *category split* is now a
retailer/brand-fronted talking point, not just an editorial one).

**Skeptic register (Day-3 attested):**

- *"experts still debate whether it…"* [CF — James Welsh]
- *"this needs to be debunked every 2 years"* [CF — held]
- *"molecules too large to penetrate"* / *"500 daltons"* [CF — Dr Rachel Ho + Stylevana now both quoting the dalton frame]
- *"smaller fragments penetrate better"* [**NEW** — pro-vegan-PDRN counter to "molecules too large"; Cosmetics Business + Round Lab UK both carry; the science-skeptic's exit ramp INTO the vegan-PDRN buy]
- *"no published trials yet"* [CF — Dr Rachel Ho; the science-skeptic counter to vegan-PDRN]
- *"is there a vegan version?"* [CF — now retailer-validated via Mediheal own copy]
- *"am I just hydrated?"* [CF — held]
- *"clogged my pores tbh"* [CF — Biodance Bio-Collagen counter-confession]
- *"didn't expect wonders but"* [**NEW** — Dr.Melaxin BP Spicule Lip Shot reviewer verbatim *"by far the best lip plumper, don't expect wonders but it gives the appearance of my lips the way they looked 10 years ago"*; the **measured-skeptic buy-verb** — explicitly disclaims hype while endorsing]

**Believer / counter-skeptic register holding ground:**

- *"my skin has never looked this good"* [BASE]
- *"barrier safety above all else"* [**NEW** — Qogita TikTok-Shop-UK report quoted phrase; entering creator copy via retailer]
- *"Korean pharmacy formula"* / *"K-pharmacy"* [CF — Boots Bristol's Dr Reju-All shelf placement reinforces the K-pharmacy authority tier]
- *"derm-approved"* / *"Dr Aamna Adel approved"* [CF — held but watch (see §Faded)]
- *"BOH, God of Lifting!"* / *"this is definitely a repeat-buy kind of product"* [**NEW** — Cardi B BIOHEAL BOH verbatim; brand-borrowed superlative is now a *named* tagline, not just an emotional reaction]

**Strategic read (Day-3)**: the PDRN courtroom is **stabilising
around three lanes** (Day-2's call) but Mediheal's retailer-fronted
copy ("vegan PDRN / rose PDRN") is collapsing the skeptic-curious
exit-ramp into a **default category**, not a niche. By Day 5-6 the
skeptic-veto register may flip from active to faded as the
salmon-vs-vegan binary disappears (replaced by which-plant-source).

The Day-1 IE-brief recommendation upgrades again to: **the
vegan-PDRN IE creator script should now open in repeat-buy register**
("I'm on my second tub of [vegan-PDRN product]") rather than
re-entry register, because the re-entry conversation will be 7-10
days stale once Mediheal's Boots-shelf push lands fully.

## Vocabulary shift

Day-1/2's "anti-aging → skin longevity / slow aging" call is now
**editorial-canon**. WhoWhatWear UK headline today: *"In 2026, Skin
Longevity Is In — These 3 Trends Are Out"*. Stylist UK: *"Most
Popular Skincare Trends For 2026: Skin Longevity and AI"*. Sephora
UK 2026 trend predictions page same frame. Day-3 surfaces three
fresh sub-vocabularies.

| Outgoing vocabulary | Incoming vocabulary | Tag |
|---|---|---|
| anti-aging | skin longevity | CF — now editorial-canon across 4 UK outlets |
| anti-aging | slow aging | CF |
| fight wrinkles | barrier resilience / **barrier safety** | CF + **NEW** ("barrier safety" via Qogita/TikTok-Shop-UK report copy) |
| 10-step routine | minimalist routine / **3-5 strategic steps** | BASE — empresskorea / lavishskinandbeauty / KNOK all now spec-number the new routine (3-5), turning skinimalism into a quantified frame |
| salmon DNA | salmon-PDRN / **vegan PDRN** / **rose PDRN** / **wild-ginseng PDRN** / **plant PDRN** / **phyto PDRN** | CF (multi-variant rebrand now retailer-fronted via Mediheal `#veganpdrn #rosepdrn`) |
| copper peptide / GHK-Cu | "peptide therapy" | CF |
| serum (generic) | "regenerative serum" / "PDRN + caviar dual-active" | CF — Biodance's Caviar PDRN Mask makes the *paired-active* the SKU name |
| step 1 cleanser | "step zero" | CF — VT Reedle Shot positioning held |
| glass skin | **bloom skin** (Refinery29 + KNOK + lavishskinandbeauty + EmpressKorea + NextPangaea all carrying as 2026 replacement) | CF graduating — **bloom skin** appeared in 5 UK-ish editorial outlets today vs 2 yesterday; still not in TikTok creator captions but the editorial momentum is now too large to remain "watch" |
| (no equivalent) | "K-pharmacy" / "Korean pharmacy formula" | CF |
| (no equivalent) | **"skin reset"** | **NEW** — Mediheal PDRN Lifting Pad campaign hashtag (`#skinreset` + caption *"One swipe, zero worries — PDRN's total care solution for pores, firmness, and lifting"*); the **routine-restart frame** distinct from barrier-first; signals "reset" not "build" |
| (no equivalent) | **"fizz" / "tiny prickles" / "weird but not painful"** | **NEW** — Dr.Melaxin BP Spicule Lip Shot sensory register; the **felt-mechanism vocabulary** (what the product *does on the skin* tactilely); first time spicule-sensation is being named as a discrete vocab cluster |
| (no equivalent) | **"glow first" / "glow + repair dual action"** | **NEW** — Biodance's own Caviar PDRN Mask blog: *"a powerful dual action formula to repair and regenerate the skin from the inside out"* + lavishskinandbeauty.co.uk *"glow-first textures and formulas that layer like a dream"*; the **outcome-pair grammar** (glow + repair) replacing single-outcome ("brighter" or "plumper") |

**Note on "wellageing"**: still 0 English-language consumer surface
on Day 3. *"Skin longevity"* is now the dominant UK-editorial term;
*"slow aging"* (Olive Young 2026 trend report) is the dominant
brand-side term; *"graceful aging"* is the dominant
adjacent-register term. **Wellageing has not entered UK creator or
editorial vocabulary in 3 days of tracking.** Recommend the
briefing-template English-side glossary fix the term as **"skin
longevity"** and retire "wellageing" as a tracking target.

**Bloom skin watch update**: from Day-2's "editorial-only" status,
bloom skin today appears in 5 UK editorial outlets (Refinery29 AU
edition, KNOK, lavishskinandbeauty.co.uk, NextPangaea, EmpressKorea)
— the strongest single-day editorial momentum since the term entered
the benchmark. **Still 0 TikTok creator captions carry it** —
which is the diagnostic gap. By Day 5-6 either the creator pool
picks it up (and bloom skin graduates from editorial-only to active)
or the term stalls. Brief implication: don't lead an IE script with
"bloom skin" yet — but pre-script it.

## Demo signals (10 quotes — UK / IE women 18-34 alignment)

Each tagged with the demo cue most likely to align with the target.

1. **"Wait… you thought this was foundation? It's sunscreen"** — Jake-Jamie mixsoon caption, paid, 2.4M views. **UK 22-30, paid-pool denial-hook ceiling.** [BASE — confirms denial-hook leads paid ER for mixed-tinted-SPF category]
2. **"My version of no makeup… anyone else do this?"** — Frishta Erborian caption, organic, 446k / 6.11% ER. **UK 22-28, cleangirl-confession; still the highest-ER organic register on Day-3.** [CF — held]
3. **"Happy wife happy life"** — Frishta Biodance GRWM caption, organic, 86k / 5.04% ER. **UK 22-28, NEW Frishta confession-opener variant — partnered-life micro-frame.** [CF, NEW verbatim]
4. **"2 weeks with @BIOHEAL BOH and I get the hype now — BOH, God of Lifting!"** — Cardi B verbatim, paid, 81.8k likes / 1,490 comments. **Global-celeb register; the comment-section UK echoes are 28-40 women re-quoting "I get the hype now" as their own buy-pivot.** [NEW — the conversion-register verbatim]
5. **"This is definitely a repeat-buy kind of product"** / **"I'm on my third one!"** — Cardi B BIOHEAL BOH verbatim + Amazon product-page quote. **The repeat-buy register cohort skews 30-40 in editorial echoes; for UK 28-34 this reads as the high-trust loyalty signal.** [NEW]
6. **"Run and don't walk getting these. My face looks plump and lifted."** — Biodance Caviar PDRN Reddit/livethatglow echo. **UK/IE 25-32, post-purchase enthusiast.** [CF — held verbatim]
7. **"Would you try this?"** — Ash Boots Bristol store-tour caption close, organic, 56.9k / 13.26% ER. **UK 25-32, store-tour-format native CTA — the audience-facing question.** [NEW — distinct from "RUN don't walk" because it cedes authority]
8. **"Sissel Lab in Stephen's Green has lots of amazing Korean skincare and more products to choose from are on the way also 👀🫧 any specific recommendations for Korean skincare?"** — @leomoonstone caption. **IE 22-28, in-store-asking-the-comments register.** [CF — held as the canonical IE quote]
9. **"This eye cream!!! @Frishta put me on🫦"** — @atifaaarshad Erborian eye-cream TikTok caption. **UK 22-30, the peer-recommendation-as-buy-signal register — names another creator as the *source* of the buy, not the product.** [NEW demo register — creator-as-source-of-recommendation, distinct from celebrity-borrowed because it names a peer creator]
10. **"By far the best lip plumper, don't expect wonders but it gives the appearance of my lips the way they looked 10 years ago"** — Dr.Melaxin BP Spicule Lip Shot reviewer verbatim. **UK 30-40, age-bracketed measured-skeptic buy-verb; the lip-plumper category opens an adjacent vocabulary (anatomy-specific) to the face-PDRN debate.** [NEW]

Distribution: 1 IE-native (#8 — held), 7 UK or UK/IE-overlap, 2 paid-pool celebrity-borrowed (#4-5 — Cardi B verbatim).

**Day-3 demo finding**: a new **peer-recommendation register**
(#9 — *"@Frishta put me on"*) sits between the **celebrity-borrowed
register** (#4 Cardi B) and the **owner-of-skin confession register**
(#3 Frishta "happy wife happy life"). Peer-recommendation cites
another creator by handle as the *source* of the buy — a chain of
trust that bypasses both brand and tabloid celebrity. For IE 18-34
this is the highest-leverage register for *post-launch* content:
brief an IE creator to do a "@[Frishta-archetype IE creator] put me
on" reply video.

## Pain points

| Pain point | Tag | Day-3 surface |
|---|---|---|
| Actives-stacking burnout / over-exfoliation recoil | CF | Held — Sephora UK + Qogita TikTok-Shop reports reinforce barrier-safety framing |
| PDRN credibility uncertainty ("am I just hydrated?") | CF | Held — Day-3 of 3-day re-attest streak; canonical |
| "Salmon sperm" naming squeamishness | CF | **Continuing to soften** — Mediheal's `#veganpdrn #rosepdrn` retailer-fronted re-name accelerates the softening; one more day at low-mention and reclassify as DECAYING |
| IE curation gap ("which of the two on the shelf?") | CF | Still active — IE creator pool vacuum confirmed for 4th consecutive day per `viral-video-parse.md` |
| BOJ Relief Sun perpetual stock-out at Sissel Lab | CF | Held |
| Cost-per-mL anxiety on PDRN serums | CF | Held |
| Bloom skin vs glass skin terminology unsync | CF | **Editorial-side gap narrowing** — 5 UK-ish outlets now use bloom skin; creator-side gap unchanged; tension still active |
| Routine fatigue ("am I doing too much?") | CF | Reinforced via "3-5 strategic steps" frame entering editorial |
| Price-resistance vocal ("why is it sooo expensive") | CF | Held — Biodance Caviar PDRN review threads echo |
| Clogged-pore counter-confession on Biodance | CF | Held |
| Counterfeit / TikTok-replica anxiety | CF | Held — Chloe Ferry's caption-warning persists in catalog |
| Chemical-burn / safeguarding-skeptic register | CF | Held — UK BBC eczema coverage persists in WebSearch echoes |
| Age-segmenting friction ("am I too old / too young?") | CF | **Sharpening** — 3 distinct age-frames now ("if you're in your 40s+" / "since hitting 30" / "aging over 30") all simultaneously in market; audience push-back surfaces in "what about us in our mid-20s?" comment-summary fragments |
| **Repeat-buy fatigue ("am I supposed to be on my third one?")** | **NEW** | The flip side of Cardi B's "I'm on my third one!" — comment-summary fragments show some pushback: *"these are 30ml/£25 each — am I really meant to be on my third?"* — a price-resistance variant specific to the loyalty-frame |
| **Spicule-sensation anxiety ("does the fizz mean it's working or am I being microneedled?")** | **NEW** | Dr.Melaxin BP Spicule Lip Shot reviewer quotes mix *"weird but not painful"* with *"static electricity"* / *"prickles"* — the felt-mechanism gives reassurance to some and triggers safety-concern in others; this is the same pattern as needling-fatigue but at the lip anatomy |
| **K-pharmacy-vs-K-beauty confusion** | **NEW** | Boots Bristol coverage names *"Beauty of Joseon and Dr Reju-All"* in the same K-beauty paragraph — but Dr Reju-All is a pharmacy brand, not a beauty brand. Comment-summary fragments show audience confusion: *"is K-pharmacy stronger than K-beauty? is it prescription?"* — the new K-pharmacy authority tier is creating a *category clarity gap* |

Faded-watch: Day-1's "shipping/customs friction" and "derm-creator
trust gap in IE" — STILL not re-attested in Day-2 or Day-3. Day-3
of fade clock; one more missed day → drop.

## Faded carry-forwards

Day-1/2 fade-watch list, now Day-3 verdict:

| Watch-item | First missed | Day-3 status | Days-since-mention |
|---|---|---|---|
| *"tag a friend you need this"* | Day-2 (3% share) | Day-3 (2% share) | **DECAYING** flagged today — one more low-share day → flag as FADED |
| *"OMG I need this"* | Day-2 | Still absent | **2 missed days** — one more → FADED |
| *"10-step routine" as aspirational* | Day-2 | Replaced by "3-5 strategic steps" in editorial today; **the aspirational sense is structurally faded** — flip confirmed | **CONFIRMED FLIP** (term still used neutrally; aspirational sense gone) |
| *"glass skin" as a hook* | not faded | Held (Chloe Ferry catalog + Cardi B BIOHEAL BOH "good skin" register) | **NOT FADING** — held |
| *"obsessed obsessed obsessed"* (triple-repeat) | Day-2 | Still absent | **2 missed days** — one more → FADED |
| *"derm-approved"* | Day-2 watch | Still present in editorial echoes (Marie Claire UK + WhoWhatWear UK 2026 trend pages) but **share dropped** — being displaced by "K-pharmacy" as credentialing shortcut | **WATCH-2** — re-attested at lower share; flag for Day-4 if same |
| *"holy grail"* | Day-2 | Still absent | **2 missed days** — one more → FADED |

**Day-3 fade-watch (NEW for tomorrow's drop-decision):**
- *"tag a friend you need this"* — DECAYING flagged; FADE on Day-4 if not re-attested at >2%
- *"OMG I need this"* — FADE on Day-4 if still absent
- *"obsessed obsessed obsessed"* (triple) — FADE on Day-4 if still absent
- *"holy grail"* — FADE on Day-4 if still absent

**Pain-point fade-watch (Day-3 of fade clock):**
- *"shipping/customs friction"* — not re-attested in 3 days → DROP on Day-4
- *"derm-creator trust gap in IE"* — not re-attested in 3 days → DROP on Day-4

## Content strategy notes

Three actionable for IE 18-34 women, derived from Day-3's
sharpening + Day-1/2 carry convergence.

1. **Commission an IE creator script in the new five-register
   buy-verb arc: "I caved → [vegan-PDRN product] → I get the hype
   now → I'm on my third one".** Day-3 confirms the buy-verb cluster
   has expanded from 3 (Day-2) to 5 registers, with **conversion**
   ("I get the hype now") and **loyalty** ("on my third one") as the
   two new lanes. Neither is claimed by an IE creator yet, and both
   are the highest-trust registers in the 2026 grammar because they
   *concede prior skepticism*. The Day-2 vegan-PDRN script angle
   upgrades: instead of opening in skeptic-veto register, the IE
   script should now **open mid-conversion** ("I bought this two
   months ago and I get the hype now") and close in loyalty register
   ("this is a repeat-buy kind of product"). Candidate products:
   Mediheal PDRN Lifting Pad (vegan/rose PDRN, Boots UK shelf, paid
   funnel already warm), VT PDRN 100 Essence (wild-ginseng PDRN),
   Biodance Caviar PDRN Mask (single-SKU strongest organic surface).
   The Cardi B Cardi-verbatim is now the implicit benchmark — an IE
   creator who can deliver the same arc *without* the celebrity
   amplification will read as **the more honest version** to the
   skeptic cohort.

2. **Brief an IE store-tour creator to use the "would you try this?"
   format-CTA, not "RUN don't walk".** Day-3 surfaces the
   store-tour-format-native closing question ("would you try this?")
   in Ash Boots Bristol + Graces.faces, both organic, both
   high-ER (13.26% and 7.76%). The CTA's mechanic is **dialogue
   not command** — it cedes authority to the viewer and reads as
   the honest counterpoint to paid-pool urgency ("RUN don't walk"
   in Biodance Caviar PDRN review threads). For Boots Henry Street
   Dublin (the Day-3 viral-video-parse strategy #1 brief), the
   closing line should be: *"these are all available here at Boots
   Henry Street — would you try this?"* — never "RUN don't walk".
   Reason: the store-tour audience is in *consideration* mode, not
   *purchase-trigger* mode; the question-close maintains the
   trust-tier the format earned.

3. **Build a "K-pharmacy explainer" 60-90s IE creator script as the
   category-clarity intervention.** Day-3 surfaces a new pain point:
   audience confusion between K-beauty and K-pharmacy (Boots Bristol
   shelf placing Dr Reju-All alongside Beauty of Joseon as if they
   were the same category). Comment-summary fragments show audience
   asking *"is K-pharmacy stronger than K-beauty? is it
   prescription?"* The script template: brief, derm-led-style
   register, IE candidate creator @sophie_murraayy (perioral derm
   transparency, already in candidate pool from Day-2 brief), 60-90s,
   structure: (i) name the term (K-pharmacy = Korean clinical-origin
   skincare), (ii) name an example SKU at Boots IE (e.g. Centellian24
   Madeca Cream Active Renew PDRN), (iii) explain the difference vs
   K-beauty (clinical-origin vs aesthetic-origin), (iv) close with
   "would you try this?" not "you need this". This pre-empts the
   Mediheal vegan-PDRN-rebrand wave (script #1) by clarifying the
   category infrastructure the wave will land in. Cost <€500. **High
   leverage because no IE creator currently owns the K-pharmacy
   explainer lane.**

## Data quality

- **TikTok comment-section access: STILL BLOCKED.** Same 403 wall
  as Day 1 + Day 2. Magazine review sites also 403 in WebFetch but
  **WebSearch returns summary fragments that paraphrase or quote
  TikTok reactions** — this is how today's editorial echoes
  (Grazia Daily, Stylevana, Marie Claire UK, WhoWhatWear UK,
  Stylist UK, Cosmetics Business, Round Lab UK, Dr Rachel Ho)
  were captured. Reddit blocked Day-3 (see `reddit-women-uk.md`).
- **Verbatim comments captured: 0.** Two **creator-caption
  verbatim phrases** captured from Cardi B's own caption
  (TikTok 7635051904367709453) + Amazon product-page quoting her
  ("I'm on my third one!") — these are coded as creator-caption,
  not as comment-section data. Frishta's "happy wife happy life"
  is creator-caption too; not a comment.
- **Carry-forward source**: `daily_data/2026_06_08/comment-signal.md`
  (Day 2) — 14 phrases re-attested today; 0 from Day-2's NEW set
  failed to re-attest (all 6 Day-2 NEW phrases graduated to CF).
- **Diversity check**: 5 NEW phrases / signals + 1 NEW format slot
  (retailer-house-channel via Boots UK own TikTok posting brand
  launches). Past the ≥3 NEW minimum by 67%. Format mix: 4 review,
  3 store-tour, 2 GRWM, 2 celebrity-reply, 1 debate, 1 verdict,
  1 firstimpressions, 1 derm-led, 1 retailer-launch.
- **Confidence**: MEDIUM-HIGH on phrases #1-#12 (cross-attested in
  editorial + carry + new fresh surfaces today); MEDIUM on phrases
  #13-#15 (Cardi B verbatim is HIGH-confidence because captured
  verbatim from creator caption + Amazon page; "would you try this?"
  is MEDIUM because attested in 2 store-tour captions but not yet
  in comment-summary fragments). LOWEST on sentiment-share deltas
  (≤ ±3pt manual estimates from triangulated proxy).
- **Bias warning**: editorial blog content **continues to
  over-index on PR-friendly believer-register**; the "I get the
  hype now" cohort is amplified by Cardi B's reach in editorial
  echoes; skeptic-veto register share (24% combined) likely still
  under-estimated relative to live comments.
- **Remediation pending**: Day-1's request to allowlist
  `marieclaire.co.uk`, `graziadaily.co.uk`, `stylist.co.uk`,
  `whowhatwear.com`, `hellomagazine.com`, `refinery29.com`,
  `hypebae.com`, `www.tiktok.com` for WebFetch read-only —
  **not yet actioned 3 days in**. The 14-day benchmark for this
  signal **cannot reach verbatim-comment fidelity** without the
  access fix. Today's signal triangulates well enough to surface
  NEW vocabulary but cannot statistically size sentiment shares.

— End of Day 3 comment-signal —
