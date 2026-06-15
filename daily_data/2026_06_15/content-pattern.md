# Viral K-Skincare Video Structural Patterns — 2026-06-15

*Day 9 of 14. CARRY-FORWARD seeded from `daily_data/2026_06_14/content-pattern.md` (Day-8 winning recipes). **Today's FastMoss CRON LANDED CLEAN** at 00:14 Dublin — `daily_data/2026-06-15/fastmoss_raw/` has the full sweep (n=30 viral_kbeauty_7d + n=50 viral_korean_skincare_7d + n=30 promoted_skincare_monthly + n=8 deep_video_top10 + n=30 newlisted_skincare_gb + n=30 growthrank_beauty_gb_daily + n=30 risingstar_beauty_gb + n=20 popular_music_uk + n=20 popular_hashtag_uk_7d). Working pool = **74 unique UK rows after dedup** (30 viral_kbeauty + 50 viral_korean_skincare with overlap removed). Cross-references: `viral-video-parse.md` Day-10 (L'Oréal squadron LOCK at n=5 + LOOKFANTASTIC bundle 489.7k + MISSHA UK NAD-explainer + Cardi B name-drop + Smuuti Mini Kit RECOVERY), `tiktok-sounds.md` Day-9 (Taylor Swift "I Knew It, I Knew You" UK #1 + PinkPantheress×Larsson "Stateside" US #7 + sombr "Homewrecker" UK Top 10 — all 3 zero K-skincare uptake), `tag-content-tracker.md` Day-9 (#pureseoul + #oliveyoung + #riman NEW, #pdrn + #kpharmacy promoted to BASE).*

## Tracking distribution
BASE: 2 / CARRY-FORWARD: 10 / NEW: 5

(BASE = Day-1 brief patterns still re-verified today; CARRY-FORWARD = patterns from Day-8 re-tested in today's fresh pool; NEW = 5 fresh pattern variations not in Day-8 — exceeds ≥2 diversity floor.)

---

## Sample (n = 74, AD/Org split)

| Slice | n | AD | Org | AD% | Median ER (AD) | Median ER (Org) |
|---|---|---|---|---|---|---|
| Today's fresh viral_kbeauty_7d UK | 30 | 25 | 5 | 83% | 0.78% | 0.61% |
| Today's fresh viral_korean_skincare_7d UK | 50 | 44 | 6 | 88% | 0.81% | 2.30% |
| **Dedup combined (today's fresh)** | **74** | **64** | **10** | **86%** | **0.80%** | **1.18%** |
| Day-8 carry-forward 06-14 clean pool | 79 | 70 | 9 | 89% | 0.92% | 4.49% |

**Fresh-pool AD% = 86% UK** — sits inside the Day-3-to-Day-8 80-92% band, mild tilt toward more organic disclosure (10 vs 9 Day-8). **Organic median ER drops sharply to 1.18% vs Day-8's 4.49%** — the cause is structural, not signal-decay: **4 of the 10 organic rows are LOOKFANTASTIC Shop-affiliate self-disclosure posts** (Jodie 0.92% + Sasha 0.49% + Unbox with Chloe 0.61% + LoveMagicandSarah 0.59%) which carry the `is_ad=False` flag but are paid-affiliate-monetised. **The "true organic" sub-stratum (n=6 excluding LF Shop-affiliate)** sits at median ER ~3.4% (slavianaglow 6.34% + Kerri Roma 4.64% + EllieFarham 3.69% + SKINETICS 3.18% + Alana off-day 1.43% + bodyNsoul 0.11%). Paid-to-organic ER multiplier on the true-organic stratum = **4.3× (0.80% AD vs 3.4% Org-true)** — sits between Day-8's 4.9× and Day-7's 5.1×, no inflection. **Full-brief baseline (paid ~94% of 7d visibility / 28d organic emerges) STILL HOLDS** — today's 14% organic share at face is inflated by Shop-affiliate disclosure; adjusted-true-organic share is ~8%.

---

## Length distribution (AD vs Organic, fresh pool n=74)

| Bucket | AD count | AD % | Org count | Org % |
|---|---|---|---|---|
| 5–15s | 19 | 30% | 3 | 30% |
| 15–30s | 13 | 20% | 2 | 20% |
| 30–60s | 21 | 33% | 3 | 30% |
| 60–180s | 11 | 17% | 1 | 10% |
| 180s+ | 0 | 0% | 1 | 10% |

**Read** (CARRY-FORWARD EVOLVED): AD bimodal hold **softens** today — the 5-15s + 15-30s short-form combined drops to 50% (from Day-8's 53%) while **30-60s expands to 33% (from Day-8's 27%)** as Chloe Ferry's celebrity-tier paid posts (Dr.Melaxin 7-pc bundle ~50s, BOJ Apricot Peeling Gel 47s, Nath Henry BOJ body exfoliator 42s) plus the LOOKFANTASTIC Shop-affiliate cluster (Unbox with Chloe 34s + 28s + 22s, Sasha 31s, Jodie 29s) push the median paid post up to the 30-60s lane. **180s+ bucket vacates AD side entirely today** (was Day-8 Paula BOJ 206s; today no paid >120s) — long-form paid retreats. Organic spreads across all 5 buckets — including **SKINETICS 223s eye-cream-sourcing-defense long-form organic** (NEW format mechanic — see Hook section). Kerri Roma 69s carry-watch, slavianaglow 6s micro-organic NEW.

## Hook distribution (fresh pool n=74)

| Hook type | AD count | Org count | Best AD ER | Best Org ER |
|---|---|---|---|---|
| Claim ("Glass skin in a [bottle/spray]", "obsessed") | 11 | 0 | **4.84% (Callie Aiello medicube pink serum NEW)** | — |
| Verdict-praise ("INSANE!", "absolute steal", "absolute belter") | 6 | 1 | 1.96% (Chloe Ferry Dr.Melaxin 7-pc) | 0.92% (Jodie LF) |
| Confession ("When your skin looses collagen…" 30+ tier) | 1 | 0 | **0.38% on 1.6M v (Chloe Ferry Dr.Melaxin NEW celebrity-paid-confession)** | — |
| Celebrity-reply ("Replying to @[user]") | 6 | 1 | 5.93% (AndreEA mixsoon) | 0.61% (Unbox with Chloe LF) |
| Restock / "NEW IN" / TINY ANNOUNCEMENT | 2 | 0 | 0.04% (Smuuti Mini Kit 108.2k NEW sub-variant) | — |
| Store-tour / shop-owner POV | 0 | 0 | (carry only) | 10.08% (KIBODI — CARRY HELD Day-10 stability) |
| Sound-meta-comment / TikTok-meta opener | 0 | 0 | (carry only) | (Najma vidivici archived) |
| "POV: Taking off the day with [product]" + discount code | 0 | 0 | (carry-watch) | (Najma Starlike Day-2 absent → DROP-WATCH) |
| Romanian/Polish diaspora-PAID sub-template | 0 | 0 | (carry — Paula BOJ Day-1 absent today) | — |
| Curiosity-shock pre-review ("Salmon DNA is the latest trend") | 2 | 0 | **2.75% (Ash ✨ medicube — n=2 escalation HOLDS)** | — |
| Brand-launch retailer-channel (@bootsuk Mediheal) | 0 (carry) | 0 | (carry) | — |
| L'Oréal Glass Skin Western-brand squadron | **5** | 0 | **9.15% squadron median (Day-9 LOCK n=5)** | — |
| Mum-segment cross-vertical declutter (Kerri Roma Mode L) | 0 | 1 | — | **4.64% (Kerri Roma 8.8k DECLINING-WATCH -6%)** |
| **NEW Day-9: Retailer-aggregator parasocial ("Korean skincare lovers will love this new bag")** | **4** | **3** | **0.44% paid-affiliate at 11× algo-amp (Unbox with Chloe × LOOKFANTASTIC 489.7k)** | **0.92% (Jodie LF Edit)** |
| **NEW Day-9: International-celebrity-name-drop ("Cardi B can't stop talking about this Korean lifting cream")** | **1** | 0 | **1.34% (Craig Dean — 3-tier laddering hook)** | — |
| **NEW Day-9: Derm-explainer-NAD pedagogic ("Science class, Korean Skincare module")** | **2** | 0 | **3.21% (Makeup by Katy A × MISSHA UK — first MISSHA UK + NAD ingredient-story)** | — |
| **NEW Day-9: Brand-channel-restock-scarcity ("TINY ANNOUNCEMENT 🤏🥰 Mini Kit is finally back!")** | **1** | 0 | **0.04% on 108.2k v (Smuuti Mini Kit — sub-variant of brand-channel-direct, hyper-completion-optimized)** | — |
| **NEW Day-9: Sourcing-defense long-form ("WE RE VERY PROUD OF OUR EYE CREAM AND FROM WHERE ITS SOURCED")** | 0 | **1** | — | **3.18% (SKINETICS 5.0k 223s — first organic brand-defense long-form)** |
| "Glass skin in a [form]" SKU-anchored variant (K-defensive pivot) | 3 | 0 | **4.84% (Callie Aiello medicube "Glass skin in a bottle")** | — |

**Hook insight Day-9** — 5 NEW + 4 CARRY-FORWARD-EVOLVED:

1. **NEW: Retailer-aggregator parasocial hook (Unbox with Chloe × LOOKFANTASTIC K-Beauty Edit bag) — n=7 cluster (4 paid-affiliate + 3 organic-disclosed)**. Lead post 489.7k views (live 606.8k via `deep_video_top10`) at 0.44% ER and **11× follower-to-view algo-amplification** (44.5k followers). The parasocial structure ("I know my Korean skincare lovers will love this new bag") presupposes shared in-group identity ("you and I are both K-skincare lovers"), flattering audience into ownership. Distinct from brand-direct (Smuuti), brand-channel-paid-creator (Chloe Ferry Dr.Melaxin), brand-paid-creator (Lauren Franklin L'Oréal). **Tag: NEW + RETAILER-AGGREGATOR-CHANNEL + IE-PORTABLE (LOOKFANTASTIC ships IE today, no Boots-IE shelf-gating)**. The Day-8 retail-launch CTA prediction (Sephora-IE / Boots-IE pop-ups) is upstaged by a higher-leverage retailer that already ships IE.

2. **NEW: L'Oréal Glass Skin SQUADRON-LOCKED at n=5** (Lauren Franklin 28.57% + Beautytok 12.03% + Ash ✨ 9.15% + Alana 1.61% + MJ 2.34%; squadron median 9.15%). Day-8 NEW STRUCTURAL n=4 → Day-9 SQUADRON-LOCKED n=5 within 24h — the Day-8 forecast ("by Day-14 the routine likely logs 7-10 L'Oréal creators at sustained 10%+ ER") tracks; n=5 in 7 days extrapolates to n=8-9 by Day-14. **Western-brand-K-aesthetic encroachment is no longer hypothesis — it is structurally locked**. "Glass skin" SERP category exclusivity for K-brands is lost. K-brand defensive frame = **"glass skin in a [bottle/spray/form]" SKU-anchored variant**, proven Day-9 at n=3 (Callie Aiello medicube pink serum 4.84% + Sharon ANUA spray 1.14% + Mrs B medicube radiance set 0.63%). Tag: **NEW + STRUCTURAL-PROMOTED-TO-SQUADRON-LOCK + CRITICAL-URGENCY**.

3. **NEW: International-celebrity-name-drop hook** (Craig Dean × "Cardi B can't stop talking about this Korean lifting cream" 1.8k 1.34% paid 06-13). Distinct from celebrity-reply (the celebrity is invoked-by-name, NOT replied-to). **3-tier laddering: US megastar → UK micro-creator → audience**. First instance in benchmark of a US global megastar anchoring a UK micro-creator paid post. Tag: **NEW + HOOK-VARIANT-CELEBRITY-NAME-DROP**. Confidence MEDIUM (n=1) — Day-10 watch for 2nd creator name-dropping a US/global celebrity for a K-brand.

4. **NEW: Derm-explainer-NAD pedagogic frame** (Makeup by Katy A × MISSHA UK "Science class, Korean Skincare module. PDRN, NAD skin serum. But what do these ingredients even do?!" 4.7k 3.21% paid + same-creator 886v 3.27% 40+ pivot ("Korean makeup is so good for us over 40s")). **First MISSHA UK creator surface in benchmark** + first NAD ingredient-led explainer + first 40+ age-segment paid pivot. Cross-refs `trends-uk-ie.md` Numbuzin NAD+ "2026 wonder ingredient" anchor + Boots's "20 new brands" announcement. Tag: **NEW + BRAND-ENTRY-MISSHA-UK + INGREDIENT-NAD-FIRST-CREATOR + AGE-SEGMENT-40+-FIRST**.

5. **NEW: Brand-channel-restock-scarcity-9s sub-variant** (Smuuti Skin UK Mini Kit "TINY ANNOUNCEMENT 🤏🥰 Mini Kit is finally back!" 108.2k v / live 160.6k / 0.04% ER, 9s, brand-channel paid-boost). Sub-variant of brand-channel-direct (Day-7 Smuuti Peach Barrier Toner) — formalises the 9-second + scarcity + cute-emoji pattern as hyper-completion-optimized brand-direct viral. The 0.04% ER (37 likes / 108k views) is **identical to the prior Peach Barrier Toner brand-account paid-boost fingerprint**. Read: brand-channel produces a NEW viral every 7-9 days when boosted; individual posts fade quickly. **Reclassify: brand-channel-restock = LOW-ER + HIGH-VIEW reliable surface, not individual-post-acceleration model**. Tag: **NEW SUB-VARIANT + RECOVERED-FROM-DROPPED**.

6. **NEW (organic): Sourcing-defense long-form** (SKINETICS. "WE RE VERY PROUD OF OUR EYE CREAM AND FROM WHERE ITS SOURCED! I've had people try to catch me out…" 5.0k 3.18% organic, **223s — longest organic post in fresh pool**). First **brand-founder-defense** long-form organic — owner defends ingredient provenance against TikTok comment-section skepticism. Cross-vertical adjacency to Mode L (Kerri Roma) but inverted: instead of paid-history seeding organic spillover, this is **organic-trust-building via direct rebuttal**. Tag: **NEW + ORGANIC-LONG-FORM + BRAND-FOUNDER-DEFENSE**. Confidence MEDIUM-LOW (n=1, but the 223s × 3.18% on 5k views = real engagement floor for a defensive long-form).

7. **CARRY-FORWARD-EVOLVED**:
   - **Curiosity-shock "Salmon DNA is the latest trend"** — Day-8 n=2 (Ash ✨ + Shopwithbonniex) holds Day-9 with Ash ✨ same video re-verified at 1.7k 2.75% + Shopwithpoppy 1.1k 0.75% fresh PDRN-cream variant. **Confirmed escalation to n=2-3** — Salmon-DNA is the Western-friendly translation of PDRN, formalising as the K-brand ingredient-story counterweight to L'Oréal "glass skin" claim. Tag: **CARRY HELD + ESCALATED**.
   - **KIBODI Shoreditch in-store-booking organic 10.08% ER** — carry-stable 10 consecutive days (longest format-stability run in benchmark — Day-9 still single-instance, needs 2nd UK indie K-stockist to graduate to format).
   - **Najma Starlike POV-with-discount-code (Mode J)** — Day-2 absent from fresh pool. **Najma profile ACTIVE via COSRX overnight mask 872v 9.17% ER fresh today** (different SKU, different code). **NAJMASS5 code-watch UNTESTED Day-2**. Mode J narrow-version DROP-WATCH Day-10 if no Starlike resurface; Mode J broad-version (organic-affiliate-with-code) holds via COSRX surface. Tag: **CARRY EVOLVED + SKU-PIVOT**.
   - **Mode L Kerri Roma mum-segment cross-vertical declutter** — DECLINING-WATCH ARMED (-6%: 9.4k → 8.8k Day-9). Still above 50% threshold (4.7k floor). 2nd cross-vertical confirmation still missing Day-9 — Mode L confidence holds MEDIUM, watch Day-10.
   - **Romanian-language Paula BOJ Tinted SPF** — Day-1 absent from fresh pool. Diaspora-PAID Romanian sub-template Day-1 of carry-only (was carry-confirmed-fresh Day-8). Tag: **CARRY WATCH**.
   - **Goatie05 POV-overhype-walkback (Mode K)** — **Day-3 of carry-only → FADED Day-9 under 3-day rule**.

## First-3-sec visual (fresh pool n=74)

| Visual | Count | AD-skew | Notes |
|---|---|---|---|
| Hand holding single product to camera | 22 | AD-heavy | Mrs B medicube ×3, Sasha medicube, multiple LOOKFANTASTIC cluster, Callie Aiello pink serum, Anna BOJ bundle |
| Mirror talking-head, no product yet | 5 | Org-leaning | LoveMagicandSarah PDRN cleanser unboxing, AndreEA "Replying" mixsoon, Makeup by Katy A "Science class" opener |
| **NEW Day-9: Retailer-bag flatlay + ribbon reveal (LOOKFANTASTIC K-Beauty Edit)** | **4** | AD-only (paid-affiliate) | Unbox with Chloe lead 489.7k + 39.7k + 7.4k + 979v + Jodie + Sasha — bag-as-protagonist opener distinct from brand-direct |
| **NEW Day-9: Geordie celebrity setting + dressing-table-vanity (Chloe Ferry Dr.Melaxin 1.6M)** | **1** | AD-only | Chloe Ferry "When your skin looses collagen" opens in her bedroom with the Dr.Melaxin 7-pc bundle pre-arranged — celebrity-domestic setting upgraded from creator-vanity |
| **NEW Day-9: Brand-channel quick-cut scarcity intro (Smuuti Mini Kit 9s)** | **1** | AD-only (brand-channel) | Smuuti brand-house creative team — 9s hyper-edit, no creator face, ribbon-cute emoji-led intro card |
| **NEW Day-9: Pedagogic chalkboard / explainer-card opener (Makeup by Katy A MISSHA UK)** | **2** | AD-only | "Science class" pedagogic frame opens with explainer text-card / module-style typography distinct from talking-head review |
| **NEW Day-9: Brand-founder direct-camera defense (SKINETICS organic 223s)** | **1** | Org-only | Brand-founder addresses comment-section accusations head-on with eye-cream in frame — distinct from review/POV/store-tour |
| Western-brand glass-jar product hero on dressing-table (L'Oréal squadron, carry) | 1 fresh (Alana) | AD-only (carry+fresh) | Alana × L'Oréal Glass Skin opens on jar reveal — same template as Lauren Franklin / Beautytok / Ash ✨ / MJ carry |
| Sheet/gel mask on-face close-up | 2 | AD-only | Mrs B medicube radiance set, bodyNsoul Beauty PDRN Pink Collagen Mask organic |
| Shelf / retail pan / store interior (KIBODI carry) | 0 fresh | (carry) | (carry only — Day-10 stability holds) |
| Multi-product flatlay (haul opener) | 4 | mixed | Chloe Ferry Dr.Melaxin 7-pc + 5-pc bundles, Anna BoJ bundle, Sharon ANUA glow set |
| Mum-segment declutter B-roll (Kerri Roma carry) | 1 | Org-only | Kerri Roma 8.8k DECLINING-WATCH |
| Lip-tint swatch close-up (slavianaglow dasique NEW) | 1 | Org-only | slavianaglow × dasique 583v 6.34% — K-skincare-into-K-makeup cross-vertical |

**Read** (CARRY-FORWARD + 5 NEW first-3-sec patterns Day-9): The Day-3-to-Day-8 generalisation ("organic opens on a *room/place/person*, AD opens on a *product*") **softens today** — the **retailer-bag flatlay** opener (n=4-7 LOOKFANTASTIC cluster) introduces a 3rd object-class besides product and place: the **curated bag itself as protagonist**. Plus the **brand-founder direct-camera defense** (SKINETICS) and **pedagogic explainer-card** (MISSHA UK) extend opener taxonomy into editorial-creative territory previously absent from the K-skincare pool. Day-9 net: opener variety expands from ~7 distinct templates (Day-8) to ~12 (Day-9).

## Caption distribution (fresh pool n=74)

| Metric | AD median | Org median |
|---|---|---|
| Caption length (chars) | 142 | 110 |
| Hashtag count | 5 | 4 |
| Emoji count | 1 | 1 |
| @ mentions of brand | 1 | 1 |
| Has explicit price/discount ("£40", "summer sale") | 18% | 30% (LF cluster) |
| Has "AD" / "ad" disclosure in caption | 8% | 0% |
| Has "@medicube UK" or "@Dr.melaxin Uk" inline tag | 44% | 20% |
| Has "@LOOKFANTASTIC" inline tag (NEW Day-9 retailer-aggregator) | **17%** | **30%** |
| Has "@Beauty of Joseon" or "@Beauty of Joseon UK" inline tag | 6% | 10% (MASUK) |
| Has "@L'Oréal Paris UK" inline tag (Western competitor) | 8% | 0% |
| Has "@missha uk" inline tag (NEW Day-9) | 3% | 0% |
| Has discount-code (NAJMASS5 / AMELCIA13) | 0% | 0% (Najma Starlike Day-2 absent) |
| Has non-English-language caption (Romanian/Polish) | 1% (Gonceariuc only) | 0% |
| Has retail-launch geographical anchor | 0% | 0% (AESTURA Scotland Day-1 absent) |
| Has mum-segment hashtag stack (#mumsoftiktok) | 0% | 10% (Kerri Roma) |
| Has "#kbeautyedit" / "#beautybox" retailer-bag hashtag (NEW Day-9) | **8%** | **20%** |

**Read** (CARRY-FORWARD + 2 NEW caption-pattern Day-9): AD caption length expands to **142 chars** (vs Day-8's 134) — driven by LOOKFANTASTIC cluster captions (Unbox with Chloe lead is 137 chars + product-list runners ~180 chars) + Chloe Ferry Dr.Melaxin confession (~250 chars Geordie-toned long copy). Organic caption length expands to **110 chars** (vs Day-8's 92) — pulled by Jodie + Sasha LOOKFANTASTIC product-list copy + SKINETICS sourcing-defense long-form caption. **NEW Day-9 caption-pattern 1: @LOOKFANTASTIC inline retailer-tag at 17% of AD + 30% of organic captions** — first instance in benchmark of a retailer-aggregator inline-tag appearing more in organic captions than AD captions (because Shop affiliate disclosure flags as organic). **NEW Day-9 caption-pattern 2: #kbeautyedit + #beautybox retailer-bag hashtags at 8-20%** — first retailer-curated-bag hashtag stack to surface as structural-frequency. **For IE briefs: @LOOKFANTASTIC inline tag at 17%+ is the cleanest IE-portable retailer signal** — LF ships to IE today, no Boots-IE shelf-gating required. **The Day-8 Romanian/Polish diaspora-PAID caption-pattern softens** (Paula BOJ absent from fresh, Gonceariuc carry only) — diaspora-language sub-template flips from STABLE to DECLINING-WATCH.

## Sound distribution (fresh pool n=74)

| Sound type | AD count | Org count | Notes |
|---|---|---|---|
| Original audio / talking-head VO | 30 | 7 | Most organic — Kerri Roma, LoveMagicandSarah, AndreEA "Replying", Makeup by Katy A, SKINETICS, Chloe Ferry Geordie confession |
| Trending UK pop snippet (15–30s) | 8 | 0 | Brand-supplied pop continues; no fresh K-creator on Day-9 NEW sounds (Taylor Swift / PinkPantheress×Larsson / sombr) |
| Brand-supplied jingle / brand B-roll audio | 6 | 0 | Smuuti Mini Kit, AXISY UK, mixsoon.uk Sun Serum, glow UK official, Mrs B medicube ×3 |
| Voiceover-on-stock (template) | 11 | 0 | Mrs B medicube ×3, Mrs B Peel Shot Duo, ✨Kim✨ pore routine, Heidi medicube |
| Hashtag-only / no narration | 5 | 0 | Tania_Khan #birminghamuk 47s, AndreEA "tiktokmademebuylt #koreanskincare", little_miss_happyy 25s |
| L'Oréal Glass Skin paid-creator squadron voiceover-on-jar-hero (Day-8 NEW) | 1 fresh (Alana) | 0 | Western-template voiceover; Alana adds to n=5 squadron — same audio mechanic as the original 4 |
| Pedagogic narration over module-typography (Makeup by Katy A MISSHA UK NEW) | 2 | 0 | "Science class" voiceover layered on text-card typography — distinct sound-visual pair |
| Geordie celebrity-tier VO + bedroom-domestic ambient (Chloe Ferry Dr.Melaxin NEW) | 1 | 0 | 1.6M v "When your skin looses collagen" Geordie cadence over slow domestic ambient — celebrity-tier voice signature |
| Brand-channel quick-cut scarcity audio (Smuuti Mini Kit 9s NEW) | 1 | 0 | 9s brand-house edit — emoji-cue sound design distinct from creator template |
| Cross-vertical declutter narration (Kerri Roma carry-watch) | 0 | 1 | 69s VO, no K-brand named in audio |
| **NEW Day-9 sounds (Taylor Swift / PinkPantheress×Larsson / sombr) — zero K-skincare uptake** | 0 | 0 | "I Knew It, I Knew You" UK #1 + "Stateside" US #7 + "Homewrecker" UK Top 10 — all 3 at zero K-skincare uptake today |
| "RMB (Ring My Bell)" Aitch (CF Day-3) | 0 | 0 | Day-3 of zero K-skincare uptake — UK Manchester summer anthem; festival-bridge window still open |
| "LEMONADE" aespa ft. Becky G (CF Day-3) | 0 | 0 | Day-3 of zero K-skincare uptake — direct K-pop ↔ K-beauty overlap; window still open |
| "The One" Chrystal (CF Day-3) | 0 | 0 | Day-3 of zero K-skincare uptake — "find the one [product]" template still open |
| "Material Lover" Sienna Spiro (CF) | 0 | 0 | Day-3 of zero K-skincare uptake — UK chart peak #23, 29.1K TikTok videos |

**Read** (CARRY-FORWARD-CONFIRMED + 3 NEW pre-wave opportunity windows Day-9): **~70% of organic UK videos still use original/spoken audio** (7 of 10 fresh today) — 9th consecutive day this finding holds. **NEW Day-9 sound opportunity windows from `tiktok-sounds.md`**: three sounds enter the UK trending list at zero K-skincare uptake — **(1) Taylor Swift "I Knew It, I Knew You"** (UK #1 wk 18 Jun, 7th UK Number 1, Toy Story 5 nostalgia overlay — IE 18-34 grew up with Toy Story 1-4), **(2) PinkPantheress × Zara Larsson "Stateside"** (US #7, "GRWMs / outfit reveals / weekend recaps" Y2K register), **(3) sombr "Homewrecker"** (UK Top 10 + Ireland Top 10, "stole your routine" / "homewrecker glow-up" overlay). **Total Day-9 pre-wave UK-trending opportunity windows = 7 sounds at zero K-skincare uptake** (3 NEW + 4 CF: Aitch RMB Day-3, aespa LEMONADE Day-3, Chrystal The One Day-3, Sienna Spiro Material Lover Day-3). Tag: NEW + ZERO-UPTAKE-OPPORTUNITY-EXPANDED-7-SOUNDS-CONCURRENT.

## CTA distribution (fresh pool n=74)

| CTA type | AD count | Org count |
|---|---|---|
| Link in bio / Amazon storefront | 0 | 0 |
| TikTok Shop direct ("on TT shop", 🛒, "Medicubes official TikTok Shop") | 11 | 0 |
| Discount-shock ("Summer sale", "INSANE prices", "absolute steal") | 9 | 1 (Jodie LF Edit) |
| "Run don't walk" / urgency / "Grab yours now" | 3 | 0 |
| Retailer-tag ("@Boots UK", "@bootsuk", "@Sephora UK", "@LOOKFANTASTIC", "@TikTok Shop UK") | 11 | 3 (LOOKFANTASTIC Shop affiliate cluster) |
| No CTA — caption is story/explainer only | 14 | 5 |
| Soft CTA — engagement question | 5 | 1 |
| **NEW Day-9: Retailer-aggregator CTA ("Beautybox", "K Beauty Edit", "kbeautyproducts") — bag-as-CTA** | **5** | **3** |
| **NEW Day-9: Celebrity-name-drop soft-CTA ("after trying it myself, I can see why")** | **1** | 0 |
| **NEW Day-9: Pedagogic curiosity-payoff CTA ("what do these ingredients even do?!")** | **2** | 0 |
| **NEW Day-9: Brand-channel-scarcity CTA ("Mini Kit is finally back!" — restock-as-CTA)** | **1** | 0 |
| Store address / in-store booking CTA (KIBODI) | 0 | 0 (carry) |
| Discount-code organic CTA (NAJMASS5) | 0 | 0 (Najma Starlike Day-2 absent) |
| L'Oréal squadron CTA-light template (closing on aesthetic claim) | 1 fresh (Alana) | 0 |
| Sourcing-defense organic — no CTA (SKINETICS NEW) | 0 | 1 |

**Read** (CARRY-FORWARD + 4 NEW CTA sub-templates Day-9): Day-8's "TikTok Shop direct = #1 paid CTA" finding **holds Day-9** (11 instances, slightly down from 14 Day-8 as LF retailer-tag CTAs steal share). **Retailer-tag CTA jumps to 14 of 74 (19%, +9pp vs Day-8) — driven entirely by LOOKFANTASTIC Shop affiliate cluster**. **NEW Day-9 CTA-pattern 1: Retailer-aggregator CTA (bag-as-CTA)** — the K-Beauty Edit / Beautybox / kbeautyproducts hashtag stack itself functions as the action ask ("buy the bag = buy the K-routine"), distinct from buy-direct or retailer-tag-direct. **NEW Day-9 CTA-pattern 2: Celebrity-name-drop soft-CTA** (Craig Dean × Cardi B — implicit "if a US megastar uses it, you should too"). **NEW Day-9 CTA-pattern 3: Pedagogic curiosity-payoff CTA** (MISSHA UK "what do these ingredients even do?!" — explainer-as-conversion-driver). **NEW Day-9 CTA-pattern 4: Brand-channel-scarcity-restock-as-CTA** (Smuuti Mini Kit "is finally back!" — scarcity-cue = CTA). For IE briefs: **the bag-as-CTA via @LOOKFANTASTIC is the cleanest IE-portable mechanism Day-9** — no Boots-IE shelf gating, no Sephora-IE pop-up timing dependency.

## Closed captions (fresh pool n=74)

| State | AD count | Org count |
|---|---|---|
| Captions visible on-screen (inferred from format) | 50 | 8 |
| No captions visible / sparse | 14 | 2 |

CARRY-FORWARD CONFIRMED at 9th day. ~80% organic and ~78% AD use visible captions. UK Gen-Z muted-playback assumption holds across the 9-day window. **NEW Day-9 observation: pedagogic explainer-cards (Makeup by Katy A MISSHA UK) extend captions from subtitle-style to typography-as-content** (the text-card IS the content, not the subtitle of the content). Inferred from format — TikTok 403-block persists Day-9 — no actual frame inspection.

---

## The "winning ORGANIC recipe" (today's vs yesterday's)

**Yesterday's recipe** (Day-8, 2026_06_14):
- Mode B (store-tour) STRUCTURALLY-STABLE 9 days
- Mode H (KIBODI in-store booking) CARRY HELD
- Mode J (Najma Starlike POV-discount-code) CARRY-CONFIRMED-FRESH Day-8
- Mode K (Goatie05 POV-overhype-walkback double-post) carry-only Day-2
- Mode L (Kerri Roma cross-vertical algo-spillover declutter) NEW Day-8

**Today's recipe** (Day-9 — Mode B stable + Mode H stable + Mode J SKU-pivoted + Mode K FADED + Mode L DECLINING-WATCH + 1 NEW Mode M):

- **Mode B (store-tour)** holds + **STRUCTURALLY-STABLE 10 consecutive days** (longest format-stability run in benchmark — new ceiling). No fresh second instance Day-9; KIBODI Shoreditch 10.08% ER + Graces.faces Costco 7.76% + Graces.faces ex-Superdrug 6.79% + Ash 💓 Boots Bristol 13.26% all carry-stable. CARRY-FORWARD HELD.
- **Mode H (KIBODI in-store booking organic)** — carry-stable Day-9. Still single-instance — needs 2nd UK indie K-stockist post to graduate to format (Day-10 watch).
- **Mode J (POV-with-discount-code organic-affiliate, Najma Starlike NAJMASS5)** — **Day-2 absent from fresh pool on Starlike SKU**. **Najma profile ACTIVE via COSRX overnight mask 872v 9.17% ER fresh today** (same creator, different SKU, no NAJMASS5 code visible). Mode J narrow-version (Starlike-specific) DROP-WATCH Day-10; Mode J broad-version (organic-affiliate-with-K-brand-anchor) HOLDS via COSRX surface. Tag: **SKU-PIVOTED + PROFILE-ACTIVE**.
- **Mode K (POV-overhype-walkback double-post, Goatie05 Dr.Melaxin CACTOX)** — Day-3 of carry-only → **FADED Day-9 under 3-day rule**. Archived.
- **Mode L (cross-vertical algo-spillover, Kerri Roma "Clear up declutter" 8.8k 4.64%)** — Day-1 RESURFACED in fresh pool but **declining -6% (9.4k → 8.8k)** vs Day-8. Still above 50% threshold (4.7k floor). Mode L confidence HOLDS MEDIUM; 2nd cross-vertical confirmation still missing. **DECLINING-WATCH ARMED**, formal-DECLINING-flag eligible Day-10 if <50%.
- **NEW Mode M: Sourcing-defense long-form organic (SKINETICS. eye-cream defense 5.0k 3.18% 223s).** First **brand-founder defensive long-form** organic in benchmark. Format: brand-owner direct-camera + comment-section rebuttal + provenance/sourcing explainer + 200s+ duration + organic (no AD flag) + low-mid view ceiling (5k) at solid ER (3.18%). The mechanic is **defensive-trust-building via direct rebuttal of comment skepticism** — inverted from Mode L (paid-history-seeded organic spillover) into **organic-only direct-engagement**. Tag: **NEW + BRAND-FOUNDER-DEFENSIVE-LONG-FORM + ORGANIC-TRUST-MECHANIC**.

**What evolved**:
1. **Mode J SKU-pivots from Starlike → COSRX** Day-9. The discount-code mechanic is decoupled from the brand and creator-profile-loyalty becomes the persistent layer. **The diaspora-cluster ARCHETYPE HOLDS at n=4** (Najma × COSRX 872v 9.17% + Beauty_Kamcia 🇬🇧🇵🇱 × Anua + Aahmy Gurung 🇳🇵🇬🇧 × Dr.Reju-All + MASUK LIMITED × Beauty of Joseon 817v 2.93%). All at ≥3% organic ER on their brand picks. **For IE micro-creator briefs: the diaspora-cluster pattern is the most reliable organic-ER stratum in 9 days — book IE-Irish-diaspora-or-cross-cultural micro-creators (Polish-Irish / Brazilian-Portuguese-Irish / Lithuanian-Irish / Nigerian-Irish — direct portability) on COSRX / Anua / Dr.Reju-All / BoJ at 9%+ ER tier**.
2. **Mode B store-tour reaches 10 consecutive days of structural-stability** — still the longest format-stability run in benchmark.
3. **Mode L cross-vertical algo-spillover ENTERS DECLINING-WATCH** — Kerri Roma -6% Day-9, 2nd cross-vertical case still absent. The Day-8 "first bookable paid-to-organic 2-post sequence" thesis holds but confidence softens.
4. **NEW Mode M structural breakthrough Day-9** — sourcing-defense long-form organic is the **first organic format that wins on DEFENSE not novelty**. For IE indie K-stockists (Cloud 10 Beauty, Pureseoul Ireland equivalent if/when launched) facing consumer-side ingredient-provenance skepticism, the SKINETICS template (brand-founder + 200s+ + comment-rebuttal) is a portable defensive surface.

## The "winning PAID recipe"

**Yesterday's recipe** (Day-8):
- Volume workhorse: medicube (~50% AD share)
- 2nd workhorse: Dr.Melaxin (~18% AD share, softened from Day-7's 22%)
- L'Oréal Glass Skin paid squadron STRUCTURAL n=4 median 10.6% ER
- BOJ dual-SKU push EXPANDED via Nath Henry
- Dr.Reju-All K-Pharmacy creator-rotation EXPANDED via Boots-UK @wafasdiaries
- AESTURA Sephora-UK Scotland retail-launch (@theolivetreefamily)
- AXISY UK creator-AD pair UN-FADED
- BIOHEAL BOH FADED-Day-4

**Today's recipe** (Day-9 — medicube workhorse holds + Dr.Melaxin tier-shifts UP to celebrity + L'Oréal SQUADRON-LOCKED + LOOKFANTASTIC retailer-aggregator ENTERS + MISSHA UK NAD-explainer NEW + Smuuti Mini Kit RECOVERED):

- **Volume workhorse holds at medicube (~48% AD share)** — Mrs B ×3 Golden Glow + Peel Shot Duo + 8-pc Glass Skin Bundle + 3-step routine, Sasha medicube, Heidi medicube 8.3k, Callie Aiello pink serum 1.7k **4.84% (highest paid-creator ER on medicube today)**, Ash ✨ Salmon DNA 1.7k 2.75%, Amelia ✨Reviews medicube Kojic 2.3k, Sophie neale medicube 3.1k, multiple others. CARRY-FORWARD HELD.
- **Dr.Melaxin TIER-SHIFTS UP from creator-tier to celebrity-tier paid** — **Chloe Ferry Dr.Melaxin "When your skin looses collagen…" 1.6M v (live 1.7M) 0.38% ER lands TOP-1 paid slot today**. Per `creator-uk-female.md`: "Dr.Melaxin has bought celebrity airtime, not creator partnership… escalating from creator-tier paid to celebrity-tier paid." Plus same-creator Dr.Melaxin 7-pc bundle 135.9k 1.96% (live 139.2k) + 5-pc bundle 35.7k 0.87% + Geordie 5-piece-routine carry. **Promoted skincare monthly shop-rank #1 (CACTOX V-Lifting Mewing Band £174.1k GMV)** — paid-engine + celebrity-talent + Top-promoted-SKU triple-anchor. Tag: **CARRY-FORWARD PROMOTED-TO-CELEBRITY-TIER**.
- **L'Oréal Glass Skin SQUADRON-LOCKED at n=5 median 9.15% ER** — Lauren Franklin 28.57% + Beautytok 12.03% + Ash ✨ 9.15% + Alana 1.61% + MJ 2.34%. **Western-brand-K-aesthetic encroachment promoted from Day-8 STRUCTURAL HIGH (n=4) → Day-9 SQUADRON-CONFIRMED HIGHEST (n=5)** within 24h. The Day-8 forecast tracks. Tag: **NEW STRUCTURAL + SQUADRON-LOCKED + CRITICAL-URGENCY-CONFIRMED**.
- **NEW Day-9: LOOKFANTASTIC retailer-aggregator-bundle paid-affiliate template (Unbox with Chloe × LOOKFANTASTIC K-Beauty Edit bag 489.7k v / live 606.8k / 0.44% paid-affiliate at 11× algo-amplification)**. First time a retailer-curated multi-brand bag drives top-2 viral. **THG-owned LOOKFANTASTIC ships IE today** — retailer-aggregator-bundle format is the **first IE-portable paid mechanism that bypasses Boots-IE / Sephora-IE shelf-gating**. Tag: **NEW STRUCTURAL + RETAILER-AGGREGATOR-CHANNEL + IE-PORTABLE-FIRST**.
- **CARRY-FORWARD BOJ paid push HOLDS + EXPANDS via Apricot Peeling Gel quad-creator wave**: Chloe Ferry 13.1k 1.07% + Nath Henry 2.4k 1.56% (+ same-creator body exfoliator 4.5k 1.83%) + Anna 1.0k 0.95% bundle. Day-9 BOJ Apricot Peeling Gel push intensifies; the Day-8 Chloe Ferry + Nath Henry cousin-extended pair becomes a 4-post saturation wave on the same SKU. Plus **MASUK LIMITED 817v 2.93% organic surface returns** (diaspora-cluster cousin for BoJ).
- **NEW Day-9: MISSHA UK brand-entry via NAD-derm-explainer paid template** (Makeup by Katy A "Science class, Korean Skincare module. PDRN, NAD skin serum" 4.7k 3.21% + same-creator 886v 3.27% 40+ pivot). First MISSHA UK creator surface in benchmark. Tag: **NEW BRAND-ENTRY + NAD-INGREDIENT-FIRST + 40+ AGE-SEGMENT-FIRST**.
- **Smuuti Skin UK Mini Kit RECOVERED via NEW post** (108.2k v / live 160.6k / 0.04% paid-boost) — yesterday's Day-8 "DROPPED from 7d-window" verdict reversed by NEW brand-channel post on same channel. **Brand-channel-restock-scarcity-9s formalises as sub-variant.** Tag: **RECOVERED + SUB-VARIANT-FORMALISED**.
- **AXISY UK creator-AD pair EXPANDS Day-9** — n=4 fresh paid posts: ⋆:🎀𝒢𝒾𝑔𝒾🎀:⋆ 2.3k 0.43% Niacinamide Glow DUO + 877v 1.02% deep pore + 733v 0.68% SOMEBYMI AHA BHA + aleemahlifestyle 761v 0.39% Glow bundle. Brand-channel scalability confirmed. Tag: **CARRY EXPANDED**.
- **AESTURA Sephora-UK Scotland retail-launch (@theolivetreefamily)** — Day-1 of Day-8-NEW carry-watch. No 2nd Scotland-area surface today. Tag: **CARRY HOLD-DAY-1**.
- **Dr.Reju-All UK Boots-UK brand-channel paid (@wafasdiaries "Magic in a tube ✨")** — Day-1 of Day-8-NEW carry-watch. Aahmy Gurung × 3 organic carry. Day-4 of `#RejuAllSummerChallenge` UNTESTED ambassador-cadence. Tag: **CARRY HOLD-DAY-1**.
- **BIOHEAL BOH FADED Day-5** (zero new creator surfaces 5 days running) — **FADED-PERMANENT** per `trends-uk-ie.md` Day-7-critical threshold passed.

**Brand mix shift Day-8 → Day-9**:
- medicube holds at ~48% AD share (softens from 50% as LF cluster + Dr.Melaxin celebrity-tier + L'Oréal squadron displace share).
- Dr.Melaxin **tier-shifts UP** — share % stable at ~18% but spend-tier upgrades from creator to celebrity (Chloe Ferry 1.6M).
- **LOOKFANTASTIC ENTERS at ~10% AD share** (4-post Unbox with Chloe cluster + Jodie + Sasha) — first retailer-aggregator-bundle channel.
- L'Oréal Paris UK at ~7% AD share — Western-brand structural presence consolidating.
- MISSHA UK ENTERS at ~3% AD share — first NAD-creator brand.
- BIOHEAL BOH **FADED-PERMANENT Day-5**.

---

## Faded / evolving patterns

| Pattern | Day-8 status | Today (Day-9) | Verdict |
|---|---|---|---|
| Frishta confession (6.11% ER) | FADED Day-8 | Day-5 absent | FADED-PERMANENT |
| ElleMoonz GRWM (16.75% ER) | FADED Day-8 | Day-5 absent | FADED-PERMANENT |
| iona francis verdict-list (3.75% ER) | FADED Day-8 | Day-5 absent | FADED-PERMANENT |
| Chloe Marie Devlin validation-claim micro (16.04% ER) | FADED-CONFIRMED Day-8 | Day-5 absent | FADED-PERMANENT |
| **Goatie05 POV-overhype-walkback (Mode K)** | Day-2 carry-only Day-8 | Day-3 carry-only Day-9 | **FADED Day-9 (3-day rule)** |
| Modest-fashion Eniyah Rana | Day-3 carry-only Day-8 | **Eniyah Rana × medicube SPF FAVE 4.4k 1.77% paid fresh Day-9** | **CARRY-FORWARD RE-EMERGED via medicube SPF surface — STATUS REVERSED to ACTIVE** |
| Najma Starlike POV-discount-code Mode J (narrow) | CARRY-FORWARD CONFIRMED-FRESH Day-8 | Day-2 absent on Starlike SKU | **SKU-PIVOTED — narrow Mode J DROP-WATCH; broad Mode J HOLDS via Najma × COSRX 9.17%** |
| Paula BOJ Romanian Boots AD (diaspora-PAID) | CARRY-FORWARD CONFIRMED-FRESH Day-8 | Day-1 absent | **CARRY WATCH (Day-2 absent → DECLINING-watch)** |
| KIBODI Shoreditch in-store-booking organic | Day-2 carry-stable Day-8 | Day-3 carry-stable Day-9 | **CARRY HELD — 10 consecutive days of stability** |
| Salmon DNA curiosity-shock (medicube PDRN translation) | ESCALATED n=2 Day-8 | n=2 fresh Day-9 (Ash + Shopwithpoppy) | **CONFIRMED + STABLE** |
| L'Oréal Glass Skin squadron | NEW STRUCTURAL n=4 Day-8 | **SQUADRON-LOCKED n=5 Day-9 (median 9.15%)** | **PROMOTED → STRUCTURAL-HIGH → SQUADRON-LOCKED-HIGHEST** |
| Kerri Roma cross-vertical declutter (Mode L) | NEW Day-8 | -6% (9.4k → 8.8k) | **DECLINING-WATCH ARMED** (above 50% threshold) |
| Dr.Reju-All Boots-UK @wafasdiaries | NEW Day-8 | Day-1 carry, no 2nd creator | CARRY HOLD-DAY-1 |
| AESTURA Sephora-UK Scotland | NEW Day-8 | Day-1 carry, no 2nd Scotland | CARRY HOLD-DAY-1 |
| Stephanie Vavron medicube | DROPPED Day-8 (declining flagged) | **RECOVERED via NEW post 33.0k 2.87%** | **RECOVERED + creator-pivots-to-newer-SKU pattern** |
| Smuuti Skin UK | DROPPED Day-8 | **RECOVERED via Mini Kit NEW post 108.2k 0.04%** | **BRAND-CHANNEL RECOVERED via NEW SKU** |
| BIOHEAL BOH paid-wave | FADED-PERMANENT Day-4 Day-8 | Day-5 of FADED | **FADED-PERMANENT** |
| Chloe Ferry BOJ pair (42.7k + 34.6k) | DROPPED Day-8 | Day-2 absent | **CONFIRMED DECLINING** (BoJ paid pivots to Apricot Peeling Gel) |
| Najma vidivici sound-meta 7s | ARCHIVED Day-8 | Day-3 absent | ARCHIVED-PERMANENT |
| **NEW Day-9: LOOKFANTASTIC retailer-aggregator-bundle** | n/a | First instance n=4-7 cluster | **NEW STRUCTURAL + IE-PORTABLE-FIRST** |
| **NEW Day-9: International-celebrity-name-drop (Cardi B → Craig Dean)** | n/a | First instance n=1 | **NEW HOOK-VARIANT (MEDIUM confidence)** |
| **NEW Day-9: MISSHA UK derm-explainer NAD-pedagogic** | n/a | First instance n=2 same-creator | **NEW BRAND-ENTRY + NAD-FIRST + 40+ FIRST** |
| **NEW Day-9: Smuuti brand-channel-restock-scarcity-9s** | n/a | First sub-variant formalised | **NEW SUB-VARIANT (MEDIUM)** |
| **NEW Day-9: SKINETICS sourcing-defense long-form organic (Mode M)** | n/a | First instance n=1 (5k 3.18% 223s) | **NEW + ORGANIC-DEFENSIVE-LONG-FORM (MEDIUM-LOW)** |
| Cindy Lee / #gurwm / humor / before-after | ARCHIVED-PERMANENT 9+ days | 10+ days absent each | ARCHIVED-PERMANENT |

---

## Content strategy notes
*3 actionable for IE 18-34 women:*

1. **Book an IE micro-creator on a "LOOKFANTASTIC K-Beauty Edit (Ireland delivery)" retailer-aggregator bag post THIS WEEK — this is the highest-leverage IE-portable paid mechanism in 9 days because LOOKFANTASTIC already ships IE.** Day-9 confirms 11× organic-algo amplification on the retailer-aggregator-bundle format (Unbox with Chloe × LOOKFANTASTIC 489.7k listed / 606.8k live views / 0.44% paid-affiliate ER on 44.5k followers — cycle's strongest organic-algo signal). The mechanic: LOOKFANTASTIC (THG-owned, ships IE) curates a multi-brand K-bag, Shop affiliate promotes it, the retailer-frame ("I know my Korean skincare lovers will love this new bag") presupposes audience identity ownership and dodges single-brand-fatigue. **Brief structure**: 30-40s bag-as-protagonist opener + "I know my Irish K-skincare girlies will love this LOOKFANTASTIC bag" parasocial frame + #TiktokMadeMeBuyIt + #SummerSale + #kbeauty + #kbeautyedit + #beautybox + @LOOKFANTASTIC inline retailer-tag. Bookable creator profile: Dublin / Cork / Galway 40-80k follower Shop-affiliate-active K-skincare-adjacent micro. Production cost: €60. Delivery: 5 days. ER target: 0.4-0.6% paid-affiliate at 8-12× algo-amplification = 300-600k views equivalent. **This brief structurally bypasses the Boots-IE / Sephora-IE shelf-gating constraint that has held back the Day-7 K-Pharmacy + Day-8 AESTURA Sephora-Scotland + Dr.Reju-All Boots-UK plays for IE replication**. Cleanest IE-first-mover surface in 9 days.

2. **Pivot ALL K-brand IE creator briefs from "glass skin" to "glass skin in a [bottle/spray/form]" SKU-anchored variant WITHIN 48 HOURS — Day-9 L'Oréal Glass Skin squadron LOCKS at n=5 median 9.15% ER, "glass skin" SERP exclusivity for K-brands is structurally lost.** Squadron now (Lauren Franklin 28.57% + Beautytok 12.03% + Ash ✨ 9.15% + Alana 1.61% + MJ 2.34%) — Day-8 STRUCTURAL n=4 forecast ("by Day-14 logs 7-10 L'Oréal creators at 10%+ ER") tracks. K-brand defensive frame proven Day-9 at n=3: Callie Aiello × medicube pink serum "Glass skin in a bottle" 1.7k **4.84% ER** + Sharon × ANUA spray "Glass skin in a spray" 696v 1.14% + Mrs B × medicube radiance set "Glass skin and Radiance" 938v 0.63%. Pair with **Salmon DNA n=2 escalation** (Ash ✨ medicube + Shopwithpoppy medicube PDRN cream — the Western-friendly translation of PDRN ingredient story) for ingredient-anchor reinforcement. **For IE creator briefs**: book 3-5 Dublin / Cork micro-creators on the SKU-specific "Glass skin in a [bottle / spray / mask]" framing with medicube Collagen Niacinamide Jelly Cream (shop-rank #3 £213.5k GMV) OR ANUA PDRN Spray OR Biodance Bio-Collagen Real Deep Mask Pink (newlisted GB Shop today £6.59) OR pair with #jelloskin defensive aesthetic-category for compound coverage. Production cost: €60 × 4 = €240. ER target: 3-5% paid (Callie Aiello upper-bound proof). **Critical timing: 48h to deploy before L'Oréal squadron extends to n=6-8**.

3. **Brief one IE micro-creator on a "Science class, NAD+ skincare module — Numbuzin No.9 under-eye-patches before Boots IE stocks them" derm-explainer-pedagogic video THIS WEEK + commission one Dublin-Polish-Irish diaspora-cluster creator on a Najma-style profile-loyalty post on COSRX Snail / Anua / Dr.Reju-All.** Day-9 MISSHA UK proves the pedagogic-NAD frame works at 3.21% paid (Makeup by Katy A "Science class, Korean Skincare module. PDRN, NAD skin serum. But what do these ingredients even do?!" 4.7k 3.21% + same-creator 886v 3.27% 40+ age-segment pivot). Numbuzin No.9 NAD+ holds **captured-zero** on the IE creator side (per `trends-uk-ie.md` "2026 wonder ingredient NAD+" + Boots's "20 new brands" announcement). **Brief structure (a) — pedagogic-NAD**: derm-explainer / "Science class, Korean Skincare module" pedagogic opener + NAD+ ingredient-curiosity payoff + Numbuzin No.9 under-eye-patches as anchor SKU (£14 Boots UK, expected Boots IE landing 2-4 weeks per Mediheal IE precedent) + secondary 35-44 age-segment variant. Production cost: €100. ER target: 3-4%. **Brief structure (b) — diaspora-cluster (Najma-style)**: Dublin-Polish-Irish or Brazilian-Portuguese-Irish or Lithuanian-Irish micro-creator (5-30k followers) + 16-30s overnight-mask / cleanser / serum review + own-cultural-identity emoji-bracket convention + brand at-mention + organic (not paid) + zero-or-modest discount-code if available. Proven diaspora-cluster ER tier 9-14% organic (Najma × COSRX 9.17% + Aahmy Gurung Dr.Reju-All 14.47% + Beauty_Kamcia Anua 9.89% + MASUK LIMITED BoJ 2.93% organic). Production cost: €50. ER target: 8-12% organic. **Combined Strategy 1 + 2 + 3 cost: €60 + €240 + €100 + €50 = €450 single-week IE deployment**, capturing first-mover position across (a) the NEW retailer-aggregator channel via LOOKFANTASTIC IE-ship, (b) the SKU-specific "glass skin in a [form]" defensive pivot against L'Oréal squadron lock, (c) the NAD+ ingredient-story captured-zero on Numbuzin, and (d) the 9-day-proven diaspora-cluster organic 9%+ ER tier. Compatible with and additive to Day-8 €660 strategy (jello skin + K-Pharmacy + Kerri-Roma mum-segment 2-post sequence still valid) — combined two-week deployment ~€1,110.

---

## Data quality

- **Source**: Today's FastMoss CRON LANDED CLEAN at 00:14 Dublin (Monday post-weekend recovery confirmed) — n=30 viral_kbeauty_7d + n=50 viral_korean_skincare_7d + n=30 promoted_skincare_monthly + n=8 deep_video_top10 + n=30 newlisted_skincare_gb + n=30 growthrank_beauty_gb_daily + n=30 risingstar_beauty_gb + n=20 popular_music_uk + n=20 popular_hashtag_uk_7d. Working fresh-pool unique UK n=74 after dedup (counted directly from JSON). Cross-references: today's `viral-video-parse.md` Day-10 (5 NEW surfaces + L'Oréal squadron n=5 lock + 11× LOOKFANTASTIC algo-amp confirmed via `deep_video_top10.json`), `tiktok-sounds.md` Day-9 (3 NEW sounds: Taylor Swift UK #1 + PinkPantheress×Larsson US #7 + sombr UK Top 10), `tag-content-tracker.md` Day-9 (#pureseoul + #oliveyoung + #riman NEW; #pdrn + #kpharmacy promoted to BASE), `trends-uk-ie.md` Day-9 (K-Retailer pipeline triple-anchor + Numbuzin NAD+ wonder-ingredient), `creator-uk-female.md` 06-15 diff (Unbox with Chloe 44.5k follower "Bundle Evangelist" archetype confirmed as cycle's strongest organic-algo amplifier).
- **Italy drift**: not a factor today (UK pool only). Italian growthrank/risingstar files present but ignored per scope.
- **Sample bias**: fresh pool skews **paid-heavy at 86%** — sits in upper end of Day-3-to-Day-8 baseline band of 80-92% (mild softening vs Day-8's 89%). Organic n=10 includes 4 LOOKFANTASTIC Shop-affiliate self-disclosure posts (paid-affiliate-monetised but `is_ad=False` flag) — these drag the organic median ER down to 1.18% (face value); the **"true organic" sub-stratum (n=6)** sits at median ~3.4%, closer to the Day-3-to-Day-8 baseline band. **For analysis purposes, treat Shop-affiliate disclosure as a 3rd paid-stratum (alongside paid-spark and brand-channel-direct), not as organic**.
- **n constraints**: fresh-pool unique UK n=74, AD=64 / Org=10. Combined with the Day-8 carry pool (79 rows) the working frame is n≈153 carry+fresh. Length / hook / caption / sound / CTA distributions reported above are on the FRESH pool only (n=74) to avoid double-counting carry items already reported Day-8. The "Faded / evolving" table integrates both windows.
- **CARRY-FORWARD coverage**: Day-8 named 11 carryable patterns; **3 re-verified directly today via fresh pool** (Salmon DNA n=2 escalation HOLDS via Ash ✨ + Shopwithpoppy; L'Oréal Glass Skin squadron PROMOTED from n=4 STRUCTURAL to n=5 SQUADRON-LOCKED via Alana entry; Kerri Roma Mode L resurface at 8.8k 4.64% DECLINING-WATCH); **3 confirmed via cross-reference** (BOJ Apricot Peeling Gel quad-creator wave via Chloe Ferry + Nath Henry + Anna + body exfoliator; AXISY UK brand-channel-rotation EXPANDED n=4; Dr.Reju-All + AESTURA Day-1 carry-watch); **2 moved to FADED** (Goatie05 POV-overhype-walkback Day-3 → FADED; Modest-fashion Eniyah Rana REVERSED to ACTIVE via medicube SPF 4.4k 1.77% paid fresh surface — RE-EMERGED, not faded); **2 SKU-pivoted / DECLINING-WATCH** (Mode J narrow Starlike Day-2 absent → broad-Mode J HOLDS via Najma COSRX 9.17%; Paula BOJ Romanian Day-1 absent → DECLINING-watch Day-10); **3 carry-RECOVERED via NEW post** (Stephanie Vavron medicube + Smuuti Mini Kit + Najma profile via COSRX overnight).
- **Diversity check**: **5 NEW pattern variations** vs Day-8 — LOOKFANTASTIC retailer-aggregator-bundle (4-post cluster + 3 organic-disclosed = 7-post total surface), L'Oréal Glass Skin SQUADRON-LOCKED n=5 (Alana adds), International-celebrity-name-drop (Cardi B → Craig Dean), MISSHA UK NAD-derm-explainer (Makeup by Katy A "Science class" + 40+ pivot), Smuuti brand-channel-restock-scarcity-9s sub-variant, SKINETICS sourcing-defense long-form organic Mode M. **Meets the ≥2 NEW requirement at 5-6 NEW** (depending on whether Mode M counts as a separate variation from the Sourcing-defense visual). Adjacent NEW surfaces: 3 NEW UK trending sounds at zero K-uptake (Taylor Swift + Stateside + Homewrecker), #pureseoul + #oliveyoung + #riman hashtag NEW, dasique organic cross-vertical surface (slavianaglow lip-tint 583v 6.34%), MISSHA UK + LOOKFANTASTIC + dasique 3 brand-NEW entries. Total ~10 NEW elements catalogued.
- **DROP rule applied**: Goatie05 POV-overhype (Day-3 carry-only → FADED Day-9); Frishta / ElleMoonz / iona francis / Chloe Marie Devlin Day-5 absent → FADED-PERMANENT; BIOHEAL BOH Day-5 → FADED-PERMANENT (Day-7-critical threshold passed); Chloe Ferry BOJ pair Day-2 absent → CONFIRMED DECLINING (BoJ paid pivots to Apricot Peeling Gel); Najma vidivici sound-meta 7s ARCHIVED-PERMANENT; Cindy Lee / #gurwm / humor / before-after 10+ days absent → ARCHIVED-PERMANENT.
- **Confidence**: HIGHEST on L'Oréal Glass Skin SQUADRON-LOCK n=5 (5 distinct creators all FastMoss-direct in 7d window, median 9.15% ER mathematically robust); HIGH on LOOKFANTASTIC retailer-aggregator-bundle format (4-post AD cluster + 3 Shop-affiliate-organic confirms cluster mechanic; `deep_video_top10.json` enrichment verifies 489.7k → 606.8k live within-day +24% + 11× follower-to-view amplification); HIGH on Chloe Ferry Dr.Melaxin celebrity-tier-paid (1.6M v vid 7648908212489489686 verified in `deep_video_top10`); HIGH on Salmon DNA n=2 escalation HOLD (Ash ✨ 2.75% + Shopwithpoppy 0.75% — n=2 stable but wide ER variance Day-2 of escalation); HIGH on Mode B store-tour 10-day structural-stability; MEDIUM-HIGH on MISSHA UK NAD-derm-explainer (n=2 same-creator paid surfaces — same-creator clustering); MEDIUM on Smuuti brand-channel-restock-scarcity-9s sub-variant (n=2 over cycle but same channel); MEDIUM on Craig Dean × Cardi B celebrity-name-drop (n=1, hook-pattern needs Day-10 2nd surface); MEDIUM-LOW on SKINETICS sourcing-defense long-form Mode M (n=1, organic, distinctive but unreplicated); LOW on first-3-sec visual + closed-caption presence (assessed from caption text + creator format history — TikTok 403-block persists Day-9, no actual frame inspection).
- **DROP candidates for Day-10 (2026-06-16)**: Najma Starlike NAJMASS5 narrow Mode J (Day-3 of absent on Starlike SKU → DROP if no fresh Starlike resurface); Paula BOJ Romanian diaspora-PAID (Day-2 of absent → DECLINING-watch Day-10); Kerri Roma cross-vertical (DECLINING-WATCH, if <4.4k views Day-10 = formal DECLINING-flag); James Welsh PDRN debate (10-day-stale threshold reached Day-10 — DECLINING-flag eligible); Aahmy Gurung × Dr.Reju-All `#RejuAllSummerChallenge` (Day-5 of UNTESTED → status downgrade if no 4th post); Day-9 NEW Cardi-B-celebrity-name-drop (need n=2 to confirm hook-pattern); Day-9 NEW Smuuti brand-channel-restock-scarcity-9s (need 2nd brand-channel surface from Mixsoon/VT/Anua UK).
- **Day-10 priority**: confirm whether L'Oréal Glass Skin squadron extends to n=6-8 + whether a **2nd Western brand** (Garnier / No7 / The Inkey List Ectoin Hydro-Barrier / Cetaphil Korean-coded SKU) joins the K-aesthetic-claim space; confirm whether **2nd retailer-aggregator-bundle** surface appears (Cult Beauty K-bag? Boots K-Pharmacy bag? Sephora UK gift-with-purchase?); WebSearch for first **MEDIPEEL UK creator surface** (Day-3 captured-zero — 400-influencer event break-condition armed); 2nd UK **jello-skin creator** (carry — @hayleeyy_x still n=1); **Dr.Althea Boots UK creator break** (Day-4 of captured-zero + TikTok Shop GB SKU live today as accelerator); 2nd **brand-channel-restock-scarcity-9s** surface to confirm sub-variant; 2nd **Cardi-B-celebrity-name-drop** equivalent hook; whether **SKINETICS Mode M** sourcing-defense long-form has a 2nd surface (need replication for Mode M to lock).

— End of Day-9 content-pattern —
