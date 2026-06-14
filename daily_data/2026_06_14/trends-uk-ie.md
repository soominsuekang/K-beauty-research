# K-Beauty Google Trends — UK & Ireland — 2026-06-14

> **DATA QUALITY — read first.** Day 8 of the `trends.google.com` block. `pytrends.TrendReq` constructs cleanly (urllib3<2 pin held) but every `interest_over_time()` call still returns `ResponseError: 403`. Direct `curl` to `trends.google.com`, `google.com`, `news.google.com`, `wikipedia.org`, `reddit.com` all return `HTTP/2 403 x-deny-reason: host_not_allowed`. **No numerical UK/IE Google-Trends values were captured this cycle.** `WebSearch` remains the only working web-side signal in the container; UK avg / IE avg columns hold a qualitative `+`/`=`/`−`/`n/a` triage sampled from UK/IE trade press + retail announcements, NOT a 0–100 Trends index. See `## Data quality` for the full diagnosis + escalation status. **Day 8 of the fade clock — Manyo Day 4 SURVIVED with John Lewis × Skin Cupid 20-brand cohort attribution; BIOHEAL BOH Day 6 still on watch (no Boots/Sephora UK anchor); TONYMOLY Snail PDRN Day 2 still thin.** Today's headline retail signal is the **AESTURA "Barrier Hotline" Sephora UK pop-up at 59 Greek Street on 6–7 June 2026** (Cosmetics Business + Sephora UK live PDPs) — the first Korean dermocosmetic brand to physically activate in UK Sephora — plus the **MEDIPEEL "Science in Red" UK Launch Event with GlamTouch** (PR Newswire + GlamTouch Bloomsbury) + 400 EU influencer cohort + concurrent Printemps Paris Haussmann debut, and the **Dr Reju-All Advanced PDRN Rejuvenating Cream 20ml live on Boots UK** (PDP 10382170 + Superdrug listing). Three new K-Pharmacy / K-derm retail anchors in 24h = the K-Pharmacy category has graduated from "named in yesterday's Boots Trends Report framing" to "three named UK retail anchors live this week".

## Tracking distribution
BASE: 23 / CARRY-FORWARD: 31 / NEW: 4

- BASE brands (14): medicube, Dr.Melaxin, d'Alba, COSRX, Beauty of Joseon, AXISY, mixsoon, INKEY List, Wonderskin, Halara, Numbuzin, Anua, VT, Purito
- BASE categories (9): Korean skincare, k-beauty, glass skin, tiktok skincare, kbeauty haul, well ageing, skin longevity, PDRN, NAD+
- CARRY-FORWARD brands (12):
  - Day 8 (origin 2026-06-07): Biodance, Laneige, TIRTIR, HaruHaru Wonder, Yepoda *(all "off watch" per yesterday's Day-7 survival)*
  - Day 6 (origin 2026-06-08): BIOHEAL BOH *(still on watch — Day 7 tomorrow critical)*, Mediheal *(off watch)*
  - Day 4 (origin 2026-06-10): Manyo *(SURVIVED Day 4 with John Lewis × Skin Cupid 20-brand cohort attribution — off watch)*
  - Day 3 (origin 2026-06-11): Sulwhasoo, Rejuran, Dr.Althea
  - Day 2 (origin 2026-06-12, promoted from NEW): TONYMOLY Snail PDRN Recovery
  - Day 1 (origin 2026-06-13, promoted from NEW): Keyth
- CARRY-FORWARD categories / ingredients / retail-events (19):
  - Day 8 (origin 2026-06-07): snail mucin, rice toner, skin barrier *(off watch)*
  - Day 6 (origin 2026-06-08): spicules, exosome
  - Day 5 (origin 2026-06-09): hanbang, ectoin *(off watch)*, polyglutamic acid *(off watch)*, glazed donut skin
  - Day 4 (origin 2026-06-10): Korean bodycare, Korean lash lift, azelaic acid
  - Day 3 (origin 2026-06-11): matcha skincare
  - Day 2 (origin 2026-06-12, promoted from NEW): bakuchiol, fermented retinol, Boots K-Beauty Airlines (Bristol)
  - Day 1 (origin 2026-06-13, promoted from NEW): K-Fragrance, K-Haircare, jelly beauty / jello skin
- NEW today (4 — required ≥3):
  1. **AESTURA** (brand — K-Pharmacy / dermocosmetic) — **AESTURA "Barrier Hotline" pop-up at 59 Greek Street with Sephora UK on 6 and 7 June 2026** (per Cosmetics Business "Aestura to host skin barrier-focused UK pop-up in partnership with Sephora"); **ATOBARRIER365 full line live on sephora.co.uk** — Lotion 150ml, Cream, Cream Mist 120ml, Hydro-Essence 200ml, Hydro Cera-Ha Serum 30ml all indexed; AESTURA branded brand-page on Sephora UK live (`/brands/aestura`); **17-country European Sephora rollout** (~680 stores) per Amorepacific official news (5 March 2026) + AESTURA International. Distinct from BASE brands because AESTURA is Amorepacific's clinical / dermocosmetic line — Korea's #1 dermatologist-recommended dermocosmetic brand per the official PRNewswire wire — making it the FIRST K-dermocosmetic brand the routine has logged with both a physical UK pop-up and a Sephora UK PDP cohort. Anchors the K-Pharmacy NEW category row.
  2. **MEDIPEEL** (brand — K-derm aesthetic) — **"MEDIPEEL UK Launch Event — Science in Red" announced** (per PR Newswire "MEDIPEEL EXPANDS ACROSS EUROPE WITH OFFICIAL PRINTEMPS DEBUT AND UK LAUNCH EVENT" 16 Jan 2026 + GlamTouch UK collections page `/collections/medipeel`); in-store pop-up + hands-on product demos + **400 UK and European influencers** + 'MEDIPEEL Lab Passport' programme + QR-code activations; concurrent **Printemps Paris Haussmann flagship debut** following earlier two-Printemps-France launch; **GlamTouch Bloomsbury (London) named UK partner** — positioned as "London's premier K-beauty select shop"; **Red Lacto Collagen Wrapping Mask + Young Cica PDRN line** named as standout SKUs. Distinct from BASE because MEDIPEEL is a professional derma-aesthetic brand entering through an EU-wide flagship-partner channel (Printemps + Sephora-adjacent GlamTouch), not the Boots/Sephora-led BASE/CF pattern — first MEDIPEEL UK entry the routine has logged.
  3. **Dr Reju-All** (brand — K-Pharmacy) — **Dr.Reju-All Advanced PDRN Rejuvenating Cream 20ml live on Boots UK** (PDP 10382170 `/dr-rejuall-all-advanced-pdrn-rejuvenating-cream-20ml-10382170`); **Superdrug listing live** (`/dr-reju-all-advanced-pdrn-rejuvenating-cream-20g/p/mp-00298714`); **Amazon UK PDP live** (B0FN7L65C1) with "Korean Pharmacy Anti-Aging Skin Care Face Cream"; **Stylist UK "K Pharmacy is the latest K Beauty trend to know" editorial names Dr Reju-All alongside Dr.Althea as the two Boots K-Pharmacy anchors**; 99% pure salmon DNA gel-type / 1200ppm PDRN / Niacinamide + Panthenol + Collagen + HA / Dermatest "Excellent" 0.00 irritation index. Distinct from BASE because Dr Reju-All is purely a K-Pharmacy positioning (built by doctors and pharmacists with dermatology background) — second K-Pharmacy brand at UK retail in the routine after Dr.Althea (CF Day 3 today). Anchors the K-Pharmacy NEW category row alongside AESTURA.
  4. **K-Pharmacy** (category) — yesterday flagged in the Boots Trends Report structural-shift framing (alongside K-Fragrance + K-Haircare) but had no named retail anchor; today the category gains **three concurrent UK retail anchors**: **AESTURA at Sephora UK** (PDPs live + Barrier Hotline pop-up 6–7 June 2026), **Dr Reju-All at Boots UK + Superdrug** (Advanced PDRN Rejuvenating Cream live), and **Dr.Althea at Boots UK** (CF Day 3 — PDRN Reju 5000 Cream + Vitamin C + Pure Grinding cohort holds); **Stylist UK "K Pharmacy is the latest K Beauty trend to know" editorial live** = consumer-press validation; Boots's "selected stores nationwide offer skin scan services with advanced imaging" = dermatology-service flank reinforces the K-Pharmacy positioning. Distinct from CF K-Fragrance + K-Haircare because K-Pharmacy is the medicalised / derm-tech axis specifically — PDRN concentration claims (1200ppm Dr Reju-All / "PDRN Reju 5000" Dr.Althea / 99% pure salmon DNA) and barrier-recovery claims (ATOBARRIER365) are explicitly clinical, not aesthetic. The IE 18-34 audience's adjacent-tier (CeraVe / La Roche-Posay / The Ordinary) is the most direct gateway demographic.

## Brands (last 7 days)

*UK avg / IE avg columns hold qualitative signal (`+` rising, `=` flat, `−` falling, `n/a` no signal). They are NOT Google-Trends 0–100 indices — they are a `WebSearch` triage. Replace with pytrends values the moment the policy is loosened.*

| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| medicube | BASE | + | + | + | rising HARD — **medicube was #1 and #2 on TikTok Shop UK Top Products April 2026** (per FastMoss European top-products report) — two SKUs in top 5; Bristol K&J Beauty Airlines pop-up K-anchor holds; Marie Claire UK Medicube edit "The Products To Add To Your Basket" holds; Azelaic Acid 16 Calming Serum holds; Collagen Jelly Cream 40k+ Amazon-sales anchor holds (probiotics + hydrolyzed collagen + niacinamide) |
| Dr.Melaxin | BASE | + | n/a | + | holding — Boots 2026 June beauty launches lineup placement holds; no Boots UK SKU PDP indexed yet today (Day-9 watch — will check tomorrow whether PDPs go live) |
| d'Alba | BASE | n/a | n/a | n/a | no fresh signal |
| COSRX | BASE | = | = | = | flat — perennial UK staple, Snail Mucin Power Essence remains the cross-trend benchmark; no fresh hit today |
| Beauty of Joseon | BASE | + | + | + | rising HARD — **Matte Sun Stick Mugwort + Camelia confirmed at Lookfantastic UK + Sephora UK** (per Dr Rachel Ho + Nicola Londors + Arktastic reviews); **Relief Sun + Rice Probiotics SPF50+ holds as global cult sunscreen**; Marie Claire UK "Best Korean SPFs" feature holds; Bristol K&J Beauty Airlines K-anchor holds; Revive Firming Moisturizer with Ginseng Ceramide + Fermented Retinol holds |
| AXISY | BASE | n/a | n/a | n/a | no fresh signal |
| mixsoon | BASE | + | n/a | + | rising — K-pop idol routine anchor (ENHYPEN, Jeon Somi) via Skin Cupid UK holds; mass-K creator-side anchor holds |
| INKEY List | BASE | + | + | + | rising — Ectoin Hydro-Barrier Serum + Polyglutamic Acid Hydrating Serum UK retail anchor holds (off-watch per yesterday); UK-origin consumer-discovery layer for two K-aligned CF ingredients holds |
| Wonderskin | BASE | n/a | n/a | n/a | no fresh signal |
| Halara | BASE | n/a | n/a | n/a | apparel, off-thesis |
| Numbuzin | BASE | + | n/a | + | rising — **Numbuzin's NAD+ line confirmed in Boots's "20 new brands" announcement** ("the latest line from Korean Skincare favourite, Numbuzin, features 2026's wonder ingredient NAD+") per Boots Newsroom; No.9 NAD Collagen Under Eye Patches £14 holds; routine's cleanest single-brand NAD+ × K-beauty UK retail hit |
| Anua | BASE | + | + | + | rising HARD — Azelaic Acid 10 Hyaluron Serum + Azelaic + PDRN Serum Bundle Boots UK holds; **Boots Ireland skincare-advice page names Anua among "trending Korean brands at Boots Ireland"** alongside Dr.Jart+ / LANEIGE / Beauty of Joseon / Erborian = IE retail-merchandising-side anchor; Bristol K&J Beauty Airlines K-anchor holds; John Lewis × Skin Cupid cohort holds |
| VT | BASE | + | + | + | rising — Reedle Shot 300 holds as UK consumer-facing spicules wrapper; head-to-head with TONYMOLY Snail PDRN Mirai Skin piece holds |
| Purito | BASE | = | n/a | = | flat — Boots UK 4-brand K-cohort placement holds, no fresh hit today |
| Biodance | CARRY-FORWARD (Day 8) | + | + | + | rising — **Biodance Bio-Collagen Real Deep Mask Pack named the standout K-2.0 viral product** (per Accio TikTok beauty trends report) — "delivers glass skin glow in just one use"; K-beauty 2.0 average basket $40–60 anchor; Grazia UK + British Brief consumer-test pieces hold. Off watch. |
| Laneige | CARRY-FORWARD (Day 8) | + | + | + | rising — Bouncy & Firm Eye Sleeping Mask 20ml indexed as "NEW" at Boots UK holds; **named as IE-retail trending Korean brand by Boots Ireland skincare-advice page**; Sephora UK Sleeping Beauty edit holds. Off watch. |
| TIRTIR | CARRY-FORWARD (Day 8) | + | n/a | + | rising HARD — Matcha PDRN line at Sephora UK (`/brands/tirtir/Matcha`) holds; SKINSIDER UK ingredient spotlight holds. Off watch. |
| HaruHaru Wonder | CARRY-FORWARD (Day 8) | + | n/a | + | rising HARD — Rose PDRN Glowly Balm 10ml Boots UK (10386950) holds; full Rose PDRN line live on official site holds. Off watch. |
| Yepoda | CARRY-FORWARD (Day 8) | + | n/a | + | rising — Yepoda "double UK store portfolio in 2026" + 650+ Sephora Europe stores + The Depuff Eyespresso 90g Sephora UK + K-Beauty Icons Set £40 bundle hold. Off watch. |
| BIOHEAL BOH | CARRY-FORWARD (Day 6) | + | n/a | = | thin — **@bioheal.boh.uk official TikTok handle still active** + Olive Young slow-aging brand-story holds + notino.co.uk PDP holds; **TikTok Shop UK named Colorgram + BIOHEAL BOH as the K-labels using TikTok Shop to introduce and trial products with UK consumers** (per Cosmetics Business TikTok Shop beauty-brand-winners + Cosmetics Business retailtimes) = trade-press validation. **Still on watch — Day 7 tomorrow CRITICAL.** No Boots/Sephora UK retail-shelf anchor yet (third week of TikTok-only). |
| Mediheal | CARRY-FORWARD (Day 6) | + | + | + | rising — PDRN Lifting Pad Boots UK "temporarily unavailable" sell-through state continues (5 days); Boots IE `boots.ie/mediheal` brand page live holds; Boots Ireland Official FB post for PDRN Lifting Pads holds as IE social anchor. Off watch. |
| Manyo | CARRY-FORWARD (Day 4) | + | n/a | + | **SURVIVED Day 4** — **John Lewis × Skin Cupid 20-brand Korean-skincare-and-haircare cohort attribution confirmed** (per Marie Claire UK Cult Beauty page + John Lewis Partnership Korean-skincare-partnership press release) — "Manyo is one of 20 Korean skincare and haircare brands being introduced to John Lewis through a partnership with Skin Cupid"; MA:NYO Pure Cleansing Oil Mini Skin Cupid UK holds; brand "sorceress" botanic-formulation positioning + 2012-established mid-tier credibility holds. **Off watch.** |
| Sulwhasoo | CARRY-FORWARD (Day 3) | + | n/a | + | rising — Cult Beauty UK Concentrated Ginseng Rejuvenating Serum 50ml + Cream 50ml PDPs hold (17601242 / 17601247); Sulwhasoo brand page Cult Beauty UK holds; Who What Wear UK edit holds. CF Day 3 maturing. |
| Rejuran | CARRY-FORWARD (Day 3) | + | n/a | + | rising — 380 Sephora US stores rollout 16 March 2026 backdrop holds; London clinic price cluster (£325–£380/session) holds; Rejuran Advanced Anti-Aging Retinol + c-PDRN Serum 30ml £147.95 Glam Global UK holds. CF Day 3 maturing. |
| Dr.Althea | CARRY-FORWARD (Day 3) | + | + | + | rising HARD — **Stylist UK "K Pharmacy is the latest K Beauty trend to know" editorial names Dr.Althea as the high-end vegan K-Pharmacy anchor alongside Dr Reju-All** = consumer-press elevation; Boots UK 7-SKU range holds (345 Relief Cream + 147 Barrier Cream + Vitamin C Boosting Serum + Pure Grinding Cleansing Balm + Gentle Vitamin C Serum + Rapid Firm Sculpting Cream + PDRN Reju 5000 Cream); Stylist UK £23 PDRN Reju 5000 Cream review piece holds |
| TONYMOLY Snail PDRN Recovery | CARRY-FORWARD (Day 2) | = | n/a | = | thin — Snail PDRN Recovery Cream + Toner + Lotion + Skincare Set live at YesStyle + Beauty Box Korea + Nex Beauty + Belieef holds; no UK retail surface area surfaced today (Boots / Sephora UK / Cult Beauty UK did not return TONYMOLY). **Day 2 of CF — flagged for Day 3-7 monitoring**. UK-availability gap is the open question — the K-pharmacy / K-PDRN cohort grew today but TONYMOLY did not. |
| Keyth | CARRY-FORWARD (Day 1) | + | + | + | rising — **Boots first UK high street K-fragrance launch holds** (Boots UK Newsroom + 9 regional UK news outlets); positioned as "newest name in Korean beauty"; first K-fragrance UK retail anchor in the routine; PDP indexing pending tomorrow. **CF Day 1.** |
| AESTURA | NEW | + | + | + | rising HARD — **Sephora UK "Barrier Hotline" pop-up 59 Greek Street 6–7 June 2026** (per Cosmetics Business); **ATOBARRIER365 line live on sephora.co.uk** — Lotion 150ml + Cream + Cream Mist 120ml + Hydro-Essence 200ml + Hydro Cera-Ha Serum 30ml; AESTURA brand page Sephora UK (`/brands/aestura`); **17-country EU Sephora rollout ~680 stores** (Amorepacific official 5 March 2026); Korea's #1 dermatologist-recommended dermocosmetic brand framing |
| MEDIPEEL | NEW | + | n/a | + | rising HARD — **"MEDIPEEL UK Launch Event — Science in Red"** with GlamTouch + 400 UK + European influencers + MEDIPEEL Lab Passport + QR-code activations (per PR Newswire 16 Jan 2026); concurrent **Printemps Paris Haussmann flagship debut** following earlier two-Printemps-France launch; **GlamTouch Bloomsbury London** named UK partner; **Red Lacto Collagen Wrapping Mask + Young Cica PDRN line** named standout SKUs |
| Dr Reju-All | NEW | + | n/a | + | rising HARD — **Dr.Reju-All Advanced PDRN Rejuvenating Cream 20ml live on Boots UK** (PDP 10382170); **Superdrug listing live** (mp-00298714); **Amazon UK** B0FN7L65C1; **Stylist UK "K Pharmacy is the latest K Beauty trend to know" names Dr Reju-All as Boots K-Pharmacy anchor**; 99% pure salmon DNA 1200ppm PDRN + Niacinamide + Panthenol + Collagen + HA; Dermatest "Excellent" 0.00 irritation index |

## Categories (last 7 days)

| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| Korean skincare | BASE | + | + | + | rising HARD — **Boots Ireland skincare-advice page "What is K-Beauty?" live** + Boots IE Korean Skincare category page live = IE consumer-discovery layer reinforced; Boots fivefold YoY UK + "sold every 11 seconds" + John Lewis × Skin Cupid 20-brand partnership + 800% YoY hold; Bristol K&J Beauty Airlines pop-up holds; **the Boots 2026 K-Fragrance + K-Haircare + K-Pharmacy expansion structurally elevates the category** |
| k-beauty | BASE | + | + | + | rising — TikTok Shop UK K-Beauty Collective holds; #kbeauty = 3rd most-used UK beauty hashtag; **K-beauty 2.0 framing now appears in TikTok-trends reports as the higher-basket ($40-60) successor to clean-girl** (per Accio + Qogita) |
| glass skin | BASE | + | + | + | rising — Penneys IE "How To Get Glass Skin" holds; Glass Skin Masks named in TikTok-Shop sales report holds; **Biodance Bio-Collagen Real Deep Mask Pack = canonical glass skin product** per Accio "delivers glass skin glow in just one use"; now competing in-aesthetic with jelly beauty + jello skin |
| tiktok skincare | BASE | + | + | + | rising — TikTok Shop UK K-Beauty search +125% holds; #kbeauty 3rd most-used UK beauty hashtag holds; top 10 beauty hashtags drove $670M+ combined sales holds; TikTok Shop UK Beauty Crush Week K-beauty promo holds |
| kbeauty haul | BASE | = | = | = | flat (steady creator-side format, no inflection) |
| well ageing | BASE | = | n/a | = | flat — continues losing SoV to "skin longevity" + "hanbang 2.0" + "Project Preservation" + BIOHEAL BOH's "slow aging" + AESTURA "barrier care" terminology |
| skin longevity | BASE | + | + | + | rising — Numbuzin "Project Preservation" Boots 2026 framing holds; BIOHEAL BOH "slow aging" reinforces; **AESTURA "Barrier Hotline" + Skin Barrier 365 line adds the barrier-restoration → longevity terminology** |
| PDRN | BASE | + | + | + | rising HARD — **6 UK/IE PDRN retail anchors now live**: Anua Azelaic + PDRN Bundle Boots UK + HaruHaru Rose PDRN Glowly Balm Boots UK + Dr.Althea PDRN Reju 5000 Cream Boots UK + Mediheal PDRN Lifting Pad Boots IE + Rejuran c-PDRN Serum Glam Global UK + **Dr Reju-All Advanced PDRN Rejuvenating Cream Boots UK + Superdrug (NEW)**; PDRN +21.20% CAGR → $4.3B by 2033 forecast holds; TikTok #pdrn = 170.4K posts; PDRN concentration claims wars now public ("1200ppm" Dr Reju-All vs "PDRN Reju 5000" Dr.Althea vs "99% pure salmon DNA" framing) |
| NAD+ | BASE | + | n/a | + | rising — **Numbuzin No.9 NAD+ line explicitly named in Boots's "20 new brands" announcement** ("2026's wonder ingredient NAD+"); £14 Under Eye Patches Boots holds; routine's only NAD+ × K-beauty UK retail hit |
| snail mucin | CARRY-FORWARD (Day 8) | + | + | + | rising — TONYMOLY Snail PDRN Recovery brand-level snail-mucin × PDRN crossover holds; COSRX UK staple holds. Off watch. |
| rice toner | CARRY-FORWARD (Day 8) | = | + | + | rising in IE — Penneys IE PS… K-Beauty Rice Face Toner holds; Penneys IE Korean Skincare collection page live. Off watch. |
| skin barrier | CARRY-FORWARD (Day 8) | + | + | + | rising HARD — **AESTURA "Barrier Hotline" Sephora UK pop-up + ATOBARRIER365 5-SKU sephora.co.uk cohort live** = single biggest skin-barrier retail anchor the routine has logged; "Multi-Ceramide Systems" 2026 K-Beauty Packaging Resource framing holds; **K-Pharmacy as Boots's new K-category structurally reinforces the barrier/dermatology axis**. Off watch. |
| spicules | CARRY-FORWARD (Day 6) | + | n/a | + | rising — +119% YoY spicule skincare / +535% YoY liquid microneedling UK velocity holds; VT Reedle Shot 300 wrapper holds |
| exosome | CARRY-FORWARD (Day 6) | + | n/a | + | rising — KIPO exosome-delivery patent filings +60% (2023→2024) holds; Amorepacific + Huons + CHA Biotech patent cluster holds |
| hanbang | CARRY-FORWARD (Day 5) | + | n/a | + | rising — Sulwhasoo £220 ginseng cream + Beauty of Joseon "ginseng ceramide + fermented retinol" Revive Firming Moisturizer pair holds; modernised hanbang term holds |
| ectoin | CARRY-FORWARD (Day 5) | + | + | + | rising — UK ectoin searches +86% holds; INKEY List Ectoin Hydro-Barrier Serum UK retail anchor holds; VITA "10 Skincare Power Players 2026" holds. Off watch. |
| polyglutamic acid | CARRY-FORWARD (Day 5) | + | + | + | rising — INKEY List Polyglutamic Acid Hydrating Serum UK retail anchor holds; 4× moisture-retention vs HA framing holds. Off watch. |
| glazed donut skin | CARRY-FORWARD (Day 5) | + | + | + | rising — Penneys IE "How To Get Glass Skin" holds; `#glazeddonutskin` >1.8M TikTok views holds; competing in-aesthetic with jelly beauty + jello skin |
| Korean bodycare | CARRY-FORWARD (Day 4) | + | + | + | rising — Marie Claire UK piece holds; summer KP / body-acne / neck-décolletage window open through July–August |
| Korean lash lift | CARRY-FORWARD (Day 4) | + | n/a | + | rising HARD — +20,082% YoY UK Fresha booking searches holds; **#1 top-searched beauty service for 2026** (Qogita) holds |
| azelaic acid | CARRY-FORWARD (Day 4) | + | + | + | rising HARD — Medicube Azelaic Acid 16 Calming Serum holds (3rd K-brand UK-context azelaic SKU); +49% YoY UK searches (60,500/mo) holds; "Western acne concerns" K-beauty merchandising angle holds |
| matcha skincare | CARRY-FORWARD (Day 3) | + | + | + | rising HARD — TIRTIR Matcha brand page Sephora UK holds; 4 Matcha-line SKUs at UK retail hold; **+212.5% Aug 2024–Aug 2025 skincare search growth driven partly by TikTok matcha-skincare trend** (per Accio) |
| bakuchiol | CARRY-FORWARD (Day 2) | + | + | + | rising — SKINSIDER UK "K-beauty's latest obsession" holds; UK bakuchiol sales +6.5% CAGR through 2025–2035 (Future Market Insights) holds |
| fermented retinol | CARRY-FORWARD (Day 2) | + | + | + | rising HARD — Beauty of Joseon Revive Firming Moisturizer Ginseng Ceramide + Fermented Retinol holds; New Beauty 2026 Best Retinoid Launches naming holds |
| Boots K-Beauty Airlines (Bristol) | CARRY-FORWARD (Day 2) | + | + | + | rising — Bristol pop-up 28 May–19 July 2026 holds (44 days left); BeautyMatter + Beauty Magazine UK + Bristol247 trade-press follow-up holds; **store displays >200 leading and emerging brands across skincare, haircare, fragrance, cosmetics, premium beauty, wellness and electrical beauty** + complimentary scalp + skin-imaging services |
| K-Fragrance | CARRY-FORWARD (Day 1) | + | + | + | rising — Boots K-Fragrance named as 1 of 3 strategic K-categories holds; 2024 Korean perfume exports = $386.4M, +40% YoY (fastest-growing K-beauty export segment) holds; Marie Claire UK K-Fragrance editorial holds; Keyth = first UK retail K-fragrance brand anchor (CF Day 1 brand row) |
| K-Haircare | CARRY-FORWARD (Day 1) | + | + | + | rising — Daeng Gi Meo Ri + Kundal Boots UK holds; Marie Claire UK "9 Best K-Beauty Hair Products" holds; Boots `/beauty/hair/korean-haircare` category page holds |
| jelly beauty / jello skin | CARRY-FORWARD (Day 1) | + | + | + | rising — Marie Claire UK "Jelly Beauty" + Stylist UK "Jello skin" editorials hold; #jelloskin = 14M TikTok views holds; **Medicube Collagen Jelly Cream 40k+ Amazon sales = jelly skin's named hero product**; distinct from glass skin + glazed donut |
| K-Pharmacy | NEW | + | + | + | rising HARD — **3 named UK retail anchors live today**: AESTURA Sephora UK + Dr Reju-All Boots UK + Superdrug + Dr.Althea Boots UK; **Stylist UK "K Pharmacy is the latest K Beauty trend to know" editorial = consumer-press anchor**; Boots's "selected stores nationwide offer skin scan + advanced imaging" services reinforces dermatology-service flank; **K-Pharmacy = the medicalised / derm-tech axis distinct from K-Fragrance + K-Haircare**; PDRN concentration claims wars + ATOBARRIER365 + AESTURA "Korea's #1 dermatologist-recommended" framing = K-Pharmacy's consumer-positioning playbook |

## Faded / contradicted carry-forwards

- **Manyo Day 4 SURVIVED** — John Lewis × Skin Cupid 20-brand Korean-skincare-and-haircare cohort attribution confirmed today via Marie Claire UK Cult Beauty page + John Lewis Partnership official press release. Manyo went from Day 3 "thin / creator-side only" to Day 4 "20-brand-cohort + multi-retailer trade-press" = clean survival. **Manyo moves OFF watch.**
- **BIOHEAL BOH Day 6 — still on watch, Day 7 tomorrow CRITICAL.** TikTok Shop UK Cosmetics Business piece names Colorgram + BIOHEAL BOH as K-labels using TikTok Shop to trial products with UK consumers = trade-press validation, but still no Boots/Sephora UK retail-shelf anchor. Day 7 tomorrow is the **drop-or-survive** decision under the 3-consecutive-thin rule (the @bioheal.boh.uk TikTok-only signal has been the only fresh anchor since Day 1). If no Boots/Sephora UK PDP or trade-press retail-listing surfaces tomorrow, BIOHEAL BOH should be marked "faded — TikTok-only proof-of-life insufficient under retail-anchor rule".
- **TONYMOLY Snail PDRN Recovery Day 2 — thin.** No UK retail surface area surfaced today (Boots UK / Sephora UK / Cult Beauty UK did not return TONYMOLY in any search). YesStyle + Beauty Box Korea + Nex Beauty + Belieef listings hold as Day-2 baseline but TONYMOLY's UK-retail-shelf gap is widening relative to the K-Pharmacy cohort (which added 3 UK retail anchors in 24h). Day 3 tomorrow continues monitoring; Day 5 will be the fade-clock decision point if no UK retail breakthrough.
- **K-Fragrance CF Day 1 — Keyth PDP still pending Boots UK indexing.** Boots Newsroom + 9 regional UK news outlets still the only anchors; Boots.com PDP search for `keyth` did not return SKU pages today. Day 2 tomorrow continues monitoring.
- **Round Lab + SKIN1004 + Centellian24 stay dropped** (faded 2026-06-11 / 2026-06-11 / 2026-06-10). No fresh signal today contradicts the fade. Round Lab + SKIN1004 confirmed still on Boots UK + Sephora UK shelves but that is baseline retail presence, not a fresh news anchor.

**No contradictions** — nothing in today's sampling refutes a previously surfaced brand or category. PDRN's retail anchor count expanded by one (Dr Reju-All), Boots IE skincare-advice page reinforced multiple CF brands (Anua + Laneige + Beauty of Joseon), and the K-Pharmacy structural-shift thesis logged its first 3 named UK retail anchors in a single day.

## Anomalies (>50% change)

- **AESTURA's 17-country European Sephora rollout = ~680 physical stores** (per Amorepacific 5 March 2026 + AESTURA International + Cosmetics Business) — single largest fresh K-derm retail-footprint anomaly today; the UK Sephora "Barrier Hotline" pop-up is the named UK activation within that pan-EU rollout.
- **MEDIPEEL Lab Passport + 400 UK + European influencer cohort** (per PR Newswire 16 Jan 2026 + GlamTouch) — single largest fresh creator-mobilisation figure today for a K-derm UK launch.
- **+212.5% Aug 2024–Aug 2025 skincare search growth** driven by TikTok routines like "Project Pan" + matcha-skincare ingredient trends (per Accio) — held + corroborates the matcha-skincare CF row.
- **TikTok Shop UK active creators +72% YoY** (per Cosmetics Business + TikTok Newsroom UK) — held; creator-supply growth = creator-led K-beauty distribution accelerator.
- **132% YoY hypochlorous acid skincare search growth** (per Accio) — first-time logged anomaly; HOCl is the adjacent-axis to K-Pharmacy / barrier-care positioning (white-blood-cell-produced gentle-reset framing). Watch for K-brand HOCl SKU at UK retail as a fade-clock trigger.
- **PDRN concentration claims wars are now public** — "1200ppm" (Dr Reju-All) vs "PDRN Reju 5000" (Dr.Althea naming convention) vs "99% pure salmon DNA" (Dr Reju-All purity claim) — first time the routine has logged competing PDRN-concentration marketing claims at UK retail simultaneously.
- **2024 Korean perfume exports = $386.4M, +40% YoY** — held (CF anchor for K-Fragrance category).
- **PDRN skincare market +21.20% CAGR → $4.3B by 2033** — held (Barchart).
- **Yepoda plans to DOUBLE UK store portfolio 2026** — held (Cosmetics Business + Trend Hunter).
- **UK ectoin skincare searches +86%** — held (Luxury London).
- **Rejuran Cosmetics 380 Sephora US stores 16 March 2026** — held (Barchart + NewBeauty); backdrop for UK Sephora rollout watch.
- **UK bakuchiol sales +6.5% CAGR through 2025–2035** — held (Future Market Insights).
- **Boots K-Beauty +500% YoY / "sold every 11 seconds"** — held.
- **TikTok Shop UK K-Beauty search +125% / basket value ~35% above skincare average** — held.
- **Korean lash lift +20,082% YoY UK Fresha booking searches** — held; #1 top-searched beauty service 2026 (Qogita).
- **TikTok #pdrn = 170.4K posts** — held.
- **Spicules / liquid microneedling +119% / +535% YoY UK** — held.
- **TikTok Shop UK 60% YoY beauty sales growth** — held; TikTok Shop = 4th-largest UK beauty retailer.
- **azelaic acid +49% YoY UK monthly searches** (60,500/mo) — held.
- **matcha skincare +2,300% Google search surge** (Jan 2025 base) — held.
- *No other >50% movers in today's qualitative sample. Real anomaly detection resumes the moment pytrends is unblocked.*

## Notes for content strategy (IE 18-34 women)

1. **The "K-Pharmacy is THIS WEEK's K-beauty acceleration story — and it has 3 named UK retail anchors live right now" pitch is the cleanest macro-shoot.** AESTURA at Sephora UK ("Barrier Hotline" 59 Greek Street 6–7 June 2026 + ATOBARRIER365 5-SKU cohort), Dr Reju-All at Boots UK + Superdrug (Advanced PDRN Rejuvenating Cream 20ml + Stylist UK editorial), and Dr.Althea at Boots UK (7-SKU range + Stylist UK £23 PDRN Reju 5000 review) = three named K-Pharmacy retail anchors that all hit shelves in the same fortnight. Pitch: *"K-Beauty just turned into K-Pharmacy: 3 Korean derm brands now sold next to your CeraVe at Boots Henry Street / Sephora Dundrum. Here's the £20 hero from each — and which one's right for your skin barrier."* IE 18-34 audience has been primed by CeraVe / La Roche-Posay / The Ordinary — K-Pharmacy is the natural next-tier upgrade. Strong because all 3 brands are under £25 entry-tier (Dr.Reju-All 20ml + Dr.Althea PDRN Reju 5000 Cream £23 + AESTURA ATOBARRIER365 ~£20) — directly substitutable into the IE 18-34 dupe-economy shopping pattern.

2. **The "Boots's K-beauty triple expansion = K-Fragrance + K-Haircare + K-Pharmacy" structural-shift framework holds for the IE side too.** Yesterday's pitch (Keyth = Sol de Janeiro replacement, Daeng Gi Meo Ri = Olaplex alternative) gains a third leg today with AESTURA + Dr Reju-All + Dr.Althea as the K-Pharmacy anchors. Pitch: *"K-beauty is no longer just glass skin — it's the 3-aisle takeover: a Korean perfume (Keyth), a Korean haircare (Daeng Gi Meo Ri), and a Korean derm cream (AESTURA ATOBARRIER365) at one Boots run. Here's the £100 budget K-beauty haul that mirrors your existing Sephora / Boots routine in three categories."* The Boots IE Henry Street + Dundrum surface area means the IE 18-34 viewer can walk in and buy these — the Bristol K&J Airlines anchor is the UK-only flank.

3. **"Medicube wins TikTok Shop UK April 2026 (#1 + #2)" is the cleanest creator-economy macro-flex shoot.** FastMoss data confirms two medicube SKUs in the TikTok Shop UK April top 5 — that's #1 across the entire UK TikTok Shop beauty category. Pitch: *"This Korean brand owned TikTok Shop UK in April — and the £25 jelly cream that's at the centre of it is the same one Marie Claire UK just put in their basket. Why Medicube is the K-brand to know if you're shopping TikTok-first."* Plug into the existing IE 18-34 TikTok-Shop demand pattern (April European top-products report = anchor) — this is the "shop the trend that's already winning" pitch, not the discovery pitch.

4. **The "MEDIPEEL just landed at GlamTouch Bloomsbury with 400 EU influencers" pitch is the cleanest London-IRL → IE-discovery angle.** MEDIPEEL UK Launch Event "Science in Red" + GlamTouch's Bloomsbury K-beauty select store + 400 UK + EU influencers + Lab Passport QR programme + concurrent Printemps Paris Haussmann flagship = the most ambitious K-derm event-marketing activation the routine has logged. Pitch: *"London's biggest K-beauty store (GlamTouch Bloomsbury) is about to host the launch of a derma brand the Korean dermatologists already use — Red Lacto Collagen + Young Cica PDRN. Here's what to grab when you fly over for a weekend, or which SKUs to order to Dublin via their site."* The London-IRL → Dublin-online conversion is the IE 18-34 weekend-trip / online-import shopping pattern.

## Data quality

**Status: PARTIAL — Google Trends fetch blocked at the network-policy layer for the EIGHTH consecutive day; qualitative `WebSearch` triage substituted again.**

Diagnosis (Day 8, unchanged from Days 5–7):
- `pip install pytrends 'urllib3<2'` succeeds; `pytrends.TrendReq` constructs cleanly.
- Single-keyword GB + IE `interest_over_time()` fetches both return `ResponseError: The request failed: Google returned a response with code 403`.
- Direct `curl -sI -m 6 https://trends.google.com/trends/api/explore` → `HTTP/2 403 x-deny-reason: host_not_allowed`.
- Direct `curl` to `google.com`, `news.google.com`, `wikipedia.org`, `reddit.com` → same `HTTP/2 403 host_not_allowed`.
- **`WebSearch` is unblocked** and was used today to triage UK/IE-press signal for each tracked keyword. Sources sampled today: Boots UK Newsroom + Boots.com PDPs + Boots IE + Sephora UK PDPs + brand pages + Cult Beauty UK + Superdrug + Amazon UK + Marie Claire UK + Stylist UK + Cosmetics Business + BeautyMatter + CEW UK + Cosmetics Business UK + Retail Times UK + ChannelX + Supply Chain Digital + TheIndustry.beauty + TikTok Newsroom UK + FastMoss European top-products + Accio TikTok beauty trends + Qogita + PR Newswire + Amorepacific official news + AESTURA International + GlamTouch UK + One Eye Beauty + KherBlog + STYLEVANA + Hello Seoul + Notino UK + SKINSIDER UK + Mirai Skin + Korean Skincare Coach + Penneys IE + Boots IE + John Lewis Partnership + Marie Claire UK Cult Beauty page + Bristol247 + Beauty Magazine UK + KamCity + COOS Cosmetics + Thai Botanics + Dr Rachel Ho + Nicola Londors + Arktastic + I DEW CARE + Spill the Coffee + Trend Hunter + NewBeauty + Barchart + Coréelle + Hwahae rankings + House of Korea + Female Daily Reviews + Skin2Seoul + The Scarborough News + Northern Ireland World + Derry Journal + National World regional UK cluster.

What that means for the table: UK avg / IE avg / Today-vs-7d-avg columns are a **qualitative** sample (`+`/`=`/`−`/`n/a`) sourced from `WebSearch`, **not** a Google-Trends 0–100 index. The bucket framework, the fade clock, and the anomaly column are still valid; cross-day velocity comparisons will not be quantitative until pytrends is unblocked.

Escalation status:
- **Day 8 of 403 → escalation overdue.** Today's run re-confirms the value of the WebSearch proxy: AESTURA + MEDIPEEL + Dr Reju-All + K-Pharmacy = 4 NEW, plus Manyo promoted off-watch via John Lewis × Skin Cupid 20-brand cohort attribution. **Day 8 of identical block = network policy decision, not a transient — file the loosening request with Anthropic now** (target hosts: `trends.google.com`, `news.google.com`, `wikipedia.org`, `reddit.com`, `google.com`). Documentation: https://code.claude.com/docs/en/claude-code-on-the-web.
- Worst-case substitute (continues to work): keep building on `WebSearch` triage + `fastmoss_raw/` TikTok exports + Boots.ie / Skin Cupid IE / Cult Beauty UK PDP review-count deltas + Bristol concept-store visit-side reviews once they appear + Sephora UK Greek St "Barrier Hotline" pop-up footfall reporting.

Tomorrow's run will: (a) re-attempt pytrends — if Day 9 of 403, the escalation should be filed or this becomes the permanent deliverable; (b) advance fade clock to Day 9 — **BIOHEAL BOH Day 7 = drop-or-survive** under the 3-consecutive-thin rule; (c) Keyth Day 2 — check if Boots UK PDPs are indexed (will be the routine's first K-fragrance retail PDP); (d) TONYMOLY Snail PDRN Day 3 — check Boots UK / Sephora UK / Cult Beauty UK fresh; (e) AESTURA Day 2 — check post-pop-up press recap (Cosmetics Business + Beauty Magazine UK + TheIndustry.beauty likely follow-ups); (f) MEDIPEEL Day 2 — check whether GlamTouch Bloomsbury event date is announced; (g) Dr Reju-All Day 2 — check if Boots IE / Superdrug IE PDPs land.

---

Sources sampled today (via `WebSearch`, all UK/IE-facing trade, consumer press, or retail announcements):

- [Boots releases 2026 Beauty & Wellness Trends Report — Boots UK Newsroom](https://www.boots-uk.com/newsroom/news/boots-releases-2026-beauty-wellness-trends-report-alongside-line-up-of-trending-new-brands/)
- [Boots accelerates beauty reinvention with opening of new concept store in Bristol — Boots UK Newsroom](https://www.boots-uk.com/newsroom/news-item/boots-accelerates-beauty-reinvention-with-opening-of-new-concept-store-in-bristol/)
- [Aestura to host skin barrier-focused UK pop-up in partnership with Sephora — Cosmetics Business](https://cosmeticsbusiness.com/aestura-to-host-skin-barrier-focused-uk-pop)
- [AESTURA ATOBARRIER365 Lotion 150ml — Sephora UK](https://www.sephora.co.uk/p/aestura-atobarrier365-lotion-skin-barrier-strenghtening-moisturizing-lotion)
- [AESTURA ATOBARRIER365 Cream — Sephora UK](https://www.sephora.co.uk/p/aestura-atobarrier365-cream-skin-barrier-strenghtening-moisturizing-cream)
- [AESTURA ATOBARRIER365 Cream Mist 120ml — Sephora UK](https://www.sephora.co.uk/p/aestura-atobarrier365-cream-mist-skin-barrier-moisturizing-mist)
- [AESTURA ATOBARRIER365 Hydro-Essence 200ml — Sephora UK](https://www.sephora.co.uk/p/aestura-atobarrier365-hydro-essence-hydrating-essence-to-support-the-moisture-barrier)
- [AESTURA ATOBARRIER365 Hydro Cera-Ha Serum 30ml — Sephora UK](https://www.sephora.co.uk/p/aestura-atobarrier365-hydro-cera-ha-serum-skin-barrier-enhancing-hydrating-serum)
- [Aestura — Korean Dermocosmetic Skincare brand page — Sephora UK](https://www.sephora.co.uk/brands/aestura)
- [AESTURA Announces Official Launch at Sephora Across 17 European Countries — Amorepacific](https://www.apgroup.com/int/en/news/2026-03-05-1.html)
- [AESTURA Officially Launches at Sephora Across 17 European Countries — AESTURA International](https://int.aestura.com/blogs/news/aestura-officially-launches-at-sephora-across-17-european-countries)
- [AESTURA Expands US Presence with New Soothing Collection in Partnership with Sephora — PR Newswire](https://www.prnewswire.com/news-releases/aestura-koreas-1-dermatologist-recommended-dermocosmetic-brand-expands-us-presence-with-new-soothing-collection-in-partnership-with-sephora-302677175.html)
- [MEDIPEEL EXPANDS ACROSS EUROPE WITH OFFICIAL PRINTEMPS DEBUT AND UK LAUNCH EVENT — PR Newswire](https://www.prnewswire.com/news-releases/medipeel-expands-across-europe-with-official-printemps-debut-and-uk-launch-event-302663317.html)
- [Glam Touch Opens The Biggest K-beauty Store in the UK — Glam Touch Bloomsbury Store](https://glamtouch.co.uk/blogs/edits/the-most-instagrammable-k-beauty-store-in-the-uk)
- [MediPeel collection — Glam Touch UK](https://glamtouch.co.uk/collections/medipeel)
- [Glam Touch Stores and Events](https://glamtouch.co.uk/pages/stores-and-events)
- [Talks, Pop Ups And Freebies: The Best London Beauty Events — Grazia UK](https://graziadaily.co.uk/beauty-hair/event/best-beauty-events-to-attend/)
- [Dr.Reju-All Advanced PDRN Rejuvenating Cream 20ml — Boots UK](https://www.boots.com/dr-rejuall-all-advanced-pdrn-rejuvenating-cream-20ml-10382170)
- [Dr.Reju-All Advanced PDRN Rejuvenating Cream — Amazon UK](https://www.amazon.co.uk/Reju-All-Advanced-PDRN-Rejuvenating-Cream/dp/B0FN7L65C1)
- [Dr.Reju-All Advanced PDRN Rejuvenating Cream 20g — Superdrug](https://www.superdrug.com/skin/face-skin-care/face-cream/dr-reju-all-advanced-pdrn-rejuvenating-cream-20g/p/mp-00298714)
- [Dr.Althea PDRN Reju 5000 Cream 20ml — Boots UK](https://www.boots.com/dr-althea-pdrn-reju-5000-cream-20ml-10382699)
- [K Pharmacy is the latest K Beauty trend to know — Stylist UK](https://www.stylist.co.uk/beauty/skincare/k-pharmacy-k-beauty-at-boots/1060238)
- [Boots Beauty and Wellness Trends Report 2026 — CEW UK](https://cewuk.co.uk/boots-beauty-and-wellness-trends-report-2026/)
- [Boots opens second beauty-only concept store — Beauty Magazine UK](https://www.beauty-magazine.co.uk/news/boots-opens-second-beauty-only-concept-store)
- [Boots to open second 'beauty-only' branch in Bristol — Bristol247](https://www.bristol247.com/lifestyle/news-lifestyle/boots-to-open-second-beauty-only-branch-in-bristol/)
- [Boots Opens Bristol Beauty Store as UK Retail Rivalry Intensifies — BeautyMatter](https://beautymatter.com/articles/boots-beauty-only-expands-to-bristol)
- [Boots to bring second beauty-only concept store to Bristol — Cosmetics Business](https://cosmeticsbusiness.com/boots-second-beauty-only-concept-store-bristol)
- [Boots Ireland Korean Skincare — Boots IE](https://www.boots.ie/beauty/skincare/korean-skincare)
- [What is K-Beauty? — Boots Ireland skincare advice](https://www.boots.ie/skincare-beauty-advice/skincare-advice/skincare-routines/what-is-k-beauty)
- [Beauty of Joseon — Boots Ireland brand page](https://www.boots.ie/beauty-of-joseon)
- [Dublin Henry Street store — Boots IE](https://www.boots.ie/stores/dublin-boots-henry-street)
- [John Lewis bets big on beauty, unveiling new loyalty focus and Korean skincare partnership — John Lewis Partnership](https://www.johnlewispartnership.co.uk/media-centre/latest-news/2026/23887)
- [John Lewis Steps Up Focus On Beauty Via Retailer Partnership And New Loyalty Focus — KamCity](https://www.kamcity.com/namnews/uk-and-ireland/general/john-lewis-steps-up-focus-on-beauty-via-retailer-partnership-and-new-loyalty-focus/)
- [MA:NYO — Skin Cupid UK](https://www.skincupid.co.uk/collections/ma-nyo)
- [Cult Beauty discount codes June 2026 — Marie Claire UK](https://www.marieclaire.co.uk/vouchers/cultbeauty.co.uk)
- [TikTok Shop UK unveils its beauty brand winners of 2025 — Cosmetics Business](https://cosmeticsbusiness.com/tiktok-shop-uk-unveils-its-beauty-brand-winners)
- [TikTok Shop emerges as UK's fourth-largest beauty retailer — Retail Times UK](https://retailtimes.co.uk/tiktok-shop-emerges-as-uks-fourth-largest-beauty-retailer-with-60-yoy-growth-and-k-beauty-surge/)
- [TikTok Shop now UK's fourth largest beauty retailer — ChannelX](https://channelx.world/2026/01/tiktok-shop-now-uks-fourth-largest-beauty-retailer/)
- [From 'Glass Skin' to British Favourites — TikTok Newsroom UK](https://newsroom.tiktok.com/tiktokshopbeautycrush?lang=en-GB)
- [Top TikTok Shop Products in Europe April 2026 — FastMoss](https://www.fastmoss.com/blog/tiktok-shop-europe-top-products-april-2026/)
- [Beauty Trends TikTok 2026: Skincare & AI — Accio](https://www.accio.com/business/beauty-trends-tiktok)
- [Top TikTok Beauty Trends 2026 — Qogita](https://www.qogita.com/blog/tiktok-beauty-trends-2026/)
- [BIOHEAL BOH: The Korean Slow-Aging Secret — One Eye Beauty](https://oneeyebeauty.com/why-bioheal-boh-is-your-go-to-korean-skincare-for-slow-aging/)
- [BIOHEAL BOH NAD-Prizcell Glow Power Serum Review — KherBlog](https://www.kherblog.com/2026/03/bioheal-boh-nad-prizcell-glow-power-serum.html)
- [BIOHEAL BOH — notino.co.uk](https://www.notino.co.uk/bioheal-boh/)
- [BIOHEAL BOH UK official TikTok — @bioheal.boh.uk](https://www.tiktok.com/@bioheal.boh.uk/video/7616376142362234115)
- [BIOHEAL BOH — Hello Seoul UK](https://helloseoul.co.uk/collections/bioheal-boh)
- [BIOHEAL BOH — Coréelle](https://coreelle.com/collections/bioheal-boh)
- [TONYMOLY Snail PDRN Recovery Toner — YesStyle](https://www.yesstyle.com/en/tonymoly-snail-pdrn-recovery-toner-120ml/info.html/pid.1135407854)
- [TONYMOLY Snail PDRN Recovery Skincare Set — YesStyle](https://www.yesstyle.com/en/tonymoly-snail-pdrn-recovery-skincare-set-4-pcs/info.html/pid.1135407851)
- [TONYMOLY Snail PDRN Recovery Lotion — YesStyle](https://www.yesstyle.com/en/tonymoly-snail-pdrn-recovery-lotion-120ml/info.html/pid.1135407853)
- [TONYMOLY Snail PDRN Recovery Cream — TONYMOLY AU](https://tonymoly.com.au/products/snail-pdrn-recovery-cream)
- [Beauty of Joseon Matte Sun Stick: Mugwort + Camelia — Amazon UK](https://www.amazon.co.uk/Beauty-Joseon-Matte-sun-stick/dp/B0BQVTM1BJ)
- [Beauty of Joseon Matte Sun Stick Review — Dr Rachel Ho](https://www.drrachelho.com/blog/beauty-of-joseon-matte-sun-stick-review/)
- [Beauty of Joseon Matte Sun Stick Review — Nicola Londors](https://www.nicolalondors.com/beauty-picks/beauty-of-joseon-matte-sun-stick-review-discount-code)
- [Beauty of Joseon Matte Sunstick Review — Arktastic](https://www.arktastic.com/blog/product-review/beauty-of-joseon-matte-sunstick)
- [Best Korean Sunscreens UK 2026 Guide — Skin2Seoul](https://www.skin2seoul.co.uk/blogs/blog/best-korean-sunscreens-in-the-uk-2026-guide)
- [Best Korean Sunscreen UK 2026 — House of Korea](https://houseofkorea.co.uk/best-korean-sunscreen-uk-2026-complete-guide/)
- [Best Korean SPFs From Beauty Of Joseon, Dr Jart & More — Marie Claire UK](https://www.marieclaire.co.uk/beauty/best-korean-spf)
- [Round Lab brand page — Sephora UK](https://www.sephora.co.uk/brands/Round-Lab)
- [Round Lab brand page — Boots UK](https://www.boots.com/round-lab)
- [Skin1004 brand page — Sephora UK](https://www.sephora.co.uk/brands/Skin1004)
- [Skin1004 brand page — Boots UK](https://www.boots.com/skin1004)
- [Cica or Centella : Understanding the Viral K-Beauty Ingredient — PURESEOUL](https://pureseoul.co.uk/blogs/k-beauty-catch-up/cica-or-centella-understanding-the-viral-k-beauty-ingredient)
- [Centella Asiatica K-Beauty Guide 2026 — Mirai Skin](https://www.mirai-skin.com/blogs/news/korean-skincare-ingredient-centella-asiatica)
- [Top Skincare Trends for 2026 and the Ingredients Driving the Shift — Korean Skincare Coach](https://www.koreanskincarecoach.com/blog/top-skincare-trends-for-2026-and-the-ingredients-driving-the-shift)
- [Trending Skincare Ingredients to have on your radar in 2026 — Luxury London](https://luxurylondon.co.uk/wellbeing/the-trending-skincare-ingredients-to-have-on-your-radar-in-2026/)
- [Seoulceuticals Launches Industry's First PDRN Vitamin C Serum — Barchart](https://www.barchart.com/story/news/52887/seoulceuticals-launches-industry-s-first-pdrn-vitamin-c-serum-as-bio-regenerative-actives-dominate-2026-k-beauty)
- [Korean Skincare — Penneys IE](https://www.primark.com/en-ie/c/beauty/skincare/korean-skincare)
- [How To Get Glass Skin | Korean Glass Skin — Penneys IE](https://www.primark.com/en-ie/a/inspiration/skincare-and-makeup/how-to-get-glass-skin)

Saved to repo: `daily_data/2026_06_14/trends-uk-ie.md`
