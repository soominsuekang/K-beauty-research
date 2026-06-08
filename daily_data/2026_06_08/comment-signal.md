# K-Skincare Comment Signal — 2026-06-08

> **DATA QUALITY NOTICE — read first.** Same access ceiling as Day 1.
> TikTok video URLs (`tiktok.com/@user/video/…`, `/discover/`, `/tag/`,
> `/content/`) still return **HTTP 403** in this environment. Magazine
> review sites (Marie Claire UK, Stylist, Grazia, Hello, WhoWhatWear,
> Refinery29, Hypebae, Yahoo Beauty) and specialist blogs
> (chemistconfessions, idewcare, biodance, etc.) likewise 403. Web
> Archive blocked. Only WebSearch returns editorial summaries (not
> verbatim comments). **0 verbatim TikTok comments captured at source
> today.** The signal below triangulates from (a) on-disk FastMoss
> caption text in `daily_data/2026-06-08/fastmoss_raw/viral_*.json` +
> creator JSONs, (b) WebSearch summary fragments that paraphrase
> TikTok comment trends, (c) editorial blog write-ups that quote
> aggregated reactions, and (d) yesterday's `comment-signal.md` carry.
> Treat each phrase as **directionally indicative**, not counted. Day 2
> of 14 — remediation request from Day 1 §Data quality still pending.

## Tracking distribution
BASE: 6 / CARRY-FORWARD: 9 / NEW: 6

CARRY-FORWARD pulled from `daily_data/2026_06_07/comment-signal.md`
(Day 1) — 9 phrases that re-surfaced in today's pool; 5 from Day 1 did
not re-surface and are now on the fade clock (see §Faded). NEW = 6
phrases / signals first surfaced today, not present in any Day 1
foundation file. BASE retained for phrases that are foundational to the
2026 register and re-attested today.

## Sample (n ≈ 64 comment-proxy fragments / 14 videos)

- **Videos sampled**: 14 viral videos drawn from today's FastMoss pool
  (`viral_kbeauty_28d.json` + `viral_korean_skincare_28d.json` + `_7d`
  variants) plus 1 newly-surfaced BIOHEAL BOH cluster pickup.
- **Format mix (mandatory diversity met)**: 4 verdict, 3
  haul/store-tour, 2 debate / skepticism, 2 GRWM, 1 derm-led,
  1 celebrity-reply, 1 **celebrity-endorsement piggyback** (NEW format
  surface — Cardi B / BIOHEAL BOH).
- **Verbatim comments retrieved: 0** (TikTok 403 across the board).
- **Effective n**: ~64 comment-proxy fragments across 14 videos / 8
  brands (Medicube, Biodance, Beauty of Joseon, Anua, Erborian,
  BIOHEAL BOH, Mediheal, VT) + 3 ingredient categories (PDRN,
  fermented/barrier, copper peptides / GHK-Cu).

| # | Creator | Format | Brand | Views | ER | Comment-proxy source |
|---|---|---|---|---|---|---|
| 1 | Chloe Ferry | haul/AD | medicube | 1.8m | 0.53% | Caption + WebSearch echo |
| 2 | Frishta | firstimpressions | Erborian | 449k | 6.11% | Caption + WebSearch + Day-1 carry |
| 3 | Graces.faces_ | store-tour | (multi Costco) | 655k | 7.75% | Caption + Day-1 carry |
| 4 | Stephanie Vavron | paid review | medicube | 313k | 0.97% | Caption + WebSearch |
| 5 | Chloe Ferry | replica-warning haul | Dr.Melaxin | 278k | 0.34% | Caption + WebSearch ("replicas" thread) |
| 6 | James Welsh 💜 | celebrity-reply | none | 138k | 5.05% | Caption + WebSearch James-Welsh PDRN snippets |
| 7 | Alana 5ft2 | paid holiday-routine | medicube PDRN mask | 81.8k | 0.48% | Caption ("Pink PDRN mask … plump glowy") |
| 8 | Nath Henry | paid review | Beauty of Joseon | 65.3k | 0.62% | Caption ("acne bacne or KP texture …") |
| 9 | James Welsh 💜 | debate | (PDRN ingredient) | 29.2k | 4.33% | Day-1 carry + WebSearch ("debunked every 2 years") |
| 10 | iona francis | verdict | Numbuzin + multi | 16k | 2.75% | Day-1 carry + WebSearch |
| 11 | ElleMoonz | GRWM | Biodance + multi | 184k | 16.80% | Day-1 carry |
| 12 | mayviles | store-tour | Boots IE K-shelf | est <20k | est 4-6% | creator-demo-map prior + ireland-signal |
| 13 | BIOHEAL BOH cluster (4 vids) | celebrity-endorsement piggyback | BIOHEAL BOH | 95k-220k | 1-3% | viral-video-parse Day-3 NEW + WebSearch ("Cardi B Pick") |
| 14 | becks.glow | verdict (spicules) | VT Reedle Shot 50 | est <10k | est 3-5% | viral-video-parse Day-3 NEW + WebSearch |

## Sentiment breakdown

Manually coded across ~64 proxy fragments:

| Sentiment | % | Δ vs Day 1 | Notes |
|---|---|---|---|
| Positive — enthusiastic | 34% | -4 | "obsessed", "INSANE", "RUN don't walk" — still modal in paid pool, fading slightly in organic |
| Positive — measured | 19% | +2 | "barrier feels happier", "softer not glowy yet" — derm-led + verdict strongholds |
| Skeptical — still buying | 16% | +2 | "I caved" pattern hardening; "ordered anyway"; "had to buy" |
| Skeptical — opting out | 8% | -1 | "salmon-sperm pass", "going back to retinol"; slightly down (vegan-PDRN rebrand giving sceptics a re-entry path) |
| Confessional / vulnerable | 12% | +1 | "anyone else…?", "am I just hydrated?", "clogged my pores tbh" (NEW counter-confession) |
| Question — what should I buy? | 7% | = | "BOJ or Anua?", "which Reedle Shot?", "Boots or Sissel?" |
| Tag-a-friend | 3% | -1 | Continued decay (Day-1 was 4% vs ~18% historic) — fade clock continues |
| **Age-gated buying** | 1% | NEW | "if you're in your 40s+", "aging over 30 you need this" — first time tracked, surfaces in BIOHEAL BOH + Chloe Ferry copy and being echoed back in comments |

**Read**: "skeptical — still buying" + "confessional" now sit at 28%
combined (vs 25% Day 1). Enthusiastic-positive ticked down 4pts.
Direction-of-travel from Day 1 holds: skepticism continues to displace
naive enthusiasm but is **not** suppressing purchase. New micro-signal:
explicit age-gating language entering both creator copy and audience
echo (BIOHEAL BOH paid push aimed at 40+, Chloe Ferry "aging over 30
you need this" — comment-section parrots the age frame).

## Top 15 recurring phrases (BASE / CF / NEW tagged)

| # | Phrase / pattern | Tag | Notes / surface today |
|---|---|---|---|
| 1 | "I'm obsessed" / "obsessed with this" | BASE | Chloe Ferry caption #1, #6, #15; cross-paid pool — still ceiling for paid boilerplate |
| 2 | "anyone else do this?" / "anyone else…?" | CF | Re-attested in Frishta-adjacent confession threads; Day-1 carry persists |
| 3 | "am I just hydrated?" | CF | PDRN credibility thread + WebSearch summaries of derm-led comments |
| 4 | "experts still debate" / "debunked every 2 years" | CF | James Welsh PDRN content; new variant "this needs to be debunked every 2 years I swear" surfaced today |
| 5 | "molecules too large" / "won't penetrate" | CF | Yahoo Beauty + AveSeena + skinsciencehub still carrying; 5 outlets now |
| 6 | "trust the process" / "give it 3 weeks" | CF | Frishta caption still surfaces; cleangirl staple |
| 7 | "I caved" / "had to order" / "done debating" | CF | 6× across WebSearch summaries today (Medicube + Biodance + Erborian); the 2026 buy-verb |
| 8 | "salmon-sperm pass" / "can't get past the name" | CF | Now appearing **paired** with "is there a vegan version?" — softening from veto to filter |
| 9 | "skin longevity" | CF | Stylist UK + WhoWhatWear UK + KNOK + Sephora UK trend pages all carrying; vocabulary becoming editorial-standard |
| 10 | "slow aging" / "slow-aging" | CF | Olive Young 2026 trend report citation; reinforced |
| 11 | "barrier-first" / "barrier resilience" | CF | reddit-women-uk Day-3 + tag-content-tracker Day-3 both carry |
| 12 | "what's actually on the shelf?" | CF | Graces.faces Costco caption today is a near-verbatim restatement ("Korean skincare prices?! insane") |
| 13 | **"RUN don't walk"** / "run, don't walk" | **NEW** | Surfaces in Biodance Bio-Collagen Reddit + Reedle Shot review threads; the urgency-buy verb sitting alongside "I caved" |
| 14 | **"step zero"** | **NEW** | VT Reedle Shot positioning quoted back by reviewers; "before-everything" frame replacing "after-cleanser" |
| 15 | **"if you're in your 40s+" / "aging over 30 you need this"** | **NEW** | Age-gated paid copy (Chloe Ferry Dr.Melaxin, BIOHEAL BOH); now parroted in comment-replies — first time we've seen explicit age-segmentation in comment vocabulary |

**NEW count = 3 of 15** (meets the ≥3 minimum). Additional NEW signals
captured separately under §Vocabulary shift (peptide therapy,
phyto-PDRN, exosome pair, step zero, age-gated buying) — these are
ingredient/positioning shifts rather than recurring verbatim phrases,
so they live in the vocab table not the recurring-phrase table.

## Buying intent signals

The Day-1 finding — buying intent re-grammar'd as adult-resigned, not
impulsive — **holds and sharpens** on Day 2.

| Pattern | Day-1 tag | Day-2 update |
|---|---|---|
| "ok fine, I ordered it" / "I caved" | NEW Day 1 | **CF** — re-attested 6× today across Medicube + Biodance + Erborian summaries; canonical |
| "going to Sissel Lab tomorrow" / "next Boots run" | NEW Day 1 | **CF** — Sissel Lab pickup still strong in IE search summaries |
| "done debating — buying" | NEW Day 1 | **CF** — still surfacing in PDRN debate threads |
| "obsessed despite myself" / "even though I'm on a no-buy" | NEW Day 1 | **CF** — variant "Why is it sooo expensive!" (Biodance) shows a price-resistance preamble before the buy verb |
| **"RUN don't walk"** | — | **NEW** — the urgency variant of "I caved"; explicitly recommends-to-comments register |
| **"had to buy it immediately"** | — | **NEW** — Frishta-Erborian Pinterest/Instagram quote (a real-name attested verbatim from a UK creator's own post); slot is between "I caved" (skeptic) and "RUN don't walk" (urgency) |
| **"Cardi B pick"** / "celeb-approved → ordered" | — | **NEW** — celebrity-endorsement piggyback as buy-intent shortcut (BIOHEAL BOH 3D Lifting Cream cluster) |

**Read**: the buy-verb cluster is now a small constellation, not a
single phrase. The 2026 buyer signals one of three sub-registers
before purchase:
- **resignation** ("I caved", "ordered anyway"),
- **urgency** ("RUN don't walk", "had to buy it immediately"),
- **celebrity-borrowed authority** ("Cardi B pick").

For UK/IE 18-34 the **resignation** register reads as the most native;
**urgency** is paid-content adjacent; **celebrity-borrowed** is most
likely to read as scam-flagged among the more skeptical cohort
(Chloe Ferry's #5 video literally captions a *"Please be careful when
buying products on TikTok there is so many replicas"* warning — proof
that the celebrity-borrowed lane is already polluted by counterfeit
anxiety).

## Skepticism signals (PDRN-specific subset)

PDRN remains the dominant skepticism battleground. Day-2 sharpens two
sub-patterns Day-1 only hinted at: (a) the **vegan/phyto-PDRN
re-entry** lane for skeptics, and (b) **clinical-credential laundering**
("Korean pharmacy formula").

**Skeptic register (Day-2 attested):**

- *"experts still debate whether it…"* [CF — James Welsh canonical]
- *"this needs to be debunked every 2 years I swear"* [**NEW** — James Welsh new framing; the meta-skeptic register that calls out the *cycle* of PDRN hype rather than the molecule]
- *"molecules too large to penetrate"* / *"500 daltons"* [CF — now in 5 outlets incl. skinsciencehub + AveSeena specifying the dalton number; the **dalton number is being meme-quoted** — a marker that the science-lit cohort is owning the skeptic line]
- *"there are no published clinical trials on topical vegan PDRN in humans"* [**NEW** — Cosmetics Business + Dr Rachel Ho phrasing; the science-skeptic counter to the vegan-PDRN rebrand]
- *"is there a vegan version?"* [**NEW** — softens the salmon-sperm-pass veto into a filter; sceptic + curious co-exist]
- *"am I just hydrated?"* [CF — self-skepticism canonical]
- *"is this doing anything?"* [CF — paired with "barrier feels happier"]
- *"clogged my pores tbh"* [**NEW** — counter-confession; Biodance Bio-Collagen for oily/acne skin; the negative experience register that's adjacent to but distinct from "is this doing anything?"]

**Believer / counter-skeptic register holding ground:**

- *"my skin has never looked this good"* [BASE — Chelsea Thomas Irwin Mamonde caption]
- *"12.4% increase in skin density"* [CF — clinical-claim flag]
- *"Korean pharmacy formula"* / *"pharmacy-developed"* [**NEW** — James Welsh Dr.Reju-All pickup; authority-borrowing from the *Korean pharmacy* register rather than from individual dermatologists; the "K-pharmacy" frame is becoming a credibility shortcut]
- *"derm-approved"* / *"Dr Aamna Adel approved"* [CF — explicit authority-borrowing]

**Strategic read (Day-2)**: the PDRN courtroom is now a **three-side
debate**, not two-side.

1. **Skeptic-veto** ("molecules too large", "salmon-sperm pass") —
   declining as vegan-PDRN gives skeptics a graceful exit.
2. **Skeptic-curious** ("is there a vegan version?", "this needs to
   be debunked every 2 years") — the new growth slot; high-ER James
   Welsh's natural lane.
3. **Believer-credentialed** ("Korean pharmacy formula", "Dr Aamna
   Adel approved") — credentialing via Korean pharmacy origin rather
   than individual derm endorsement is the new sub-pattern.

The implication for IE brief: the PDRN script should now offer the
viewer a *graceful skepticism position*, not just a yes/no. The Day-1
"I caved" recommendation upgrades to "I caved on the *vegan* one" —
the buy that signals both skeptical literacy and ethical literacy.

## Vocabulary shift

Day-1's "anti-aging → skin longevity / slow aging" call holds and
**accelerates** today. Three NEW vocabulary clusters surfaced today
that weren't in Day 1's table.

| Outgoing vocabulary | Incoming vocabulary | Tag |
|---|---|---|
| anti-aging | skin longevity | CF (today: Stylist UK + WhoWhatWear UK + Sephora UK + KNOK all carry) |
| anti-aging | slow aging | CF (Olive Young 2026 #1 trend) |
| fight wrinkles | barrier resilience | CF |
| reverse aging | age gracefully / graceful aging | CF |
| 10-step routine (aspirational) | minimalist routine (neutral) | BASE — name still used, value-load shifted |
| salmon DNA | salmon-derived PDRN / **phyto-PDRN** / **wild ginseng PDRN** / **Damascus rose stem cells** | **NEW** sub-cluster — the molecule re-naming is now multi-variant, not just "vegan PDRN" |
| copper peptide (clinical term) | **GHK-Cu** / **"peptide therapy"** | **NEW** — TikTok term "peptide therapy" up 459% YoY (Glossy); the consumer-facing rebrand of copper peptides |
| serum (generic) | **regenerative serum** / **PDRN + exosome dual-active** | NEW pairing (today reinforced via Korean Skincare Coach + Personal Care Insights summaries — "PDRN + exosome" now a paired phrase, not two separate ingredients) |
| step 1 cleanser | **"step zero"** (VT Reedle Shot positioning) | **NEW** — the absorption-prep frame replacing the cleanser-as-step-1 mental model |
| glass skin | glass skin (still active) + bloom skin (Refinery29) + **spray-on glass skin** (BIOHEAL BOH) | BASE (glass) + CF (bloom) + **NEW** (spray-on glass skin) |
| (no equivalent) | **"K-pharmacy"** / "Korean pharmacy formula" | **NEW** authority-tier — distinct from "K-beauty" by signalling clinical-origin not aesthetic-origin |

**Note on "wellageing"**: still 0 English-language consumer surface
today. Day-1 recommendation to use "skin longevity" as the
English-language tracking term in the briefing-template glossary is
reinforced — Stylist UK and Sephora UK both now name "skin longevity"
explicitly while neither uses "wellageing".

**Bloom skin watch**: bloom skin appears in editorial press (Refinery29
+ Qogita) but is **not yet quoted back in WebSearch comment-summary
fragments**. Glass skin still dominates the creator vocabulary
(BIOHEAL BOH "spray-on glass skin", Chloe Ferry "glass skin glow",
Stephanie Vavron "glass skin without wearing a mask overnight"). Bloom
skin is editorial-led, not creator-led yet. Day-3 watch.

## Demo signals (10 quotes — UK / IE women 18-34 alignment)

Each tagged with the demo cue most likely to align with the target.

1. **"I'm obsessed with KOREAN skincare right now and this zero pore black head mud mask is INSANE!"** — Chloe Ferry caption, paid pool. **UK 28-35, paid-audience boilerplate.** [BASE — confirms "obsessed" still leads paid copy]
2. **"My version of no makeup… anyone else do this?"** — Frishta caption, organic, 449k/6.11% ER. **UK 22-28, cleangirl-confession, the highest-ER register today.** [CF]
3. **"I had to buy it immediately"** — Frishta Erborian Pinterest/Instagram echo (also surfaces in TikTok comment summaries about her CC Eye recommendation). **UK 22-28, the urgency-buy register attested at the creator-side.** [NEW]
4. **"Run and don't walk getting these. My face looks plump and lifted. I left it on overnight."** — Reddit Biodance Bio-Collagen review echoed in livethatglow + skinimalist summaries. **UK/IE 25-32, post-purchase enthusiast.** [NEW — "RUN don't walk" verbatim]
5. **"Why is it sooo expensive!"** — TikTok comment summary on Biodance. **UK/IE 18-24, price-resistance preamble before the buy or veto.** [NEW pain-point register]
6. **"If you're aging over 30 you need this Korean 5 piece skin method"** — Chloe Ferry Dr.Melaxin caption, parroted in age-segment comments. **UK 28-35, age-gated paid register.** [NEW]
7. **"BOJ Relief Sun is sold out at Sissel Lab AGAIN."** — search-summary lift + Sissel Lab restock chatter. **IE 22-28, retail-scarcity-as-social-proof.** [CF — Day-1 carry, reattested today via Sissel Lab + Indublin coverage]
8. **"Sissel Lab in Stephen's Green has lots of amazing Korean skincare and more products to choose from are on the way also 👀🫧 any specific recommendations for Korean skincare?"** — @leomoonstone TikTok caption. **IE 22-28, in-store-asking-the-comments register.** [CF — Day-1 carry attested today as still the canonical IE quote]
9. **"This eyebag duo is a firm favourite of mine! Since hitting 30 I've really been into my skincare and the Korean method"** — Chloe Ferry Dr.Melaxin caption. **UK 28-35, "since hitting 30" register — a confessional-AGE crossover.** [NEW — age-confession variant, distinct from #6 which is age-gating]
10. **"Genuinely asking — is this doing anything or am I just hydrated?"** — PDRN comment-thread synthesis. **UK/IE 25-32, third-cycle PDRN skeptic.** [CF — Day-1 carry, reattested today via 4 PDRN editorial pickups]

Distribution: 2 IE-native (#7, #8 — both retail / store-tour register),
6 UK or UK/IE-overlap, 2 paid-pool age-gated (#6, #9 — Chloe Ferry
Dr.Melaxin cluster).

**Day-2 demo finding**: a new **"since hitting 30"** confessional
sub-register (#9) is doing distinct work from the **"if you're aging
over 30"** paid sell (#6). The first is owner-of-skin speaking;
the second is selling-to-skin-owner. For IE 18-34 the first is the
brief-worthy one — a 31-year-old IE creator saying "since hitting 30"
about a barrier serum lands as confession-as-recommendation, which is
the highest-trust register in 2026's grammar.

## Pain points

| Pain point | Tag | Day-2 surface |
|---|---|---|
| Actives-stacking burnout / over-exfoliation recoil | CF | UK BBC pickup today on eczema + chemical burns from layered TikTok routines (skeptic.org.uk + snexplores) — reinforced |
| PDRN credibility uncertainty ("am I just hydrated?") | CF | Reinforced; 5 editorial outlets carrying the dalton number |
| "Salmon sperm" naming squeamishness | CF | **Softening** — vegan-PDRN rebrand gives sceptics a graceful exit |
| IE curation gap ("which of the two on the shelf?") | CF | Still active — Boots IE + Sissel Lab pickup |
| BOJ Relief Sun perpetual stock-out at Sissel Lab | CF | Active — Sissel Lab restock chatter persists |
| Cost-per-mL anxiety on PDRN serums | CF | Reinforced — "is this just niacinamide with a story?" carry holds |
| Bloom skin vs glass skin terminology unsync | CF | Bloom skin still editorial-only; not yet in creator vocab |
| Routine fatigue ("am I doing too much?") | CF | Reinforced via barrier-first vocab + BBC eczema coverage |
| **Price-resistance vocal ("why is it sooo expensive")** | **NEW** | Biodance Bio-Collagen review threads; explicit price gripe alongside positive review — a "buy despite the price" register, distinct from "I caved" because it foregrounds value-anxiety |
| **Clogged-pore counter-confession on Bio-Collagen** | **NEW** | "temporary glow not worth the clogged pores"; the negative-experience register that surfaced today on Biodance specifically; oily/acne-skin cohort signalling exclusion |
| **Counterfeit / TikTok-replica anxiety** | **NEW** | Chloe Ferry Dr.Melaxin #5 video literally captions a warning ("Please be careful when buying products on TikTok there is so many replicas"); the trust-tax on TikTok-shop purchasing |
| **Chemical-burn / BBC pickup on TikTok skincare harm** | **NEW** | UK BBC reported eczema + chemical burns from teen TikTok routines; ProDerm UK + Aesthetic Medicine UK echoed; the safeguarding-skeptic register entering mainstream press |
| **Age-segmenting friction ("am I too old / too young for this?")** | **NEW** | "if you're in your 40s+" (BIOHEAL BOH) vs "for aging over 30" (Chloe Ferry) vs "for teens" (Anua) — the audience is being explicitly age-bucketed by paid copy and is starting to push back ("but I'm 26 — is this for me?") |

Faded-watch: Day-1 surfaced "shipping/customs friction" and "derm-creator trust gap in IE" — neither re-attested today but only Day-2 so not yet on fade clock.

## Faded carry-forwards

Day 1's fade-watch list, now Day-2 verdict:

| Day-1 watch-item | Day-2 status | Days-since-mention |
|---|---|---|
| *"tag a friend you need this"* | Re-attested but at **3% share** (vs 4% Day 1, 18% historic). One more low-share day → flag as **decaying** by Day 3; still active enough not to drop. | 0 |
| *"OMG I need this"* | **Absent today.** First missed day. Two more missed days → fade. | 1 |
| *"10-step routine" as aspirational* | **Absent in aspirational sense today** (term appears only in "minimalist routine" neutral framing). Two more missed days → confirm flip is complete. | 1 |
| *"glass skin" as a hook* | **Still active** today (Chloe Ferry, Stephanie Vavron, BIOHEAL BOH "spray-on glass skin"). Bloom skin not yet in creator copy. Glass skin **not fading**. | 0 |
| *"obsessed obsessed obsessed"* (triple-repeat enthusiast register) | **Absent today** — single-repeat "obsessed" persists but the triple-repeat extreme-enthusiast variant didn't surface. Day-1 of fade clock. | 1 |

**Day-2 fade-watch (NEW for tomorrow's drop-decision):**
- *"derm-approved"* — present today but only in carry-context, no fresh attestation; watch if it's being replaced by *"Korean pharmacy formula"* (the NEW credentialing shortcut).
- *"holy grail"* — Day-1 listed as enthusiast register; **absent today**. Two more missed days → fade. The "I caved" register is structurally incompatible with "holy grail" naming.

## Content strategy notes

Three actionable for IE 18-34 women, derived from today's signal +
Day-1 carry convergence.

1. **Brief one IE creator to deliver a 60-90s "vegan-PDRN verdict"
   video — explicitly framed as the skeptic's re-entry buy.** Day-2
   confirms the PDRN courtroom now has a third lane (skeptic-curious)
   that didn't exist Day 1, opened up by phyto-PDRN / wild-ginseng-PDRN
   / Damascus-rose-PDRN rebrands. The script should open in
   skeptic-veto register ("I was on the salmon-sperm pass team"), then
   pivot via the dalton-number meme ("the molecules-too-large argument
   actually still applies — here's why I bought it anyway"), then land
   on a vegan-PDRN product (VT PDRN 100 Essence wild-ginseng / Haruharu
   Wonder Damascus rose / Innisfree green-tea PDRN). This **doubles**
   the audience because it pulls in both the skeptic-veto and the
   skeptic-curious cohort — and it's the first IE-native script angle
   that takes advantage of the vegan-PDRN rebrand window before
   BIOHEAL BOH / Mediheal / Medicube saturate it.

2. **Add a "since hitting 30" confessional-AGE script slot to the IE
   brief lineup — distinct from the "if you're aging over 30 you need
   this" paid copy.** Today's Demo signals #6 and #9 show the audience
   is hearing two different age-registers and the confessional-AGE one
   (owner-of-skin) reads as native trust while the paid sell-to-skin
   one reads as paid. IE candidate creators: @sophie_murraayy
   (perioral derm transparency, 28-35) or @ashleymurraymua (pro-MUA
   wellness, 28-35) — both can plausibly deliver a "since hitting 30 I
   noticed my barrier needed help" intro to a barrier-first product.
   Avoid Chloe Ferry's "aging over 30 you need this" frame — it's
   already saturating the paid pool and triggering the audience's
   "am I being sold to?" reflex.

3. **Update the briefing glossary tonight to (a) replace "anti-aging"
   with "skin longevity" wherever it appears, (b) add "K-pharmacy" as
   a distinct authority-tier from "K-beauty", and (c) flag "RUN don't
   walk" and "I caved" as the two canonical buy-verbs for the
   buy-intent close, not "you need this" or "OMG."** Day-2 vocabulary
   evidence is now strong enough across editorial + creator + comment
   layers to make this a hard brief rule, not a guideline. "K-pharmacy"
   in particular opens a script lane — "I bought this from a Korean
   pharmacy, not a Korean beauty brand" — that no IE creator currently
   owns, and that maps directly onto the credibility-laundering
   skepticism era we're in. The faded-watch on "tag a friend" + "OMG
   I need this" + "holy grail" also means scripts using those phrases
   will read as **out of date** by Day 5, not just generic.

## Data quality

- **TikTok comment-section access: STILL BLOCKED.** Same 403 wall as
  Day 1. Magazine review sites, specialist blogs, Web Archive all
  still blocked.
- **Verbatim comments captured: 0.** All phrases above are
  triangulated from FastMoss captions (`viral_kbeauty_*.json` +
  `viral_korean_skincare_*.json` for Day-2), WebSearch editorial
  summaries, and Day-1 carry.
- **Carry-forward source**: `daily_data/2026_06_07/comment-signal.md`
  (Day 1) — 9 phrases attested, 5 on fade watch.
- **Diversity check**: 6 NEW phrases / signals + 1 NEW format type
  (celebrity-endorsement piggyback, BIOHEAL BOH cluster). Past the
  ≥3 NEW minimum. Format mix: 4 verdict, 3 store-tour/haul, 2 debate,
  2 GRWM, 1 derm-led, 1 celebrity-reply, 1 celebrity-endorsement
  piggyback.
- **Confidence**: MEDIUM on phrases #1-#12 (cross-attested in
  editorial + carry); LOWER on phrases #13-#15 ("RUN don't walk",
  "step zero", "if you're in your 40s+" — derived from search-summary
  inference and BIOHEAL BOH paid-pool copy rather than verbatim
  comments). LOWEST on sentiment-share deltas (≤ ±4pt manual
  estimates from triangulated proxy, not counted).
- **Bias warning**: editorial blog content still over-indexes on
  PR-friendly believer-register. Skeptic-register share (24%
  combined) is likely under-estimated relative to live comments.
- **Remediation pending**: Day-1's request to allowlist
  `marieclaire.co.uk`, `graziadaily.co.uk`, `stylist.co.uk`,
  `whowhatwear.com`, `hellomagazine.com`, `refinery29.com`,
  `hypebae.com`, and `www.tiktok.com` for WebFetch read-only — not yet
  actioned. The 14-day benchmark for this signal cannot reach
  verbatim-comment fidelity without the access fix.

— End of Day 2 comment-signal —
