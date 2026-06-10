# Viral Video Discovery — UK K-skincare — 2026-06-10

*Day 5 of 14. Carry-forward seeded from `daily_data/2026_06_09/viral-video-parse.md` (Day 4). Today's FastMoss raw pool sits in `daily_data/2026-06-10/fastmoss_raw/` — 12 files, 3,763 lines, **and a structural shift in collection: the 3 brand-search slots (biodance/centellian24/numbuzin) executed yesterday are NOT in today's pool**. Instead today's run executed deep_video enrichment on the top 8 viral videos + the standard viral_kbeauty_7d / viral_korean_skincare_7d / promoted_skincare_monthly / risingstar_gb / growthrank_gb / newlisted_skincare_gb files. **The Italy-drift bug from Day-4 has resolved — today's `viral_kbeauty_7d.json` returned 30 UK-tagged rows and `viral_korean_skincare_7d.json` returned 50 UK-tagged rows.** WebSearch surfaced 1 additional NEW UK video corroboration (Mediheal Boots launch chain). Diversity rule satisfied: 9 NEW creators/videos.*

## Tracking distribution
BASE: 3 / CARRY-FORWARD: 8 / NEW: 9

(BASE = videos seeded from the Day-1 brief watchlist; CARRY-FORWARD = videos re-verified vs. yesterday's pool or refreshed via today's deep_video pull; NEW = videos that did not appear in any prior day's parse — 8 from today's FastMoss 7d UK rows + 1 from WebSearch.)

---

## Top 20 viral videos
*Ranked by views × ER signal (organic prioritised over paid where views close). All UK. Views marked † refreshed via today's `deep_video_top10.json` pull. The Top 20 today blends (a) today's FastMoss 7d UK rows where they exceed prior-day floors and (b) carry-forward March-May videos still relevant in the 28-90d window.*

| # | Creator | Bucket | Country | Views | ER | AD | Caption hook (60ch) | Brand | Format | Publish |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Jake-Jamie | CARRY-FORWARD | UK | 2.4M | 1.20% | Y | Wait… you thought this was foundation? It's sunscreen | mixsoon | verdict | 2026-03-28 |
| 2 | Maryam | CARRY-FORWARD | UK | 2.1M | 2.62% | Y | One thing that can make me look like I've had 8 hrs sleep | Erborian | review | 2026-03-14 |
| 3 | amy🤠✨ | CARRY-FORWARD | UK | 2.1M | 0.35% | Y | A drop you don't want to miss!!! Medicube hypochlorous | medicube | haul | 2026-03-31 |
| 4 | Chloe Ferry | BASE+CF | UK | 1.6M | 0.50% | Y | I'm obsessed with this zero blackhead clay mask | medicube | review | 2026-05-13 |
| 5 | BeautyByNori | CARRY-FORWARD | UK | 1.5M | 0.69% | Y | Micro needling? Nvm — Erborian ginseng micro shot at home | Erborian | review | 2026-04-12 |
| 6 | Graces.faces_ | BASE+CF | UK | 653.2k | 7.76% | N | I'm back in the Costco beauty section & K-skincare prices | (multi) | store-tour | 2026-05-15 |
| 7 | Frishta | BASE+CF | UK | 446.4k | 6.11% | N | My version of no makeup… anyone else do this? | Erborian | firstimpressions | 2026-05-21 |
| 8 | Chloe Ferry | BASE+CF | UK | 330.9k | 0.35% | Y | If you're aging over 30 you need this Korean 5 piece | Dr.Melaxin | haul | 2026-05-20 |
| 9 | Chloe Ferry | BASE+CF | UK | 298.9k | 0.82% | Y | Me and Nath Henry are skin influencers now 😂 | Dr.Melaxin | celebrity-reply | 2026-05-07 |
| 10 | **Stephanie Vavron** | **NEW** | UK | 254.4k† | 0.67% | Y | Say goodbye 👋 to pores and blemishes w/ medicube bundle | medicube | review | 2026-06-04 |
| 11 | SAMIE ELISHI | CARRY-FORWARD | UK | 751.9k | 1.90% | Y | sunscreen that feels like serum>>> Biodance | Biodance | review | 2026-05-22 |
| 12 | ElleMoonz🤍☁️🧸 | CARRY-FORWARD | UK | 184.8k | 16.75% | N | GRWM Alexander's first day of school 🥹📚 | Biodance+multi | grwm | 2026-05-14 |
| 13 | JEN M | CARRY-FORWARD | UK | 129.7k | 0.30% | Y | No white cast, no pilling — Biodance melts into skin | Biodance | review | 2026-05-29 |
| 14 | Kerri Roma | CARRY-FORWARD | UK | 128.8k | 0.53% | Y | Hydrated, glowy, plump after one mask 💜 Caviar PDRN | Biodance | review | 2026-05-31 |
| 15 | **Smuuti Skin UK** | **NEW** | UK | 102.2k† | 0.05% | Y | PEACHY RESTOCK ALERT! 🍑 Peach Barrier Toner restocked | Smuuti Skin | review | 2026-06-05 |
| 16 | **Eniyah Rana** | **NEW** | UK | 51.4k† | 0.75% | Y | EVERY SINGLE TIME!!! medicube PDRN #modeststreet | medicube | review | 2026-06-04 |
| 17 | **Chloe Ferry** (BOJ peel) | **NEW** | UK | 39.5k† | 0.84% | Y | The glow was hiding under dead skin all along — BOJ peel | BOJ | firstimpressions | 2026-06-05 |
| 18 | **Lou☁️** | **NEW** | UK | 30.8k† | 0.14% | Y | my saviour #medicube #hypochlorus #koreanskincare | medicube | review | 2026-06-05 |
| 19 | **Chloe Ferry** (BOJ NEW IN) | **NEW** | UK | 32.2k† | 0.68% | Y | 🍑 NEW IN 🍑 BOJ Apricot Blossom Peeling Gel | BOJ | review | 2026-06-05 |
| 20 | **Lou☁️** (glass skinnnn) | **NEW** | UK | 18.0k† | 0.25% | Y | everything you need for glass skinnnn 🌞✨ medicube | medicube | grwm | 2026-06-03 |

**Refresh deltas (deep_video_top10.json against publish-date views)**:
- Stephanie Vavron 201.2k → **254.4k** (+26%, 6 days after publish — strongest 7d paid trajectory in today's pool)
- Eniyah Rana 45.0k → **51.4k** (+14%, the #modeststreet medicube run continues to accumulate)
- Lou☁️ "my saviour" 30.5k → **30.8k** (flat, mature within 5 days)
- Lou☁️ "glass skinnnn" 16.7k → **18.0k** (+8%)
- Chloe Ferry BOJ "NEW IN" 19.3k → **32.2k** (+67%), Chloe Ferry BOJ "glow was hiding" 21.0k → **39.5k** (+88%) — **the Beauty of Joseon Apricot Blossom Peeling Gel paid push is the fastest-accelerating SKU in the deep-refresh pool**
- Smuuti Skin UK 31.8k → **102.2k** (+221%) — own-brand channel paid push, but ER collapsed from 0.12% to 0.05% (views grew, engagement did not)
- iona francis "Top 5 hydrating serums" 6.6k → **7.6k** (+15%, 7 days after publish, ER held at 3.5-3.75% — slowest paid grower but the only top-8 deep-refresh ORGANIC video)

---

## Paid vs Organic split

Working pool today = today's FastMoss 7d UK rows (~80 UK rows across viral_kbeauty + viral_korean_skincare) + deep_video_top10 enrichment + carry-forward.

| Bucket | Paid % | Organic % | Avg views (paid) | Avg views (organic) | Median ER (paid) | Median ER (organic) |
|---|---|---|---|---|---|---|
| 7d window UK (today's pool, ~80 rows) | **88%** | **12%** | 14.2k | 4.8k | 0.78% | **5.04%** |
| 28d window (carry-forward, 200+ rows) | 75% | 25% | 91k | 113k | 0.92% | 4.66% |
| 90d window (deep carry) | 88% | 12% | 891k | 154k | 0.78% | 4.20% |
| **NEW Day-5 additions (9 videos)** | 67% (6/9) | 33% (3/9) | 88k | 5.4k | 0.34% | **6.91%** |

**Day-5 drift signal**: The 7d UK organic-share **12%** today is exactly in line with the 90d rolling baseline — **the Italy-drift correction restored the 7d-paid-dominance signal we had from Days 1-3**. Today's median organic ER **5.04%** is the highest single-day organic ER median in the benchmark so far (Day-4 was 4.66%). The organic-to-paid ER multiplier in the 7d window is now **6.5× (5.04% / 0.78%)** — sharply above the Day-3 standing 4× figure. **The strategic implication holds: in the UK K-skincare creator pool, organic content is the ER signal; paid is the views signal.**

---

## Top ORGANIC videos (the real signal)
*Day-5 view: **micro-organic creators are the new ER ceiling** (Chloe Marie Devlin 16.04%, Najma🎋 12.26%, KIBODI STORE 10.08%, Olaide Arike Ganiyu 8.48% — all under 100k followers, all with sub-1k views, all >8% ER). Format diversifies: store-owner POV joins as a sub-pattern of store-tour.*

| Rank | Creator | Views | ER | Format | Brand named | Tag |
|---|---|---|---|---|---|---|
| 1 | ElleMoonz🤍☁️🧸 (Alexander GRWM) | 184.8k | **16.75%** | grwm | Biodance, MEDIHEAL, Clinique | CARRY-FORWARD |
| 2 | Chloe Marie Devlin (medicube PDRN gel mask) | 486 | **16.04%** | review | medicube | **NEW** |
| 3 | ElleMoonz🤍☁️🧸 (GRWM shopping) | 57.6k | **15.34%** | grwm | Biodance, anua, haruharu, Garnier | CARRY-FORWARD |
| 4 | Ash 💓 (Boots Bristol store-tour) | 56.9k | **13.26%** | store-tour | Biodance, medicube, anua, byoma, Bubble | CARRY-FORWARD |
| 5 | MaggieA (numbuzin toner pads + multi) | 99.5k | **12.92%** | review | numbuzin, RoC, Tatcha, Innisfree, No7 | CARRY-FORWARD |
| 6 | Najma🎋 (vidivici beauty ambassador) | 734 | **12.26%** | review | Vidivici | **NEW** |
| 7 | KIBODI STORE (Shoreditch K-skincare facial) | 694 | **10.08%** | store-tour (owner-POV) | (KIBODI house) | **NEW** — store-owner sub-pattern |
| 8 | Olaide Arike Ganiyu (AXISY toner) | 625 | **8.48%** | review | AXISY | **NEW** |
| 9 | Graces.faces_ (Costco) | 653.2k | 7.76% | store-tour | (multi) | BASE+CF |
| 10 | Graces.faces_ (ex-Superdrug) | 127.3k | 6.79% | store-tour | medicube, TIRTIR, Biodance, anua | CARRY-FORWARD |
| 11 | faith_succexx (Replying to Uduwan) | 34.7k | 6.35% | celebrity-reply | Biodance, BOJ, Clinique, e.l.f. | CARRY-FORWARD |
| 12 | Frishta (Erborian "anyone else do this?") | 446.4k | 6.11% | firstimpressions | Erborian | BASE+CF |
| 13 | Sharon 💋 (medicube PDRN explainer) | 578 | **5.36%** | dermatologist-led | medicube | **NEW** |
| 14 | James Welsh 💜 (@trishapaytas) | 135.1k | 5.07% | celebrity-reply | none | BASE+CF |
| 15 | MASUK LIMITED (Beauty of Joseon review) | 7.6k | **4.02%** | review | Beauty of Joseon | **NEW** (pivoted creator, full BOJ review) |
| 16 | iona francis (Top-5 hydrating serums) | 7.6k† | **3.75%** | verdict | Abib, anua, IUNIK, TIRTIR, Biodance | **NEW** (second verdict video by same creator in 7 days) |
| 17 | LoveMagicandSarah (medicube PDRN capsule cream) | 679 | 2.94% | review | medicube | **NEW** (organic launch reaction post-paid one) |
| 18 | Hannah Wilkie (Yepoda partner) | 997 | **4.31%** | review | Yepoda | **NEW** brand (Yepoda first surface in benchmark) |
| 19 | Aimée Isabella (Narae UK overnight mask) | 998 | **4.10%** | review | Narae UK | **NEW** brand (Narae UK surfaces) |
| 20 | bodyNsoul Beauty (medicube PDRN Pink) | 1.9k | 1.23% | dermatologist-led | medicube | **NEW** (over-50 audience explainer) |

**Day-5 organic findings**:
- **Micro-organic ER ceiling is REAL.** Five of today's NEW organic finds (Chloe Marie Devlin 16.04%, Najma🎋 12.26%, KIBODI STORE 10.08%, Olaide 8.48%, Sharon 5.36%) all sit between 9-95k followers with sub-2k views and 5-16% ER. This is the same ER profile as the Centellian24 long-tail UGC noted Day-4 (dziosefinajlk 33%, Charna 21%, Bruna 19%). **The pattern is structural to the UK K-skincare creator pool, not idiosyncratic to one brand.** ER ceiling is in the micro-creator stratum (<100k followers), NOT the mid/macro (100-500k) layer.
- **KIBODI STORE introduces a store-owner sub-pattern of store-tour.** Whereas Graces.faces / Ash do walkthrough-the-shelves at chain retailers, KIBODI STORE (a Shoreditch indie K-skincare boutique) does owner-POV: "I run this store, here's why this facial is the move." 10.08% ER on a 1.5k-follower account. This is an IE-translatable pattern — any Dublin indie K-beauty stockist could clone it.
- **MASUK LIMITED post-pivot fully active.** The creator that pivoted from "Korean Sunscreens Banned" controversy (Day-1/2) → numbuzin paid posts (Day-4) → today's full-length Beauty of Joseon review (7.6k, 4.02% ER, organic). Confirms the PIVOTED verdict from Day-4 and adds depth: pivoted creator is doing serious long-form K-skincare reviews now, not just product placements.
- **iona francis adds a SECOND verdict in 7 days.** "Top 5 K-beauty hydrating serums" (Abib + anua + IUNIK + TIRTIR + Biodance, 3.75% ER) follows her "Top 5 Korean serums for anti-aging" video (2.6% ER, Day-4 NEW). Two clean verdict templates from the same creator in one week — **iona francis is the verdict-format prototype for IE replication**, alongside Frishta-confession and faith_succexx-celebrity-reply.
- **Two NEW brand surfaces: Yepoda and Narae UK.** Hannah Wilkie (5.4k followers, Yepoda partner — exfoliating pads, ad-disclosed but organic-tagged) and Aimée Isabella (34.8k followers, Narae UK collagen masks). Neither brand has appeared in Days 1-4 — Yepoda is a German-headquartered K-beauty brand expanding UK; Narae UK is an indie K-beauty brand with overnight mask focus. **Both surface in the small-follower-count organic layer, not the paid wave.** Watch slot opened.

---

## Format distribution
*Across the Top-50 ranked pool (yesterday's FastMoss carry + today's 80 fresh UK rows + 1 WebSearch corroboration), by format taxonomy:*

| Format | Count | Avg views | Avg ER | Notable today |
|---|---|---|---|---|
| review (single product) | 32 | 392k | 1.04% | medicube PDRN cluster expands: Lou×4, Eniyah Rana×3, Sharon, Chloe Marie Devlin all naming PDRN within 7 days. BOJ Apricot Blossom Peeling Gel is the NEW SKU surge (Chloe Ferry×2, Goatie05×3) |
| haul / 5-piece bundle | 9 | 218k | 0.66% | Stable |
| grwm | 8 | 134k | **6.92%** | Lou "glass skinnnn", Ashleigh McNab nighttime, AndreEA — count up 7 → 8; ceiling still 16.75% |
| store-tour | 5 | 187k | **8.86%** | **Now FIVE examples.** Graces.faces×2 + Ash Boots Bristol + Frishta Don Quixote + KIBODI STORE owner-POV (NEW Day-5 sub-pattern). ER median rises to 8.86% (from 6.97% Day-4) |
| celebrity-reply | 4 | 137k | 3.94% | No fresh today — Stable |
| firstimpressions | 4 | 168k | 4.10% | Chloe Ferry BOJ "glow was hiding" NEW today (paid, 0.84%) |
| verdict (named comparison) | 5 | ~22k | **3.13%** | iona francis "Top 5 hydrating serums" NEW (3.75%) — second iona verdict video in 7 days |
| dermatologist-led / explainer | 4 | 503k | 2.82% | Sharon 💋 medicube PDRN explainer NEW (organic, 5.36%) — micro-creator explainer surfaces |
| debate / skepticism | 1 | 29.2k | 4.33% | James Welsh PDRN (carry, frozen) |
| humor | 0 | — | — | **Day 5 of FADED** |
| before-after | 0 | — | — | **Day 5 of FADED** |
| #gurwm | 0 | — | — | **Day 5 of FADED** — drops permanently from active format taxonomy |

**Format shifts Day-4 → Day-5**:
- **store-tour gets a 5th example AND a new sub-pattern.** KIBODI STORE (Shoreditch K-skincare boutique owner) does owner-POV walkthrough, a sub-pattern of store-tour where the camera-holder is the store owner, not a customer. ER 10.08% on a 1.5k-follower account. **The store-tour family format now branches into (a) customer-walkthrough chain-retailer (Graces.faces, Ash) and (b) owner-POV indie-store (KIBODI). Both 8%+ ER.** Pattern is robust across both branches.
- **verdict count up 4 → 5.** iona francis second verdict video confirms the verdict format is a single-creator-replicable lane. The two iona verdicts together name 10 different K-skincare SKUs across 7 brands — high information density per video, organic-tagged.
- **dermatologist-led count up 3 → 4.** Sharon 💋 medicube PDRN explainer (organic, 5.36%) is the first organic dermatologist-led video in the pool — previously all dermatologist-led was paid (Frishta PSA, iona Erborian microneedling). Suggests the format is now creator-led, not just brand-briefed.
- **review count up 28 → 32.** Driven by today's fresh medicube + BOJ + Dr.Melaxin paid pool. ER median holds 1.04% (paid-dominant).

---

## Caption hook patterns (top 10)
*Hooks abstracted from the Top-50 + 9 NEW captions. Counted by structural pattern.*

| # | Pattern | Count | Best example | Avg ER |
|---|---|---|---|---|
| 1 | "I'm obsessed with [brand/category]" | 9 | Stephanie Vavron "Say goodbye to pores" medicube bundle | 0.70% (paid) |
| 2 | "Wake up to / Hydrated, glowy, plump after one [product]" | 4 | Aimée Isabella Narae overnight mask NEW (4.10%) | 0.65% (paid+org) |
| 3 | "Replying to @[user]" / "Replying to @[micro-celebrity]" | 6 | faith_succexx (CARRY, 6.35%) | 2.45% mixed |
| 4 | "No white cast / No sticky SPF / No pilling" (denial-hook) | 4 | Stable | 0.40% (paid) |
| 5 | "anyone else do this?" / Frishta confessions | 4 | Frishta (CARRY) | **5.50%** |
| 6 | Personal-life GRWM ("first day of school", "nighttime grwm") | 8 | ElleMoonz + Ashleigh McNab nighttime (NEW) | **6.92%** |
| 7 | "Korean skincare is [trending/saving me]" | 12 | DanMadeMeBuyIt "Korean skincare is saving me 😮" NEW | 0.65% |
| 8 | "INSANE prices" / "57% off" / store-tour shock | 5 | KIBODI STORE Shoreditch indie NEW (10.08%) | **8.86%** |
| 9 | "Spray-on glass skin" / "everything you need for glass skinnnn" | 4 | Lou "everything you need for glass skinnnn" NEW (18.0k) | est 1-2% (paid) |
| 10 | Multi-product verdict list ("Top 5 [brand] [outcome]") | 4 | iona francis "Top 5 hydrating serums" NEW (3.75%) | 3.13% |
| **NEW** | "🍑 NEW IN 🍑 / [emoji-product] launch announcement" | **3** | Chloe Ferry BOJ "NEW IN" (32.2k, 0.68%) | 0.80% (paid) |

**Hook insight Day-5**:
- **The "🍑 NEW IN 🍑" launch-announcement pattern surfaces as the new SKU-launch hook.** Three videos this week (Chloe Ferry × 2 BOJ Apricot Blossom Peeling Gel + LoveMagicandSarah medicube PDRN Capsule Cream organic launch reaction) use the "🍑 NEW IN 🍑" or equivalent emoji-product-launch opener. The Chloe Ferry videos drove the strongest deep-refresh delta in the pool (+88% and +67% in 5 days). **This is the brand-paid launch-announcement hook, distinct from the brand-paid catalog-restock denial-hook noted Day-4.** IE creators with brand-paid launch briefs should adopt this template.
- **The "Korean skincare is saving me" / "Korean skincare is [outcome]" pattern is the highest-volume caption in the pool (12 instances, up from 11 Day-4)** but it is also the lowest-ER caption (0.65%). This is a generic-paid-tag hook — high prevalence, low engagement. **Diagnostic for IE creators: do NOT use this opener unless it's a paid post obligation.**
- **The store-tour shock-price hook ("INSANE prices", "57% off", "this shop is like being a kid in a candy store") averages 8.86% ER across 5 examples.** KIBODI STORE NEW pushes the ER median up. The hook's structural element is **specificity + a reaction beat** ("this £14 for 5 full-size products is insane" — Goatie05 paid bundle video uses this template at 0.65% ER, which suggests the hook + format pairing matters: shock-price-in-store > shock-price-on-screen).

---

## Brand presence (AD vs organic split)
*Brand mentions across the Top-50 + 9 NEW pool, split by paid/organic:*

| Brand | Paid views (cumulative) | Organic views | Notes |
|---|---|---|---|
| medicube | 9.5M (with Stephanie Vavron 254k† + Eniyah Rana 51k† + Lou 49k† + Ashleigh McNab × 2 + Alana + LoveMagicandSarah × 2 + Sharon + Wishuglam + Mia Noid + Sewfy + IZ'S FINDS + AXISY + others NEW today) | 446k (Frishta) + 127k (Graces.faces) + 1.9k (bodyNsoul) + 578 (Sharon) + 486 (Chloe Marie Devlin) + 679 (LoveMagicandSarah PDRN capsule) | **medicube is the most-saturated paid brand in today's 7d UK pool.** PDRN remains the lead-SKU theme. PDRN Capsule Cream is the NEW launch SKU (just dropped this week, organic creator surface starting) |
| Dr.Melaxin | ~9.6M + Char × 3 (5.4k cumulative NEW) + Bina13 (1.9k) + Ashleigh McNab × 1 + TanyaS1988 + JAZMINE ROSE + AndreEA | 0 | 100% paid. NEW Day-5: CACTOX V-LIFTING MEWING BAND surges to **rank 1 in promoted_skincare_monthly with £174.1k GMV in 30d**, 12.9k units. The mewing-band SKU joins the spicule-lip plumper as a Dr.Melaxin device-tier SKU. Watch for creator surface Day-6/7 |
| Biodance | 1.2M+ (paid cluster carry) | 184k (ElleMoonz) + 127k (Graces.faces) + 102k (Tat'heer Fatemah) + others | **No fresh Biodance brand-search today** — carry holds. iona francis names Biodance hydro cera-nol ampoule in her Top-5 hydrating serums verdict (NEW organic mention) |
| Beauty of Joseon | 55k (carry) + **Chloe Ferry × 2 BOJ Apricot Blossom Peeling Gel (32.2k + 39.5k† NEW)** + Goatie05 × 3 Ginseng+Retinal eye set + DanMadeMeBuyIt tinted SPF | 7.6k (MASUK LIMITED full BOJ review, NEW organic) | **Beauty of Joseon Apricot Blossom Peeling Gel is the NEW SKU launch wave** — Chloe Ferry's two paid videos drove +67% and +88% deltas in 5 days. The Goatie05 cluster (3 paid videos in 1 day for Ginseng+Retinal eye set) is the same-day-multi-post format from a 22.8k-follower paid creator |
| Erborian | 9.5M (carry, no fresh today — no Erborian brand search this cycle) | 1.1M (Frishta PSA, carry) | Mature carry |
| MEDIHEAL UK | 144k (carry) + Boots UK house-channel launch video (WebSearch corroborated — TheIndustry.beauty confirms 4-of-6 SKUs sold out in 3 days post October-2025 online launch, Boots store rollout from December 2025, wider 2026 rollout planned) | 184k (ElleMoonz GRWM indirect carry) | **Mediheal Boots launch is a 2026-wave brand expansion — wider rollout planned across 2026 per TheIndustry.beauty. Boots UK / Boots Ireland retailer-tier amplification thesis holds.** No fresh creator surface today |
| mixsoon | 2.4M (Jake-Jamie carry) + 2.4k (Makeup by Katy A NEW today, tinted moisturiser, organic-tag-but-AD-disclosed) + Eniyah Rana × 1 + Georgiana Stamate × 1 | (small) | Carry + 3 fresh paid hits today |
| BIOHEAL BOH | ~380k (carry) + Eniyah Rana 1.5k NEW today ("THIS THIS AND THISSSSS #bioheal #biohealboh") | 0 | **BIOHEAL BOH paid wave gets a single fresh hit today** (Eniyah Rana, 1.5k views, 2.38% ER, paid). Compared to Day-3's ~380k cumulative figure, this is a stall — the paid-wave-entry thesis from Day-3 is now downgrading to MATURE rather than new. No new creators activated this week |
| d'Alba | (carry, Italian White Truffle First Spray Serum holds rank 9 in promoted_skincare_monthly, £202k GMV, 22.1k units 30d — **strongest pure-paid K-brand catalog SKU**) + Eniyah Rana × 2 (#dalba #dalbamist 5.2k + 5.2k) + Beauty With Rhianne × 1 (#dalba multi-balm 2.2k) | 0 | d'Alba is the third-rail K-brand on TikTok Shop UK paid promotion — high GMV, high promoted-skincare ranking, near-zero organic creator surface. Wonderskin-style pattern (catalog-paid only) |
| AXISY | 678 (AXISY UK own channel, paid) + 625 (Olaide Arike Ganiyu, organic, **8.48% ER**) | 625 (Olaide) | **AXISY is the NEW Day-5 brand of note** — surfaces with own-channel paid + a high-ER micro-organic mention in one week. Toner-focused, light surface but high organic-ER signal |
| Smuuti Skin UK | 102.2k† (own brand, NEW today's deep_video — +221% paid growth in 6 days) + 2.5k (Limited stock) | 0 | Self-brand channel paid push. ER collapsed (0.12% → 0.05%) as views grew — paid views without engagement |
| Yepoda | 997 (Hannah Wilkie, ad-disclosed but organic-tagged, **4.31%**) | 997 (same row, ad-disclosed) | **NEW brand Day-5.** German-HQ K-beauty brand expanding UK. First surface in this benchmark. Watch slot opened |
| Narae UK | 998 (Aimée Isabella, paid) + 870 (Aimée Isabella second post, paid) | (paid-tagged but organic-style content, 4.10% + 4.48% ER) | **NEW brand Day-5.** Indie K-beauty overnight collagen mask focus. Two posts same creator within 1 day. Watch slot opened |
| Vidivici | 0 | 734 (Najma🎋, ambassador-tagged, **12.26%**) | NEW brand Day-5. Najma🎋 holds "#skinseoulambassador" tag — micro-organic ambassador surface, high ER, tiny views |
| KIBODI STORE | 0 paid | 694 (KIBODI STORE owner-POV, **10.08%**) | NEW Day-5 — **independent Shoreditch K-skincare boutique with own TikTok channel doing owner-POV store-tour content**. House-brand and house-services pivot. Direct IE-translatable pattern (e.g. for a hypothetical Dublin equivalent) |

**Strategic read updated Day-5**:
- **medicube is now the saturated UK-paid K-brand.** Today's pool yielded 20+ medicube paid posts in 7 days from 15+ different creators. The PDRN family is the lead-SKU theme. **PDRN Capsule Cream just launched this week** (LoveMagicandSarah organic launch reaction post, paired with her own paid medicube post 4 days prior). Watch for the PDRN Capsule Cream creator wave Day-6/7.
- **Beauty of Joseon Apricot Blossom Peeling Gel is the NEW SKU-launch wave** — Chloe Ferry × 2 paid videos with **+67% and +88% 5-day refresh deltas** are the fastest-accelerating paid videos in the deep-refresh pool. The "🍑 NEW IN 🍑" emoji-launch hook is the template. This is functionally the BOJ replacement for the Ginseng+Retinal eye set that's still being pushed (Goatie05 × 3).
- **Dr.Melaxin device-tier pivot confirmed.** CACTOX V-LIFTING MEWING BAND now ranks #1 in `promoted_skincare_monthly` at £174.1k GMV / 12.9k units. Combined with the spicule-lip plumper +1184% growth flagged Day-4, **Dr.Melaxin is structurally pivoting from skincare-only into device-tier (mewing band) + lip-plumper (spicule)**. This is a brand-strategy signal, not just a SKU signal: Dr.Melaxin is moving into the high-ASP K-skincare device category that Medicube's own AGE-R devices already occupy.
- **Two new brand watch slots: Yepoda + Narae UK.** Both surface organically in the micro-creator stratum (5-35k follower range). Yepoda is mid-stage UK expansion; Narae UK is indie-tier. Neither is a structural threat to the medicube/Dr.Melaxin/Biodance triumvirate, but both are early-warning signals of the long-tail UK K-skincare brand entry.

---

## Declining/faded carry-forwards

| Video / format | Yesterday | Today | Verdict |
|---|---|---|---|
| Cindy Lee #gurwm (15.4k, 8.54%) | FADED Day-3 | Absent | **FADED** (5 days absent) — archived |
| Chloe Ferry × Dr.Melaxin "skin influencers" (298.9k) | STABLE-DEAD | Same 298.9k frozen | STABLE-DEAD |
| ZhilaBeauty "5-min skincare" (68.5k, 7.31%) | FADED Day-3 | Absent | **FADED** (5 days absent) |
| #gurwm format | FADED Day-3 | 0 #gurwm Day 1-5 | **FADED permanently** — dropped from active taxonomy |
| MASUK LIMITED "Korean Sunscreens Banned" (265k) | PIVOTED Day-4 | Today: full BOJ review 7.6k, 4.02% organic (NEW organic) | **PIVOTED & ACTIVE** — original video stays archived, creator confirmed K-skincare reviewer |
| Amy Burnside Mixsoon before/after (111k) | FADED Day-3 | Absent | **FADED** (5 days absent) |
| Maryam Erborian Ramadan (2.1M, 2.62%) | TEMPORALLY DECLINING | Same — March-dated | TEMPORALLY DECLINING |
| humor format | FADED Day-3 | Absent | **FADED** (5 days absent) — archived |
| before-after format | FADED Day-3 | Absent | **FADED** (5 days absent) — archived |
| Stephanie Vavron medicube (271.9k) | STABLE Day-4 | **NEW Day-5 medicube bundle 254.4k†, 6 days into 7d window — fresh velocity** | RECLASSIFIED: Stephanie Vavron is now ACTIVE-WAVE not STABLE — she's mid-paid-push, not plateau |
| BIOHEAL BOH paid-wave (~380k Day-3) | CARRY-PENDING Day-4 | Single Eniyah Rana hit (1.5k, 2.38%) today — no new creator activations | **DECLINING** — paid-wave thesis downgrades from "active wave" to "mature, no new entries". Will be FADED Day-7 if no new BIOHEAL BOH creator surfaces |
| becks.glow VT Reedle Shot 50 | STABLE Day-4 | Absent (no VT brand search) | STABLE — first-mover IE-creator window still open |
| princess99cosmetics MEDIHEAL PDRN | RE-CHARACTERISED Day-4 | WebSearch corroborates Boots Mediheal launch wider 2026 rollout | RE-CHARACTERISED — retailer-tier amplification thesis confirmed |
| Frishta Erborian "anyone else do this?" (446.4k, 6.11%) | BASE+CF | Same — May-dated, not in 7d pool | TEMPORALLY DECLINING (still relevant in 28-90d) |
| Ash Boots Bristol (56.9k, 13.26%) | NEW Day-4 | Same — May-dated, not in 7d pool | STABLE (still the only non-Graces UK chain-store-tour example) |
| Stephanie Vavron previous medicube push | STABLE Day-4 | Refreshed to 254.4k via new bundle video | ACTIVE — refreshed |

**Day-5 net format fades**: No new format fades. #gurwm, humor, before-after officially permanent fades (5 consecutive days absent → drop from active taxonomy).

**Day-5 net carry decline-watch**: BIOHEAL BOH paid-wave is the only thesis declining today. Eniyah Rana surfaced ONE BIOHEAL BOH post (1.5k views, 2.38% ER) in today's pool — a maintenance post, not wave-extension. **Day-6 decision: if no NEW BIOHEAL BOH creator (beyond the 5 already activated in Days 2-3) surfaces, downgrade thesis to FADED. The Day-3 paid-wave-entry thesis loses one of two confirmation windows.**

---

## Strategy notes
*3 actionable for IE 18-34 women:*

1. **Lock in the iona francis-style verdict format for an IE-Dublin creator brief THIS WEEK — name 5 K-skincare SKUs available at Boots Henry Street.** Day-5 confirms verdict is the most-creator-replicable organic format in the pool: iona francis has produced TWO verdict videos in 7 days (Top-5 hydrating serums + Top-5 anti-aging serums) and both pull 3-4% ER on under-10k views. Versus store-tour (which needs a physical retail venue) or grwm (which needs a personal-life beat), verdict is filmable in a bedroom with the products on a desk. **Brief: "Top 5 Korean skincare SKUs at Boots Henry Street under €30" — name Biodance Caviar PDRN Mask + Beauty of Joseon Apricot Blossom Peeling Gel (just launched, riding Chloe Ferry's wave) + medicube PDRN Pink Serum + Mediheal Collagen Toner Pads (rolling out wider 2026 per TheIndustry.beauty) + anua Heart-Leaf Toner.** This is a €100 production cost ceiling, deliverable inside 5 days, and aligned to live Boots IE shelf stock.

2. **Pre-empt the medicube PDRN Capsule Cream creator wave — IE creator brief should land BEFORE the UK paid wave saturates.** Day-5 data shows the medicube PDRN Capsule Cream just launched this week (LoveMagicandSarah's organic launch-reaction post follows her paid medicube post 4 days prior — same creator, paid → organic same-product sequence). The UK creator-paid wave for this SKU has not yet started in volume, which means the IE creator window is **right now, 5-10 days before the UK paid wave saturates the search graph**. Brief: 60-second "first impressions on the new medicube PDRN Capsule Cream after 7 days" with before/after texture shots. **Pair the same creator's brief with a follow-on verdict-format video naming PDRN Capsule Cream against 2-3 alternative PDRN-category SKUs** — capturing both the early-adopter view layer AND the SEO-anchor verdict layer.

3. **Open a watch slot for Yepoda and Narae UK as the long-tail UK K-brand entry signal — but DO NOT commission IE content for either yet.** Both brands surfaced organically for the first time in this benchmark (Day-5). Yepoda is German-HQ mid-stage UK expansion (Hannah Wilkie partner post, 4.31% ER on 5.4k followers); Narae UK is indie-tier overnight-collagen-mask focus (Aimée Isabella × 2 posts in 1 day, 4.10-4.48% ER on 34.8k followers). Neither has the structural creator gravity of Biodance / medicube / BOJ yet. **The right play: hold watch slot, re-check Day-7 and Day-10 for second-creator activation. If a non-paid-affiliated creator picks up Yepoda or Narae UK in Days 6-10, the brand is graduating to organic and worth an IE-creator first-mover bet. Currently both are single-creator-activation, which means brand-paid-only.**

---

## Data quality

- **Source mix today**: today's FastMoss raw JSON pool — 12 files in `daily_data/2026-06-10/fastmoss_raw/` totaling 3,763 lines. 7d UK viral pools restored to 100% UK after the Day-4 Italy-drift bug. `viral_kbeauty_7d.json` returned 30 UK rows, `viral_korean_skincare_7d.json` returned 50 UK rows, `deep_video_top10.json` enriched top 8 viral videos with refresh-deltas. `promoted_skincare_monthly.json` 30 rows surfacing the Dr.Melaxin CACTOX MEWING BAND rank-1 + medicube PDRN Capsule + BOJ + AXISY paid-rank surges. `newlisted_skincare_gb.json` 30 rows surfacing fresh SKU launches (Smuuti Peach Sun Cushion, Kishkin oils, Dr.Melaxin CACTOX Pore Relief). `growthrank_beauty_gb_daily.json` 30 UK creator-growth rows (none K-skincare-specialised, all generalist Beauty top creators). `risingstar_beauty_gb.json` 30 UK rising-creator rows (Stephanie Vavron viral_index 84 confirms). 1 supplementary WebSearch query corroborated the Mediheal Boots launch chain.
- **NO brand-search slots executed today.** Day-4 burned the 3 brand-search slots on biodance/centellian24/numbuzin; today's run did not execute brand-searches. This is the structural collection difference vs. Day-4: today's pool depth is shallower per-brand but broader across the 7d UK viral pools.
- **Italy-drift bug resolved.** Day-4's 100% Italy-tagged 7d pools are 100% UK-tagged today. The collection-reminder request for `country=GB` pinning may not have been needed — the issue resolved server-side. Day-4 missed signal: ~30 UK rows that would have appeared in 7d_kbeauty during Day-4 collection. Today's pool captures a 5-7 day window so some Day-4-missed velocity is now visible (Stephanie Vavron 254k†, Eniyah Rana cluster, etc.).
- **Network policy status**: TikTok direct fetch still 403-blocked. WebSearch works.
- **Sample bias**: 100% UK-tagged creators in today's 7d slice. NO IE creator in Day-5 pool — IE creator-pool vacuum holds for 5th consecutive day. Strategy #1 (verdict-format IE brief) is the structural intervention.
- **Organic n = 11 in 7d today** (vs 14 yesterday). Drop is brand-search-related, not signal-related — yesterday's 14 included 10 Biodance organic mentions surfaced via brand-search. Today's 11 organic mentions span 7 different brands (medicube, Beauty of Joseon, Vidivici, KIBODI, AXISY, Yepoda, Narae UK) — broader brand-spread, lower per-brand depth.
- **Diversity rule (≥3 NEW)**: **9 NEW videos/creators surfaced today** (8 from FastMoss 7d UK rows: Stephanie Vavron new bundle / Eniyah Rana / Lou☁️ × 2 / Chloe Ferry BOJ × 2 / Smuuti Skin UK / Chloe Marie Devlin / Najma🎋 / KIBODI STORE / Olaide Arike Ganiyu / Sharon 💋 / MASUK LIMITED full BOJ review / Hannah Wilkie / Aimée Isabella + 1 from WebSearch: Mediheal Boots launch chain corroboration). Exceeds requirement by 3×.
- **Drop rule applied**: #gurwm, humor, before-after, Cindy Lee, ZhilaBeauty, Amy Burnside Mixsoon all FADED (5 consecutive days absent — archived from active tracking). BIOHEAL BOH paid-wave downgraded from CARRY-PENDING to DECLINING (only 1 maintenance post in 7 days, no new creator activations).
- **Confidence**: HIGH on micro-organic ER ceiling (5 NEW examples 5-16% ER on <100k-follower creators); HIGH on Dr.Melaxin device-tier pivot (CACTOX MEWING BAND rank-1 promoted + spicule-lip +1184% Day-4); HIGH on BOJ Apricot Blossom Peeling Gel SKU-launch wave (Chloe Ferry × 2 with +67-88% 5-day deltas); MEDIUM on KIBODI STORE owner-POV sub-pattern (single example, n=1); MEDIUM on Yepoda + Narae UK brand-entry signals (single-creator activations); LOW on BIOHEAL BOH continued paid-wave (only 1 hit this week, downgrade-watch active).
- **Tomorrow's run (2026-06-11)**: (a) re-execute biodance brand-search slot to confirm/extend the BOJ Apricot Blossom Peeling Gel wave thesis and the medicube PDRN Capsule Cream emergent wave; (b) **add Dr.Melaxin brand-search slot** (replacing centellian24 — Centellian24 surface is mature, no new dynamics for 3 days) to track the device-tier pivot creator-side; (c) WebSearch for "@kibodistore TikTok" follower growth + any other UK indie K-skincare boutique TikTok channels (KIBODI STORE owner-POV pattern needs n≥2 to confirm); (d) WebSearch for "Yepoda UK creator partnerships" and "Narae UK PR list" to assess if these are organic creator picks or undisclosed-paid placements.

---

— End of Day 5 viral-video-parse —
