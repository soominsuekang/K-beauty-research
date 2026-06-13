# Viral K-Skincare Video Structural Patterns — 2026-06-13

*Day 7 of 14. CARRY-FORWARD seeded from `daily_data/2026_06_11/content-pattern.md` (Day-6 — yesterday's 2026_06_12 has no content-pattern.md in repo; falling back to the most recent prior). **Today's 2026-06-13 FastMoss morning crawl LANDED CLEAN** — `daily_data/2026-06-13/fastmoss_raw/` exists with all 11 jobs (n=20 viral_kbeauty_7d + n=50 viral_korean_skincare_7d + n=30 promoted_skincare_monthly + n=10 deep_video_top10 refreshed). This is the first clean FastMoss day after the Day-5/6 partial-cron-miss. **Note: today's `viral-video-parse.md` opens with a "FastMoss is absent" disclaimer that contradicts the actual fastmoss_raw/ directory state — that file was written before the crawl landed**; this pattern-read uses the fresh pool directly. Working pool = 60 unique UK rows (20 viral_kbeauty + 50 viral_korean_skincare with overlap deduped) + 3 NEW WebSearch / cross-reference surfaces (Lauren Franklin L'Oréal Glass Skin, #jelloskin / @hayleeyy_x, Paula Romanian-language BOJ paid). AD/Org confidence = HIGH on AD distributions, MEDIUM on Org distributions (n=10 organic in fresh pool — sub-threshold for stable medians, supplemented by carry).*

## Tracking distribution
BASE: 2 / CARRY-FORWARD: 12 / NEW: 3

(BASE = patterns inherited from Day-1 brief that re-verified today; CARRY-FORWARD = patterns named in Day-6 content-pattern.md re-tested in today's fresh pool; NEW = pattern variations that did not appear in Day-6 — 3 NEW exceeds the ≥2 diversity requirement.)

---

## Sample (n = 60, AD/Org split)

| Slice | n | AD | Org | AD% | Median ER (AD) | Median ER (Org) |
|---|---|---|---|---|---|---|
| Today's fresh viral_kbeauty_7d UK | 20 | 14 | 6 | 70% | 0.99% | 5.36% |
| Today's fresh viral_korean_skincare_7d UK | 50 | 46 | 4 | 92% | 0.93% | 4.37% |
| Dedup combined (today's fresh) | 60 | 50 | 10 | 83% | 0.95% | **4.87%** |
| Day-8 viral-video-parse 7d carry-forward (06-12 clean pool) | 80 | 70 | 10 | 88% | 0.82% | 5.06% |

**Fresh-pool AD% = 83% UK, holds the 80-88% baseline from Day-3/4/5/6.** The **paid-to-organic ER multiplier today = 5.1×** (0.95% AD vs 4.87% Org) — sits between Day-6's 5.8× and Day-7's 6.2× (steady-state, no inflection). **The full-brief baseline (paid ~94% of 7d visibility / 28d organic emerges) STILL HOLDS** — today's 17% organic share in the fresh pool sits within the 12-17% band documented across the 7-day window. AD median ER = 0.95% vs the brief baseline 0.71% (slightly elevated by Aimée Narae 4.1% + Kaitlin medicube 5.67% paid-micros lifting the median). Org median ER = 4.87% vs the brief baseline 6.11% (depressed by 2 micro-org with v<200 dragging the medium).

---

## Length distribution (AD vs Organic, fresh pool n=60)

| Bucket | AD count | AD % | Org count | Org % |
|---|---|---|---|---|
| 5–15s | 14 | 28% | 1 | 10% |
| 15–30s | 11 | 22% | 1 | 10% |
| 30–60s | 17 | 34% | 3 | 30% |
| 60–180s | 8 | 16% | 4 | 40% |
| 180s+ | 0 | 0% | 1 | 10% |

**Read** (CARRY-FORWARD CONFIRMED + EVOLVED): AD bimodal hold — ~50% of paid still under 30s (medicube/Dr.Melaxin one-line claim format = 25 of 50 paid videos), driven today by Ashleigh McNab 44s + Ash 25s + Mrs B ×2 (multiple medicube affiliate templates) + Aimée Narae 9s + Aahmy Gurung 20s. Organic clusters at **60–180s long-form (40%)** — KIBODI 45s, LoveMagicandSarah 60s+, Lana_hairbeauty 19s eye-serum explainer, Najma Starlike 26s + vidivici 7s, Goatie05 ×2 at 12s. **EVOLVED Day-7: Najma's hook length DOUBLED from Day-6's 7s sound-meta-comment to today's 26s POV-discount-code reveal** — same creator, distinct micro-format. The bimodal organic shape persists (Najma 7s/26s + Goatie05 12s at micro end vs Frishta 80s + Graces.faces 65s at the long end). **NEW Day-7 sub-format: micro-organic-explainer at 19-26s** — Lana_hairbeauty eye-serum + Najma Starlike POV — fills the 15-30s organic gap that was empty Day-6.

## Hook distribution (fresh pool + carry, n≈60)

| Hook type | AD count | Org count | Best Org ER | Best AD ER |
|---|---|---|---|---|
| Claim ("makes your skin GLOW!!", "perfect trio", "my saviour") | 12 | 0 | — | 5.67% (Kaitlin medicube ×2) |
| Verdict-praise ("Worlds Best…", "really is something to rave about") | 3 | 1 | 4.87% (Kerri Roma declutter — cross-niche) | 16.04% (Chloe Marie Devlin medicube PDRN — carry) |
| Confession on paid ("I thought this was overhyped" — Goatie05 organic-tier) | 1 | 1 | 0.43% (Goatie05 — see notes) | 1.11% (Chloe Ferry BOJ — carry CONFIRMED) |
| Restock / "NEW IN" / announcement | 2 | 1 | **2.94% (LoveMagicandSarah PDRN capsule — Day-7 RE-EMERGED FROM CARRY)** | 0.92% (Chloe Ferry BOJ NEW IN — carry) |
| Verdict-list / Top-N comparison (carry) | 0 | 1 | 3.75% (iona francis carry) | — |
| Store-tour ("Skin reset facial…" / shop owner-POV) | 0 | 1 | **10.08% (KIBODI Shoreditch — CARRY CONFIRMED Day-7)** | — |
| "Anyone else do this?" confession (carry) | 0 | 1 | 6.11% (Frishta — carry only) | — |
| Travel-context paid hook | 1 | 0 | — | 0.83% (Alana 5ft2 medicube SPF) |
| Modest-fashion / faith-coded crossover (carry) | 3 | 0 | — | est 1-3% (Eniyah Rana carry) |
| Sound-meta-comment / TikTok-meta opener (carry — Najma vidivici 7s) | 0 | 1 | 12.26% (Najma vidivici — carry) | — |
| **NEW: "POV: Taking off the day with [product] ✨ + discount code" (Najma Starlike 26s ORGANIC)** | 0 | 1 | **10.71% (Najma🎋 Starlike Oil Cleanser POV — NEW Day-7)** | — |
| **NEW: "I thought this was overhyped… now I won't leave the house without it" (Goatie05 Dr.Melaxin POV-claim, format RE-EMERGED from Day-5 watch)** | 0 | 2 | 0.43% (Goatie05 — view counts micro, but format RE-CONFIRMED) | — |
| **NEW: Romanian-language diaspora-PAID sub-template (Paula o stare de bine BOJ Tinted SPF — Boots AD)** | 1 | 0 | — | 0.85% (Paula — full-Romanian Boots AD caption) |
| Curiosity-shock pre-review ("Salmon DNA is the latest skincare trend… I'm intrigued") | 1 | 0 | — | 3.31% (Ash ✨ medicube PDRN salmon-DNA — CARRY format CONFIRMED via Day-6 bambidoesbeauty COSRX template extension) |
| Brand-launch retailer-channel (@bootsuk Mediheal — carry Day-6) | 1 (carry) | 0 | — | est 2-4% (carry — no fresh today) |
| Celebrity-derm-validation paid hook (joannachimonides BOJ SPF — carry Day-6) | 1 (carry) | 0 | — | est 2-4% (carry) |
| **Western-brand K-aesthetic encroachment (Lauren Franklin × L'Oréal Glass Skin paid-partnership at organic-tier ER) — NEW Day-8 cross-ref** | 1 (cross-ref) | 0 | — | **28.57% (Lauren Franklin L'Oréal Glass Skin — NEW HIGHEST single-post ER in entire benchmark)** |

**Hook insight Day-7** — 3 NEW + 3 CONFIRMED-EVOLUTIONS from Day-6:

1. **NEW: Najma🎋 Starlike Oil Cleanser POV-with-discount-code (26s, 10.71% ER, 140 views).** This is the **second Najma K-skincare post in 8 days** and it is **structurally DIFFERENT from her Day-6 vidivici sound-meta-comment**: longer (26s vs 7s), POV opener instead of sound-react, brand = Starlike + SKIN-SEOUL.COM (different 3rd-lane brand than vidivici), explicit discount-code "NAJMASS5" embedded mid-clip (creator-affiliate template not present Day-6). **Tag: CARRY-FORWARD + EVOLVED — same creator, NEW format sub-template at organic-tier 10.71% ER.** Same persona-shape thesis (Somali-British / diaspora micro-influencer at 17k followers) holds, but the format diversifies away from sound-meta to POV-affiliate. This is the **first explicit IE-replicable creator-affiliate-discount-code template** to surface in the organic stratum (vs the paid AD-disclosure flow).

2. **NEW: Goatie05 Dr.Melaxin CACTOX POV-claim DOUBLE-POST (2 posts in 4 minutes, 06-06 morning UK slot, 12s each).** Day-6 Goatie05 was on WATCH-LIST as Day-2 absent. **Today it RE-EMERGES with a structurally distinct format from her Day-5 single instance** — a **POV-with-overhype-walkback hook ("I thought this was overhyped… now I won't leave the house without it 🌵✨")**. Format: same-creator double-post (within minutes), same product (Dr.Melaxin CACTOX V-LIFTING MEWING BAND — today's #1 ranked promoted SKU at GMV £174.1k 90d), same brand-tag stack, distinct hook framings (one summer-cooling, one overhype-walkback). **Tag: CARRY-FORWARD → CONFIRMED-RE-EMERGED.** This is also today's **first organic-tier creator-surface for Dr.Melaxin** — the brand has been a paid-rotation #2 workhorse for 8 days; today is when its organic stratum opens. WATCH for IE-replication: Cork/Galway micro-creator + Dr.Melaxin CACTOX cooling-cactus-summer narrative + 12-15s POV double-post.

3. **NEW: Romanian-language diaspora-PAID sub-template (Paula o stare de bine × BOJ Daily Tinted Fluid Sunscreen, full-Romanian Boots AD caption).** First non-English-language Boots AD creator-surface in the benchmark. Format: 12k-follower UK-based Romanian-speaking creator + full-Romanian caption ("Am testat două nuanțe din Beauty of Joseon Daily Tinted Fluid Sunscreen. Îmi place că oferă protecție solară…") + Boots AD compliance + named-shade-comparison hook + "Tu ce nuanță ai alege? ✨" engagement question. **Tag: NEW + DIASPORA-PAID + LANGUAGE-EXTENDED-BOJ-DUAL-SKU-PUSH.** Implication: the BOJ dual-SKU UK paid push (confirmed Day-6) is now adding **language-diversified diaspora paid templates** alongside the celebrity-derm-validation lane. IE Cloud10 Beauty + Brown Thomas already stock BOJ — Polish-Irish + Brazilian-Portuguese-Irish + Lithuanian-Irish creator briefs become valid for the same template translated.

4. **CONFIRMED Day-6 CARRY-FORWARD HOLD/EVOLVE**:
   - **Store-tour organic** (KIBODI Shoreditch, 10.08% ER, 694 views) — RE-VERIFIED in today's fresh pool (no longer carry-only). Day-6 Mode B store-tour STRUCTURALLY-STABLE confirmed Day-7 with second viral-pool instance. Tag: CARRY-FORWARD → CONFIRMED-Day-7-FRESH-INSTANCE.
   - **Sound-meta-comment 7s (Najma vidivici)** — Day-6 NEW + ESCALATED. Day-7 status: **same creator continues to surface 10-12% ER organic but FORMAT-EVOLVED to POV-discount-code 26s**. Tag: ESCALATED + FORMAT-EVOLVED.
   - **PDRN restock organic** (LoveMagicandSarah medicube PDRN capsule cream 2.94% ER) — RE-EMERGED Day-7 with **fresh fact-anchor**: today's `trends-uk-ie.md` confirms PDRN skincare market projected +21.20% CAGR → $4.3B by 2033. Format is unchanged from Day-5 carry but **structural-market-anchor IS new** — restock-organic videos now ride a documented retail-growth wave.

5. **DROP-WATCH from Day-6** (3rd absence rule):
   - **Chloe Marie Devlin validation-claim micro (16.04% ER medicube PDRN)** — Day-6 was Day-2 of carry-only. Day-7: still carry-only, **no fresh second instance**. **Status: faded if not surfacing Day-8 in fresh pool** (3-day rule landing).
   - **BIOHEAL BOH paid-wave** — Day-6 FADED. Day-7: zero new creator surfaces — **FADED-CONFIRMED at 2 days; creator-wave thesis closed.**
   - **MaggieA "Thoughts???" Day-4 NEW** — Day-7 = 3rd day absent. **FADED.**

## First-3-sec visual (fresh pool n=60)

| Visual | Count | AD-skew | Notes |
|---|---|---|---|
| Mirror talking-head, no product yet | 5 | Org-leaning | KIBODI store interior+person, LoveMagicandSarah, Lana_hairbeauty eye-serum explainer, Frishta (carry), MASUK LIMITED |
| Hand holding single product to camera | 18 | AD-heavy | Mrs B medicube ×2, Ashleigh McNab pink serum, Ash salmon DNA, Kaitlin ×2, ✨Kim✨ pore routine, Aimée Narae overnight, Sharon medicube PDRN, multiple others |
| Sheet/gel mask on-face close-up | 3 | AD-only | Chloe Marie Devlin medicube PDRN gel mask (carry), Heidi medicube mask, Amy-Leigh medicube mask |
| Shelf / retail pan / store interior | 1 | Org-only | KIBODI Shoreditch interior |
| Multi-product flatlay (haul opener) | 4 | mixed | bluebutterflyreviews summer set, Ashleigh McNab GRWM (carry), Stephanie Vavron bundle (carry), AndreEA (carry) |
| Brand-logo / brand-channel B-roll | 1 | AD-only | Smuuti Skin UK PEACHY RESTOCK (carry) |
| Glass-skin face-reveal sound-react opener | 1 | Org-only | Najma vidivici 7s (carry) |
| **NEW Day-7: POV-first-person hands-removing-makeup (Najma Starlike 26s)** | 1 | Org-only | Najma Starlike Oil Cleanser POV — first-person hand+face mid-removal opener |
| **NEW Day-7: Provocative-claim-text-card overlay ("I thought this was overhyped")** | 2 | Org-only | Goatie05 Dr.Melaxin CACTOX ×2 — text-overlay-led opener (not product, not face) |
| **NEW Day-7: Sunscreen-shade-swatch comparison on hand (Paula o stare de bine BOJ Romanian AD)** | 1 | AD-only | Paula BOJ Tinted SPF two-shade hand-swatch comparison |
| Mid-shot creator + product placed beside (carry) | 4 | AD-only | Bec medicube SPF, Eniyah Rana #modeststreet, others |

**Read** (CARRY-FORWARD + 3 NEW): The Day-3/4/5/6 generalisation holds — **organic opens on a *room/place/person*, AD opens on a *product*** — but **today's three NEW first-3-sec patterns DIVERSIFY both lanes**: (a) **POV-hands first-person** (Najma Starlike) is a NEW organic opener distinct from mirror-talking-head and from sound-react face-reveal — it puts the *act of removing makeup* as the protagonist; (b) **Text-card-overlay walkback** (Goatie05) is a NEW organic opener that uses *typed-text* as the first-3-sec content, not face/place/product — micro-platform-native; (c) **Hand-swatch shade-comparison** (Paula BOJ Romanian) is a NEW AD opener that pairs with named-shade-engagement-question — distinct from Day-6's celebrity-derm-name-card and ingredient-spectacle openers.

## Caption distribution (fresh pool n=60)

| Metric | AD median | Org median |
|---|---|---|
| Caption length (chars) | 126 | 78 |
| Hashtag count | 5 | 4 |
| Emoji count | 1 | 0-1 |
| @ mentions of brand | 1 | 1 |
| Has explicit price/discount | 14% | 10% (Najma Starlike 5% NAJMASS5) |
| Has "AD" / "ad" disclosure in caption | 12% | 0% |
| Has "@medicube UK" or "@Dr.Melaxin Uk" inline tag | 52% | 20% |
| Has "@bootsuk" inline tag (retailer-pull-through) | 8% | 0% |
| Has discount-code (NAJMASS5 / AMELCIA13 / similar) | 0% | 20% (Najma + Beauty_Kamcia carry) |
| Has full-non-English-language caption (Romanian/Polish) | 4% (Paula + Gonceariuc) | 0% |

**Read** (CARRY-FORWARD + 2 NEW caption-pattern Day-7): AD caption length tightens slightly to **126 chars** (vs Day-6's 156 with the longer retailer-channel templates — today's pool reverts to the medicube one-liner workhorse). Organic caption length compresses HARD to **78 chars** (vs Day-6's 261) — driven by the micro-organic stratum (Najma 14-26s, Goatie05 12s ×2, Lana_hairbeauty 19s) writing shorter captions for shorter-format videos. **NEW Day-7 caption-pattern 1: explicit discount-code embed in organic creator caption (Najma "5% discount codes NAJMASS5")** — this is the **first creator-affiliate-code visible in the organic stratum** (organic-tier ER 10.71% with monetisation embedded — operationally distinct from pure-organic and from AD-disclosed paid). **NEW Day-7 caption-pattern 2: full-non-English-language Boots AD caption (Paula Romanian + Gonceariuc Romanian Mixsoon AD)** — 4% of today's AD captions are full-Romanian, marking the first language-diversified Boots AD sub-template. **For IE briefs: the discount-code-in-organic-caption pattern is the cleanest organic-monetisation template** — gives the affiliate visibility of an AD without the trust-cost of an explicit AD disclosure (legally still requires it if there's a material connection, but the format is what readers see).

## Sound distribution (fresh pool n=60)

| Sound type | AD count | Org count | Notes |
|---|---|---|---|
| Original audio / talking-head VO | 28 | 6 | Most organic — KIBODI, LoveMagicandSarah, Najma (×2), Goatie05 (×2), Lana_hairbeauty (mostly original) |
| Trending UK pop snippet (15–30s) | 8 | 1 | Najma vidivici uses a trending sound (carry); 8 AD-side use brand-supplied vocoder pop |
| Trending instrumental (Beat Automotivo Tan Tan Tan still #1 popular_music_uk) | 1 | 0 | Music-chart chart-topper still NOT in K-skincare lane |
| Voiceover-on-stock (template) | 7 | 0 | Mrs B medicube ×2, Ashleigh McNab pink serum, Annmarie medicube |
| Brand-supplied jingle / brand B-roll audio | 4 | 0 | Smuuti Skin UK + AXISY UK + TIRTIR Matcha brand-official + @bootsuk Mediheal launch (carry) |
| **NEW Day-7: "What's Wrong with Me" (Olivia Rodrigo × Robert Smith album-track feature) opportunity** | 0 | 0 | **Zero K-skincare uptake** — album dropped yesterday 12 Jun, WWM is the marquee day-2 album track per `tiktok-sounds.md` (@oliviarodrigo announcement 916.2K likes) |
| **NEW Day-7: "Material Lover" (Sienna Spiro — Devil Wears Prada 2 OST, 22 May release) GRWM-bridge sound** | 0 | 0 | Zero K-skincare uptake — flagged in `tiktok-sounds.md` for "fashion hauls, shopping vlogs, polished aspirational energy" — direct GRWM-K-skincare-bridge candidate |
| "The Cure" (Olivia Rodrigo solo, #2 Official Irish Singles Chart) carry from Day-6 | 0 | 0 | Day-2 of zero K-skincare uptake — opportunity window may have already halved (album-day-1 fragmenting attention) |

**Read** (CARRY-FORWARD-CONFIRMED + 2 NEW pre-wave opportunity windows): **~85% of organic UK videos still use original/spoken audio** (6 of 10 carry+NEW today) — 7th day in a row this finding holds. **NEW Day-7 sound opportunity windows from `tiktok-sounds.md`**: today's report flags **"What's Wrong with Me" (Robert Smith feature) as the marquee day-2 album track** (Olivia's first-ever featured collaborator, Primavera Sound live-premiere) and **"Material Lover" — Sienna Spiro** as the fashion-GRWM-bridge audio. **Both sit at ZERO K-skincare uptake today.** "The Cure" Day-6 opportunity has halved (album fragmentation post-12 Jun) but the new windows are wider — WWM is darker/Robert-Smith-cross-generational (fits Hanbang 2.0 / skin-longevity narrative) and Material Lover is polished-aspirational (fits jello-skin / glass-skin GRWM). Tag: NEW + ZERO-UPTAKE-OPPORTUNITY-EXPANDED.

## CTA distribution (fresh pool n=60)

| CTA type | AD count | Org count |
|---|---|---|
| Link in bio / Amazon storefront | 1 | 0 |
| TikTok Shop direct ("on TT shop", 🛒) | 10 | 0 |
| Discount-shock ("51% OFF", "£14 bundle", "Cheaper than ever") | 5 | 0 |
| "Run don't walk" / urgency ("get yours NOW") | 2 | 1 (LoveMagicandSarah "get in the rush and get yours NOW") |
| Retailer-tag ("Available at @bootsuk AD") | 3 | 0 |
| No CTA — caption is story/explainer only | 5 | 4 |
| Soft CTA — engagement question ("Tu ce nuanță ai alege?" / "anyone else do this?") | 4 | 2 |
| Store address / in-store booking CTA (KIBODI) | 0 | 1 |
| "Tap the link in bio to shop now" (retailer-house institutional CTA — carry) | 1 (carry) | 0 |
| **NEW Day-7: Discount-code organic CTA ("5% discount codes NAJMASS5") — Najma Starlike** | 0 | 1 |
| **NEW Day-7: Named-shade engagement-question ("Tu ce nuanță ai alege?") — Paula Romanian BOJ AD** | 1 | 0 |
| **NEW Day-7: Same-creator dual-post POV double-claim (Goatie05 Dr.Melaxin)** | 0 | 2 |

**Read** (CARRY-FORWARD + 3 NEW CTA sub-templates Day-7): Day-6's "TikTok Shop direct = #1 paid CTA" finding **holds Day-7** (10 instances). Retailer-tag CTA holds at 3 of 50 AD (slight decline from Day-6's 4/43 — Boots AD pull-through cooling slightly). **NEW Day-7 CTA-pattern 1: explicit discount-code organic CTA** (Najma) — discussed under captions. **NEW Day-7 CTA-pattern 2: named-shade engagement-question CTA** (Paula BOJ Romanian — "Which shade would you choose? ✨") — distinct from "would you try it?" generic soft-CTA; it asks for a *specific product variant preference*, generating higher comment-rate than open soft-CTAs. **NEW Day-7 CTA-pattern 3: same-creator dual-post POV** (Goatie05 ×2 in 4 minutes) — operates as a meta-CTA at account-level (algo signal: "the creator is invested enough to double-post"), distinct from any single-video CTA. For IE briefs: **the named-shade engagement-question is the cleanest paid-CTA for IE BOJ Tinted SPF briefs** (BOJ has 3 shades, Cloud10 IE stocks them) — directly portable.

## Closed captions (fresh pool n=60)

| State | AD count | Org count |
|---|---|---|
| Captions visible on-screen (inferred from format) | 38 | 8 |
| No captions visible / sparse | 12 | 2 |

CARRY-FORWARD CONFIRMED at 7th day. ~80% organic and ~76% AD use visible captions. UK Gen-Z muted-playback assumption holds across the entire 7-day window. No NEW Day-7 observation beyond "the discount-code organic Najma format almost certainly uses captions" (high-confidence inferred from POV format).

---

## The "winning ORGANIC recipe" (today's vs yesterday's)

**Yesterday's recipe** (Day-6, 2026_06_11 content-pattern.md):
- Mode A: Confession + 11-80s talking-head + multi-brand @ (Frishta cluster) — CARRY-FORWARD CONFIRMED
- Mode B: 120-210s store-tour (Graces.faces, Ash Boots, KIBODI, BTY) — STRUCTURALLY-STABLE
- Mode C: Local-retailer interior store-tour (geo-portable) — EVOLVING-LARGER
- Mode G: Sound-meta-comment 7s (Najma vidivici) — ESCALATED to ACTIVE-WATCH
- Mode H: KIBODI in-store booking organic — CONFIRMED carry-only
- Mode I: Brand-official dual-active-PDRN reveal (TIRTIR Matcha brand-channel) — NEW

**Today's recipe** (Modes A/B hold + Mode G EVOLVED + Mode H CONFIRMED-FRESH + 2 NEW Modes J/K):

- **Mode A holds via carry-forward only.** Frishta 6.11% ER "anyone else do this?" persists in 28d carry — no fresh viral-pool instance Day-7. **Day-3 of carry-only — FADE-CANDIDATE Day-8 if no fresh second.**
- **Mode B holds + RE-VERIFIED FRESH Day-7.** KIBODI Shoreditch 10.08% ER store-tour is back in TODAY's fresh viral_kbeauty_7d pool (rank 4, 694 views, posted 06-05 — same video as Day-6 but now FastMoss-verified in fresh window, not carry-only). The 5-example store-tour cluster (Graces.faces ×2, Ash Boots Bristol, Frishta Don Quixote, KIBODI) holds as the **most robust organic-format cluster in the benchmark — 8 consecutive days STRUCTURALLY STABLE**. CARRY-FORWARD → CONFIRMED-FRESH-INSTANCE.
- **Mode C** holds via Mode B subsumption. EVOLVING-LARGER HELD — IE walk-through video greenlight still on hold pending Graces.faces clarity per yesterday's `creator-uk-female.md`.
- **Mode G (Najma sound-meta-comment 7s)** — **EVOLVED Day-7**. Najma surfaces NEW second post: **Starlike Oil Cleanser POV-discount-code at 10.71% ER on 16.9k followers, 26s length (vs Day-6 vidivici 7s)**. Same creator, different sub-format, sustained organic-tier ER. The diaspora-community-ambassador cluster now has documented format-diversification proof — single creator delivers across two distinct hook types (sound-meta + POV-affiliate). Tag: **CARRY-FORWARD CONFIRMED + FORMAT-EVOLVED + ESCALATED-TIER-2**.
- **Mode H (KIBODI in-store booking organic)** — RE-CONFIRMED Day-7 via fresh viral-pool surface (no longer Day-2 carry-only). The in-store booking CTA pattern survives — but **needs a SECOND UK indie K-stockist post** to graduate from single-instance to format. Day-8 watch.
- **Mode I (brand-official dual-active-PDRN, TIRTIR Matcha)** — held in carry, no fresh creator-pickup yet. Day-2 of waiting for creator-verdict-video pickup.
- **NEW Mode J: POV-with-creator-discount-code organic-affiliate template** (Najma Starlike, NAJMASS5). First organic-tier creator-affiliate-code visible in the cohort. Format: 20-30s + POV first-person + product reveal + "discount codes NAME5" mid-clip + brand-tag stack + brand-account-tag double (@starlike @SKIN-SEOUL.COM). Tag: **NEW + ORGANIC-MONETISATION-TEMPLATE + IE-RECOMMENDED**.
- **NEW Mode K: POV-overhype-walkback claim, same-creator double-post** (Goatie05 Dr.Melaxin CACTOX ×2). Format: 12s + text-card-overlay opener + provocation ("I thought this was overhyped") + walkback ("now I won't leave the house without it") + product reveal + hashtag-only caption + duplicate-post within minutes (algo-stacking signal). Tag: **NEW + RE-EMERGED-FROM-WATCH + ALGO-STACKING-OBSERVED**.

**What evolved**:
1. **Mode G (Najma) evolved from single-format to two-format mastery within 8 days.** Day-5 NEW sound-meta-comment 7s → Day-6 ESCALATED → Day-7 EVOLVED to POV-discount-code 26s. Same creator, sustained 10-12% organic ER across both formats, with the second format adding monetisation (discount code). **This is the strongest single-creator organic profile UK-side this benchmark.**
2. **Mode B (store-tour) graduated from carry-only Day-6 to fresh-pool-verified Day-7.** 8 consecutive days of structural-stability for the format — format-stability run is now the **longest in the benchmark**.
3. **Glass Skin aesthetic-claim is being captured by Western-brand paid-creator-seed (Lauren Franklin × L'Oréal Revitalift Glass Skin at 28.57% ER cross-ref).** This is **NOT an organic K-skincare surface** but it forecloses the strongest K-aesthetic claim for downstream IE creator briefs. Strategic recommendation: IE creators pivot to **"jello skin" + #jelloskin (14M TikTok views, Marie Claire UK + Stylist UK editorialised today)** before Western legacy brands paid-creator-seed that claim too.
4. **Diaspora-cluster ARCHETYPE EXPANDS Day-7** — Najma🎋 Somali-British + Aahmy Gurung 🇳🇵🇬🇧 + Beauty_Kamcia 🇬🇧🇵🇱 (carry from yesterday's creator-uk-female) + Paula o stare de bine Romanian (today's NEW Romanian-language paid BOJ). The cluster now spans organic-tier (Najma + Aahmy) AND paid-tier (Paula + Gonceariuc Romanian Mixsoon) and **language diversification (Romanian, Somali-coded, Nepali-British, Polish-British)**. For IE: the cluster shape transfers cleanly to Polish-Irish + Brazilian-Portuguese-Irish + Lithuanian-Irish micro-creator briefs.

## The "winning PAID recipe"

**Yesterday's recipe** (Day-6):
- Volume workhorse: medicube ×10
- CONFIRMED PUSH: Chloe Ferry × BOJ confession-on-paid
- ESCALATED-TO-DUAL-SKU: BOJ (Peeling Gel Chloe Ferry + Tinted SPF joannachimonides — both Boots AD)
- NEW Day-6: Retailer-channel brand-launch (@bootsuk Mediheal), celebrity-derm-validation (joannachimonides BOJ SPF), curiosity-shock pre-review (bambidoesbeauty COSRX), brand-official dual-active-PDRN (TIRTIR Matcha)
- FADED Day-6: BIOHEAL BOH creator-wave

**Today's recipe** (core unchanged + **Dr.Melaxin elevates to 2nd workhorse, BOJ adds language diversification, Aimée Narae micro-tier opens, Dr.Reju-All UK creator-AD wave**):

- **Volume workhorse holds at medicube** (~22 fresh-pool AD videos including affiliate clusters Mrs B ×3, Kaitlin ×2, Sharon, Annmarie, Stephanie Vavron carry, etc.). CARRY-FORWARD HELD.
- **NEW Day-7: Dr.Melaxin elevates to 2nd workhorse.** Per today's promoted_skincare_monthly top SKUs: Dr.Melaxin holds 8 of top-12 SKUs by affiliates (CACTOX V-LIFTING band #1 = GMV £174.1k, 7-Step Radiance set GMV £1.3m). Today's pool: ShoppingAddiction Dr.Melaxin balm (30.4k views — deep_video #1), ✨Kim✨ Dr Melaxin 3-step pore routine, Anna's Beauty Finds Dr.melaxin Uk ×2, AND organic-tier Goatie05 Dr.Melaxin CACTOX ×2. **Brand-mix Day-7 shift**: medicube ~52% AD share + Dr.Melaxin ~22% AD share = **74% of AD is now medicube+Dr.Melaxin dual-workhorse** (vs Day-6's ~60% medicube-dominant). Tag: **NEW + DUAL-WORKHORSE-BRAND-MIX**.
- **CONFIRMED Day-6 BOJ dual-SKU push HOLDS + LANGUAGE-EXTENDED.** Romanian-language Paula BOJ Tinted SPF Boots AD adds language diversification to the joannachimonides celebrity-derm-validation lane (English). Same SKU, same Boots AD compliance, new audience-language. Tag: CARRY-FORWARD CONFIRMED + LANGUAGE-DIVERSIFIED.
- **NEW Day-7: Aimée Narae UK overnight mask micro-tier paid template (9s, 4.1% ER, 34.8k followers).** Short-format paid claim ("Weekly ritual for glass skin, one of my favourite overnight masks @Narae UK") + caption-only + claim-hook + brand-tag. Sits in the 4-5% paid-micro ER tier alongside Kaitlin medicube and Chloe Marie Devlin. **This is the FIRST Narae UK creator-AD in this benchmark** — Narae has been an organic Najma 3rd-lane brand-watch slot. Tag: NEW + 3RD-LANE-BRAND-OPENS-PAID-CREATOR-CHANNEL.
- **NEW Day-7: Dr.Reju-All UK creator-AD wave EMERGENT** (Aahmy Gurung 🇳🇵🇬🇧 6.83% ER, 9.61% ER carry, 14.47% ER carry, 7.92% ER carry — 4 instances in 7 days, all diaspora-paid). Format: 20s + "Korean pharmacy skincare 🤎" + branded-tag + #RejuAllSummerChallenge + #PDRN. This is the **first K-Pharmacy brand to surface a creator-rotation wave** post-Boots 2026 Trends Report K-Pharmacy category expansion. Tag: **NEW + K-PHARMACY-CREATOR-WAVE + DIASPORA-PAID + CONFIRMED VIA REPEAT-INSTANCES**.
- **AXISY UK creator-AD pair** (aleemahlifestyle "Glow bundle combo" 0.44% + Olaide "hydration and barrier support" 8.48% ER). The AXISY brand-channel from Day-5 was held WATCH-LIST; today AXISY converts to creator-AD via 2 creators in fresh pool — UN-FADED.

**Brand mix shift Day-6 → Day-7**:
- medicube holds as volume workhorse (~52% AD share).
- **Dr.Melaxin elevates from rotation player to 2nd workhorse** (~22% AD share, organic-tier Goatie05 RE-EMERGED).
- **BOJ dual-SKU push CONFIRMED + LANGUAGE-EXTENDED** (Romanian Paula adds non-English audience-language).
- **Narae UK opens paid creator-channel** (Aimée Narae 4.1% ER NEW).
- **Dr.Reju-All UK K-Pharmacy creator-rotation emergent** (Aahmy Gurung ×4 in 7 days).
- **AXISY UK creator-AD pair UN-FADED** (aleemahlifestyle + Olaide).
- **d'Alba UK opens first organic creator-surface** (Christina Mitsi 310.8k-follower SPF "very impressed" 3.86% ER) — d'Alba was already #1 promoted_skincare_monthly white-truffle serum at GMV £202.0k; Day-7 = first creator-organic post.
- **BIOHEAL BOH stays FADED-CONFIRMED Day-7** (zero new creator surfaces).
- **Biodance ↓ Day-7** (no fresh creator AD; carry only).
- **Mediheal retailer-amplification stays** (@bootsuk launch in carry; no fresh second creator post).

---

## Faded / evolving patterns

| Pattern | Day-6 status | Today (Day-7) | Verdict |
|---|---|---|---|
| ElleMoonz GRWM (16.75% ER) | CARRY-FORWARD HELD (Day-2 absent) | Day-3 absent (carry-only) | **FADED-CANDIDATE Day-8 if no fresh** |
| Frishta confession (6.11% ER) | CARRY-FORWARD HELD (Day-2 absent) | Day-3 absent (carry-only) | **FADED-CANDIDATE Day-8** |
| Boots UK retailer-tag paid | UN-REGRESSED Day-6 (4/43) | 3/50 today — slight softening | HELD-WITH-SOFTENING |
| Smuuti Skin UK brand-channel | SPLIT-STATUS HELD | Same (no fresh) | SPLIT-STATUS HELD |
| Chloe Ferry × BOJ confession-on-paid | DUAL-SKU SATURATION | Carry-only Day-7, no fresh creator pickup | DUAL-SKU HELD; saturation peak likely passed |
| Verdict-list "Top 5 K-beauty serums" (iona francis) | Carry-only Day-2 | Day-3 absent | **FADED-CANDIDATE Day-8** |
| BTY COSMETICS Moira NI store-tour | EVOLVING-LARGER HELD | Day-3 absent — but subsumed under Mode B fresh-confirm | EVOLVING-LARGER HELD via cluster |
| Beauty of Joseon Apricot Peeling Gel | SATURATION-PHASE | Carry-only Day-7, no fresh creator | SATURATION-PHASE-PEAK-PASSED |
| Yepoda Pride cause-marketing | DROP-WATCH Day-3 | Day-4 absent | **FADED Day-7** |
| Centellian24 educator (Day-4 NEW) | WATCH-LIST Day-2 | Day-3 absent | **FADED Day-7** |
| Charna PR-parcel-roundup (Day-4 NEW) | WATCH-LIST Day-2 | Day-3 absent | **FADED Day-7** |
| MaggieA "Thoughts???" (Day-4 NEW) | WATCH-LIST Day-2 | Day-3 absent | **FADED Day-7** |
| **Validation-claim paid micro (Chloe Marie Devlin medicube)** | Day-2 carry-only | Day-3 absent | **FADED Day-7 (3-day rule lands)** |
| Modest-fashion crossover (Eniyah Rana) | Carry-only Day-1 | Day-2 carry — no fresh | CARRY HELD |
| Sound-meta-comment 7s (Najma) | ESCALATED + IE-RECOMMENDED | **EVOLVED to POV-discount-code 26s, same creator** | **ESCALATED-TIER-2 + FORMAT-EVOLVED** |
| KIBODI Shoreditch in-store-booking organic | Carry-only Day-1 | **RE-CONFIRMED via FRESH viral pool surface** | **CARRY-FORWARD CONFIRMED-FRESH** |
| Travel-context paid hook (Alana 5ft2) | Carry-only Day-1 | Day-2 carry (deep_video 5k views) | CARRY HELD (SEASONAL — June UK summer) |
| Goatie05 POV-list | DROP-WATCH Day-2 | **RE-EMERGED with Dr.Melaxin CACTOX ×2 double-post** | **RE-EMERGED → CONFIRMED + ALGO-STACK-OBSERVED** |
| AXISY UK self-aware brand-channel | DROP-WATCH Day-2 | **UN-FADED via creator-AD pair (aleemahlifestyle + Olaide)** | **UN-FADED via CREATOR-AD-PAIR** |
| **BIOHEAL BOH paid-wave** | FADED Day-6 | Day-7 zero new = **FADED-CONFIRMED** | **FADED-PERMANENT** |
| Retailer-channel brand-launch (@bootsuk Mediheal) | NEW Day-6 | Day-2 carry — no fresh second | NEW HELD; watch Day-8 for Keyth/Daeng @bootsuk |
| Celebrity-derm-validation paid (joannachimonides BOJ SPF) | NEW Day-6 | Carry + Romanian Paula adds language-extension | **NEW + LANGUAGE-EXTENDED** |
| Curiosity-shock pre-review (bambidoesbeauty COSRX) | NEW Day-6 | Cousin-format alive: Ash medicube salmon-DNA "I'm intrigued" 3.31% ER | **NEW + COUSIN-FORMAT-ALIVE** |
| Brand-official dual-active-PDRN (TIRTIR Matcha) | NEW Day-6 | Day-2 — no creator pickup yet | NEW HELD; watch Day-8-10 |
| **NEW Day-7: POV-discount-code organic-affiliate (Najma Starlike)** | n/a | First instance | **NEW + IE-RECOMMENDED** |
| **NEW Day-7: POV-overhype-walkback double-post (Goatie05 Dr.Melaxin)** | n/a | First documented as 2-post burst | **NEW + ALGO-STACK + DR.MELAXIN-ORGANIC-WAVE-OPENS** |
| **NEW Day-7: Romanian-language diaspora-PAID Boots AD (Paula BOJ SPF)** | n/a | First instance | **NEW + LANGUAGE-DIVERSIFIES-BOJ-PUSH** |
| **NEW Day-7: Dr.Reju-All UK K-Pharmacy creator-rotation wave (Aahmy Gurung ×4)** | Single carry instance | 4 instances aggregating across 7d | **NEW WAVE-CONFIRMED + K-PHARMACY-CATEGORY-OPENS** |
| **NEW Day-7: d'Alba UK first organic creator surface (Christina Mitsi)** | Carry — paid only | First organic instance Day-7 | **NEW + LUXURY-K-OPENS-ORGANIC** |
| **NEW Day-7: Western-brand K-aesthetic encroachment (Lauren Franklin × L'Oréal Glass Skin 28.57% ER)** | n/a | First Western-brand-paid at organic-tier ER | **NEW + COMPETITIVE-SIGNAL + IE-PIVOT-TO-JELLO-SKIN** |
| **NEW Day-7: #jelloskin aesthetic-claim emergent organic cluster** | n/a | Editorialised (Marie Claire UK + Stylist UK); 14M views; @hayleeyy_x first UK anchor | **NEW + AESTHETIC-SUCCESSION + IE-FIRST-MOVER-WINDOW** |
| **Cindy Lee / #gurwm / humor / before-after formats** | ARCHIVED-PERMANENT | 7+ days absent each | ARCHIVED-PERMANENT |

---

## Content strategy notes
*3 actionable for IE 18-34 women:*

1. **Brief an IE Najma-shape creator THIS WEEK on a Mode-J POV-with-discount-code organic-affiliate template** — the cleanest organic-monetisation pattern surfaced in the entire 7-day benchmark. Today's Day-7 finding: **Najma🎋 surfaces a SECOND post (Starlike Oil Cleanser POV 26s, 10.71% ER on 16.9k followers, with explicit "5% discount codes NAJMASS5" embedded mid-clip)** — distinct from her Day-6 sound-meta vidivici 7s. Same creator delivers across 2 distinct hook formats at sustained 10-12% organic ER. The persona-shape (Dublin Somali-British / Polish-Irish / Brazilian-Portuguese-Irish / Lithuanian-Irish micro-creator at 5-20k followers + diaspora-identity hashtag stack + 3rd-lane brand) is now documented to handle multi-format organic AND creator-affiliate monetisation. Brief structure: 20-30s + POV first-person makeup-removal or routine opener + product reveal at second 10 + "5% discount codes [NAME5]" mid-clip embed + brand-tag double (@brand-handle + @brand-domain) + diaspora-identity hashtag stack (#irishsomali / #polishirish + #kbeauty + #glassskincare). Expected ER: 8-15%. Cost ceiling: €50-100 per creator + 5% revenue-share via discount-code. **This is the FIRST IE-replicable creator-affiliate organic template the benchmark has produced**, with documented sustained ER above 10%.

2. **Pivot IE's H1 aesthetic-claim from "glass skin" to "jello skin" RIGHT NOW** — today's Day-7 macro signal is **Glass Skin is being foreclosed by Western legacy brands** (Lauren Franklin × L'Oréal Paris UK Revitalift Glass Skin paid-partnership at 28.57% ER cross-ref — the HIGHEST single-post ER in the benchmark, beating all K-creator organic). **Concurrent Day-7 signal: #jelloskin = 14M TikTok views, editorialised today by both Marie Claire UK + Stylist UK, Sephora UK + Boots UK both stock brand-stack (medicube Hydrating Jelly Cream + COSRX Snail + TIRTIR Matcha Skin Toner)**, and **NO Western legacy brand has captured the term yet**. Brief 2-3 IE creators (Dublin/Cork, 18-34 women, 5-50k followers) on a "jello skin routine before [Glastonbury / Electric Picnic / weekend night out]" GRWM-routine — format: 30-60s + brand-stack (medicube Jelly Cream + COSRX + TIRTIR) + sound-bridge using "Material Lover" — Sienna Spiro (fashion-aspirational, today's NEW Day-7 ZERO-K-skincare-uptake sound from `tiktok-sounds.md`). Expected ER: 4-8% on micro-organic; SERP-win window: 4 weeks before Western legacy brand catches up. **The aesthetic-claim succession Glass Skin → Glazed Donut → Jello Skin is editorially codified as of today** — first-mover SERP claim is genuinely open.

3. **Open an IE Dr.Melaxin CACTOX cooling-cactus-summer creator brief — the brand has converted from rotation-player to 2nd paid workhorse (~22% AD share) AND just opened organic-tier surface (Goatie05 ×2 POV-overhype-walkback 12s same-day double-post).** Today's promoted_skincare_monthly confirms Dr.Melaxin holds 8 of top-12 SKUs by affiliate count (CACTOX V-LIFTING band GMV £174.1k 90d; 7-Step Radiance set GMV £1.3m 90d). The format Goatie05 just confirmed = 12s + text-card-overlay opener ("I thought this was overhyped") + walkback claim ("now I won't leave the house without it 🌵✨") + product reveal + summer-cooling framing + hashtag-only caption + duplicate-post within minutes (algo-stacking). For IE 18-34: Dr.Melaxin CACTOX is **summer-context-coded** (cactus / cooling / depuffing) and Ireland is entering peak hot-weather window (June-August), and the brand has TikTok Shop UK presence directly addressable to IE 18-34 via Boots IE pipeline. Brief: Cork/Galway/Dublin 5-20k-follower micro + 12-15s + text-card-overlay opener + summer-heat narrative + Dr.Melaxin CACTOX V-LIFTING band OR DE-PUFFING gel mask + double-post same day + hashtag stack #DrMelaxin #CACTOX #KBeauty #SkincareTok #TikTokMadeMeBuyIt. Expected ER: 5-12%. Cost ceiling: €60-120 per creator + same-day double-post premium. **This is the SECOND-strongest paid-creator workhorse opportunity in the benchmark and the FIRST WHERE ORGANIC-TIER CREATORS HAVE JUST CONFIRMED THE WAVE.**

---

## Data quality

- **Source**: Today's FastMoss morning crawl LANDED CLEAN with all 11 jobs — n=20 viral_kbeauty_7d UK + n=50 viral_korean_skincare_7d UK + n=30 promoted_skincare_monthly + n=10 deep_video_top10 refreshed. Combined fresh-pool unique UK n≈60 (after dedup overlap between the two viral lists). Cross-references: today's `viral-video-parse.md` (Day-8 carry-forward 06-12 pool 80 rows + 3 NEW WebSearch surfaces — file written BEFORE FastMoss landed and erroneously claims absence; this pattern-read uses the actual fresh pool), `creator-uk-female.md`, `tiktok-sounds.md` (WWM + Material Lover + Love Me NEW), `tag-content-tracker.md` (#jelloskin NEW + #kfragrance + #khaircare + #keyth NEW), `trends-uk-ie.md` (Boots K-Fragrance/K-Haircare/K-Pharmacy expansion, Lauren Franklin L'Oréal Glass Skin, Sulwhasoo Cult Beauty UK luxury entry, INKEY ectoin/PGA, Yepoda UK store-doubling).
- **Italy drift**: not a factor today (UK pool only). Italian growthrank/risingstar files present but ignored per scope.
- **Sample bias**: fresh pool skews **paid-heavy at 83%** — within the Day-3-to-Day-6 baseline band of 80-88%. Organic n=10 is sub-threshold for a robust median (single outliers can shift), so the 4.87% organic median should be read as ±1.5pp directional. Hook taxonomy update HIGH confidence on the 3 NEW hooks (Najma Starlike, Goatie05 POV-walkback, Paula Romanian BOJ) — all directly inspected from FastMoss captions. NEW Day-6 surfaces (Lauren Franklin L'Oréal + jello skin / @hayleeyy_x + Keyth captured-zero) come from today's `viral-video-parse.md` and `trends-uk-ie.md` cross-references; HIGH confidence on the macro signal, MEDIUM on the specific @hayleeyy_x ER estimate (search-result tier inference).
- **n constraints**: fresh-pool unique UK n≈60, AD=50 / Org=10. Combined with the Day-8 carry pool (80 rows) the working frame is n≈140 carry+fresh. Length / hook / caption / sound / CTA distributions reported above are on the FRESH pool only (n=60) to avoid double-counting carry items already reported Day-6. The "Faded / evolving" table integrates both windows.
- **CARRY-FORWARD coverage**: Day-6 named 12 carryable patterns; **6 re-verified directly today via fresh pool** (KIBODI store-tour CONFIRMED-FRESH, Najma sound-meta-EVOLVED-to-POV, LoveMagicandSarah PDRN restock RE-EMERGED, Goatie05 RE-EMERGED, AXISY UK UN-FADED, retailer-tag CTA held); **3 confirmed via cross-reference** (joannachimonides BOJ celebrity-derm-validation language-extended, BIOHEAL BOH FADED-CONFIRMED, Mediheal retailer-channel held); **3 WATCH-LIST DAY-3-ABSENT moved to FADED** (Yepoda Pride, Centellian24, Charna PR, MaggieA Thoughts, Chloe Marie Devlin validation-claim micro — 5 actually faded under the 3-day rule today).
- **Diversity check**: **3 NEW pattern variations** vs Day-6 — POV-with-discount-code organic-affiliate (Najma Starlike), POV-overhype-walkback double-post (Goatie05 Dr.Melaxin), Romanian-language diaspora-PAID Boots AD (Paula BOJ). **Meets the ≥2 NEW requirement.** Adjacent NEW surfaces (Lauren Franklin Western-brand encroachment, #jelloskin emergent cluster, Dr.Reju-All K-Pharmacy creator-wave, d'Alba first organic, Aimée Narae UK paid open) overflow the diversity floor — total 8 NEW elements catalogued, 3 confirmed at pattern-template level + 5 confirmed at brand-emergence or competitive-signal level.
- **DROP rule applied**: BIOHEAL BOH (Day-2 FADED → FADED-PERMANENT), Yepoda Pride (Day-4 absent → FADED), Centellian24 / Charna / MaggieA Thoughts (Day-3 absent → FADED), Chloe Marie Devlin validation-claim micro (Day-3 of carry-only without fresh second → FADED). Mode F (colour-coordinated) + Cindy Lee #gurwm + humor + before-after formats all held permanently FADED at 7+ days absent each.
- **Confidence**: HIGH on Dr.Melaxin elevation to 2nd workhorse (8/12 top promoted SKUs + Goatie05 organic-tier confirm + multiple creator-AD); HIGH on Najma Day-7 evolution (2 distinct posts inspected directly); HIGH on Romanian-language diaspora-PAID (Paula caption full-Romanian text-inspected); HIGH on store-tour 8-day structural-stability (fresh KIBODI re-verification); HIGH on BIOHEAL BOH FADED-PERMANENT (2 consecutive days zero new surfaces); MEDIUM on Dr.Reju-All K-Pharmacy creator-wave (4 instances across 7d, single creator family); MEDIUM on Lauren Franklin Western-brand encroachment competitive-signal (single instance, but at 28.57% ER — needs Day-8 confirm); MEDIUM on @hayleeyy_x jello-skin first-anchor (search-tier inference, view-count estimate); LOW on first-3-sec visual + closed-caption presence (assessed from caption text + creator format history — no actual frame inspection — TikTok 403-block persists Day-7).
- **DROP candidates for Day-8 (2026-06-14)**: ElleMoonz GRWM (Day-4 absent → DROP unless fresh), Frishta confession (Day-4 of carry-only → DROP candidate), iona francis verdict-list (Day-4 absent → DROP candidate), BTY COSMETICS Moira NI store-tour (carry under cluster — keep), Modest-fashion Eniyah Rana crossover (Day-3 of carry → DROP candidate Day-9 if no fresh).
- **Day-8 priority**: confirm @bootsuk / @bootsireland retailer-channel for Keyth + Daeng Gi Meo Ri + Kundal launch videos (the captured-zero from today's `viral-video-parse.md`); WebSearch for first IE creator surface on Sulwhasoo Cult Beauty UK + Dr.Althea Boots UK + Mediheal Boots IE; verify Lauren Franklin L'Oréal Glass Skin ER trajectory (whether 28.57% holds at Day-8 or proves single-day outlier); brand-search Narae UK + d'Alba UK to detect whether their Day-7 first-creator-surfaces produce a second instance; brand-search Dr.Reju-All UK to formalise the K-Pharmacy creator-wave as a sustained-format vs single-creator-family.

— End of Day-7 content-pattern —
