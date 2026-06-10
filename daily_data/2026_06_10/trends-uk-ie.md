# K-Beauty Google Trends — UK & Ireland — 2026-06-10

> **DATA QUALITY — read first.** Day 4 of the `trends.google.com` block. `pytrends.TrendReq` constructs cleanly (urllib3<2 pin held) but every `interest_over_time()` call returns `ResponseError: 403`. Direct `curl` to `trends.google.com`, `wikimedia.org`, and `en.wikipedia.org` all return `HTTP/2 403 x-deny-reason: host_not_allowed`. **No numerical UK/IE Google-Trends values were captured this cycle.** `WebSearch` remains the only working web-side signal in the container; UK avg / IE avg columns hold a qualitative `+`/`=`/`−`/`n/a` triage sampled from UK/IE trade press + retail announcements, NOT a 0–100 Trends index. See `## Data quality` for the full diagnosis and the escalation status. **Day 4 of the fade clock — Centellian24 FADED today (no fresh UK signal); Yepoda survives (fresh Sephora UK exclusive bundle confirmed).** The headline retail signal in today's sample is the **John Lewis × Skin Cupid 20-brand K-beauty shop-in-shop programme** launching Cambridge / Kingston / Leeds this summer — single biggest UK K-beauty retail event in this routine to date, and an explicit "Korean skincare searches +800% YoY on John Lewis" figure.

## Tracking distribution
BASE: 23 / CARRY-FORWARD: 18 / NEW: 4

- BASE brands (14): medicube, Dr.Melaxin, d'Alba, COSRX, Beauty of Joseon, AXISY, mixsoon, INKEY List, Wonderskin, Halara, Numbuzin, Anua, VT, Purito
- BASE categories (9): Korean skincare, k-beauty, glass skin, tiktok skincare, kbeauty haul, well ageing, skin longevity, PDRN, NAD+
- CARRY-FORWARD brands (9):
  - Day 4 of fade clock (origin 2026-06-07): Round Lab, SKIN1004, Biodance, Laneige, TIRTIR, HaruHaru Wonder, Yepoda *(Centellian24 FADED — see Faded section)*
  - Day 2 (origin 2026-06-08): BIOHEAL BOH, Mediheal
- CARRY-FORWARD categories / ingredients (9):
  - Day 4 (origin 2026-06-07): snail mucin, rice toner, skin barrier
  - Day 2 (origin 2026-06-08): spicules, exosome
  - Day 1 (origin 2026-06-09 — promoted from NEW): hanbang, ectoin, polyglutamic acid, glazed donut skin
- NEW today (4 — required ≥3):
  1. **Korean bodycare** (category) — Marie Claire UK headlines the segment as "the next natural progression in the UK's K-beauty scene" — glass-skin-all-over, body-barrier care, PHA exfoliation, PDRN + bamboo + ceramides. Distinct from base "Korean skincare" because it is a body-not-face SKU lane (KP, body acne, neck-décolletage anti-ageing). Maps directly to summer-shorts / sleeveless IE 18-34 demand window.
  2. **Korean lash lift** (adjacent treatment category) — **+20,082% YoY UK Fresha booking searches** — the single biggest velocity number this routine has ever logged, per Parlor Beauty / NewBeauty / Refinery29 UK / The London Brow Company. Topped Fresha's 2026 in-demand-treatment list. Tracked because IE 18-34 treatment-spend bleeds into the K-skincare creator feed (same audience, same salons).
  3. **azelaic acid** (ingredient) — Fresha 2026 #2 trend: **60,500 average monthly UK searches, +49% YoY**. Anti-inflammatory + antibacterial + exfoliating; positioned as the dermatologist-coded ingredient pivot for rosacea-prone / sensitive-skin audiences. Adjacent to but distinct from K-beauty's barrier-first vocabulary.
  4. **Manyo** (brand — Manyo Factory) — one of the 20 brands in the **John Lewis × Skin Cupid** shop-in-shop launch (Beauty of Joseon, Medicube, Anua, Unove, Manyo, S.Nature, Dr Different among the named cohort). Already has a UK Facebook + Instagram presence (`@manyofactory.uk`). Selected over Unove / Dr Different / S.Nature because it has the highest existing UK creator-side surface area heading into the shop-in-shop opening.

## Brands (last 7 days)

*UK avg / IE avg columns hold qualitative signal (`+` rising, `=` flat, `−` falling, `n/a` no signal). They are NOT Google-Trends 0–100 indices — they are a `WebSearch` triage. Replace with pytrends values the moment the policy is loosened.*

| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| medicube | BASE | + | + | + | rising HARD — **named in the John Lewis × Skin Cupid 20-brand shop-in-shop cohort** (Cambridge / Kingston / Leeds, this summer); AGE-R device + PDRN Pink Peptide Serum continues to anchor UK-viral K-device pair |
| Dr.Melaxin | BASE | = | n/a | = | flat (no fresh UK/IE press hit today) |
| d'Alba | BASE | n/a | n/a | n/a | no fresh signal |
| COSRX | BASE | = | = | = | flat (still cited as the K-beauty benchmark in UK trade press) |
| Beauty of Joseon | BASE | + | + | + | rising — **named in the John Lewis × Skin Cupid cohort**; remains the "default" K-brand in IE coverage; reinforces Hello! UK 2026 prediction |
| AXISY | BASE | n/a | n/a | n/a | no fresh signal |
| mixsoon | BASE | = | n/a | = | flat — no fresh hit today (Ulta US listing logged yesterday still holds) |
| INKEY List | BASE | n/a | n/a | n/a | UK-origin brand, off-thesis — no fresh K-beauty-context hit |
| Wonderskin | BASE | n/a | n/a | n/a | no fresh signal |
| Halara | BASE | n/a | n/a | n/a | apparel, off-thesis |
| Numbuzin | BASE | = | n/a | = | flat (US Target listing — no UK launch announcement found today) |
| Anua | BASE | + | + | + | rising — **named in the John Lewis × Skin Cupid cohort**; remains the IE heart-leaf-toner anchor |
| VT | BASE | + | + | + | rising — Reedle Shot 300 continues as the established UK liquid-microneedling entry-point product (the consumer-facing wrapper for the spicules trend) |
| Purito | BASE | = | n/a | = | flat |
| Round Lab | CARRY-FORWARD (Day 4) | = | n/a | = | flat — Birch Juice Sun Cream remains in Seoul Sister Olive Young top-10; no fresh UK editorial signal today. **NOT faded** but on watch — Day 5 must produce fresh UK signal |
| SKIN1004 | CARRY-FORWARD (Day 4) | = | n/a | = | flat — Sephora UK Skin1004 brand page remains live; no fresh editorial hit today. **NOT faded** |
| Biodance | CARRY-FORWARD (Day 4) | + | + | + | rising — **Bio-Collagen Real Deep Mask Pack named in Qogita TikTok-trends-2026 round-up as "blowing up on TikTok" with probiotics + collagen + "glass skin glow in just one use"**; UK-TikTok-native demand signal. **NOT faded** |
| Laneige | CARRY-FORWARD (Day 4) | + | + | + | rising — Hello! UK 2026 prediction + Boots IE consistently stocks Lip Sleeping Mask; **NOT faded** |
| TIRTIR | CARRY-FORWARD (Day 4) | = | n/a | = | thin — Ulta US launch + Boots UK 2025 stock per ChannelX retro still in scope; no fresh UK hit today. **NOT faded** but on watch — Day 5 must produce fresh UK signal |
| HaruHaru Wonder | CARRY-FORWARD (Day 4) | = | n/a | = | flat-positive — Glossy $360M → $600M FY26 target still in scope; no fresh UK hit today. **NOT faded** |
| Yepoda | CARRY-FORWARD (Day 4) | + | n/a | + | rising — **Sephora UK launched an exclusive "K-Beauty Icons Set" 5-product bundle at £40 (per missboux.com Sephora UK 2026 promo)**; this is fresh UK retail signal, not just a brand-page listing. Off-watch and **NOT faded** — promoted from "thin signal — watch" back to active CF |
| BIOHEAL BOH | CARRY-FORWARD (Day 2) | + | n/a | + | rising — TikTok Shop UK trial cohort still in scope; positioned as Olive Young's anti-ageing TikTok Shop UK beachhead |
| Mediheal | CARRY-FORWARD (Day 2) | + | + | + | rising HARD — PDRN Lifting Pad currently "temporarily unavailable" online at Boots UK (sell-through evidence); Boots Ireland brand page live at `boots.ie/mediheal`; the launch-week 4/6-SKUs-sold-out-in-3-days story still leading UK trade press. **First confirmed evidence of UK Boots online stock-out in this routine** |
| Manyo | NEW | + | n/a | + | rising — **named in the John Lewis × Skin Cupid 20-brand shop-in-shop cohort**; has a dedicated UK Facebook + Instagram presence (`@manyofactory.uk`); the cleanest under-tracked NEW brand for the IE 18-34 audience |

## Categories (last 7 days)
| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| Korean skincare | BASE | + | + | + | rising HARD — **"Korean skincare" searches +800% YoY on John Lewis specifically** per John Lewis partnership press release; Boots reports 5× sales growth + "a Korean skincare product selling every 11 seconds" still in scope |
| k-beauty | BASE | + | + | + | rising — TikTok Shop UK 125% K-Beauty search surge still in scope; John Lewis × Skin Cupid event is the new UK retail-distribution anchor |
| glass skin | BASE | + | + | + | rising — Marie Claire UK Korean-bodycare piece explicitly cites "glass skin all over" as the body-extension thesis; glazed-donut hashtag remains the consumer-facing synonym |
| tiktok skincare | BASE | + | + | + | rising — TikTok Shop is the UK's 4th-largest beauty retailer; Qogita 2026 round-up still cites Biodance + heartleaf toner as TikTok-driven K-beauty viral products |
| kbeauty haul | BASE | = | = | = | flat (steady creator-side format, no inflection) |
| well ageing | BASE | = | n/a | = | flat — continues to lose share-of-voice to "skin longevity" + "hanbang 2.0" as 2026 umbrella terms |
| skin longevity | BASE | + | + | + | rising — Marie Claire UK Korean-bodycare piece extends longevity framing from face → "premature ageing of the neck and décolletage"; Olive Young 2026 trend report still in scope |
| PDRN | BASE | + | + | + | rising — Boots Ireland Mediheal PDRN Lifting Pad still live; **Boots UK own-brand "Boots Hydrating PDRN Serum 30ml" now indexed on boots.com** — first time the routine has logged a UK-retailer OWN-LABEL PDRN SKU. Signals PDRN has moved from imported viral ingredient → UK retail private-label commodification |
| NAD+ | BASE | n/a | n/a | n/a | no fresh K-beauty-context hit today (NAD+ coverage remains wellness-side) |
| snail mucin | CARRY-FORWARD (Day 4) | = | = | = | flat-positive — perennial UK staple, still in COSRX cohort; **NOT faded** |
| rice toner | CARRY-FORWARD (Day 4) | = | + | + | rising in IE — Penneys PS… K-Beauty Cica + Niacinamide rice toner from SS26 preview still rolling out; **NOT faded** |
| skin barrier | CARRY-FORWARD (Day 4) | + | + | + | rising — Marie Claire UK Korean-bodycare piece explicitly extends "body barrier care" framing; remains the IE 18-34 gateway term. **NOT faded** |
| spicules | CARRY-FORWARD (Day 2) | + | n/a | + | rising — held the +119% YoY (spicule skincare) / +535% YoY (liquid microneedling) UK search velocity from yesterday; Parlor Beauty / Marie Claire UK / NBC Select / Mamabella UK still publishing |
| exosome | CARRY-FORWARD (Day 2) | + | n/a | + | rising — paired with PDRN as the 2026 dual-active in Seoul derm protocols; UK trade press positioning as PDRN's sibling |
| hanbang | CARRY-FORWARD (Day 1) | + | n/a | + | rising — Hello! UK + TheIndustry.beauty + Cosmetics Business 4-predicted-K-trends piece all leading with "modernised hanbang"; ginseng + mugwort + bamboo sap is the named ingredient trio; Brit + Co confirms as #1 of the 8 K-beauty trends for 2026 |
| ectoin | CARRY-FORWARD (Day 1) | + | n/a | + | rising — flagged as "hottest emerging ingredient" by Korean Skincare Coach; NBC Select sensitive-skin explainer; hybrid humectant + barrier-protect → maps to the IE 18-34 barrier-first thesis |
| polyglutamic acid | CARRY-FORWARD (Day 1) | + | n/a | + | rising — VITA 2026 ingredient edit + Korean Skincare Coach 2026 predictions; SkinSort 10-best PGA treatments listing — consumer-discovery infrastructure already in place |
| glazed donut skin | CARRY-FORWARD (Day 1) | + | + | + | rising — `#glazeddonutskin` >1.8M TikTok views per Kiehl's editorial; consumer-facing TikTok-native synonym for "glass skin" |
| Korean bodycare | NEW | + | + | + | rising — **Marie Claire UK leads with "the next natural progression in the UK's K-beauty scene is a new category entirely: Korean bodycare"**; body barrier care, PHA exfoliation, PDRN + bamboo + ceramides; KP / body-acne / neck-décolletage anti-ageing the named SKU lanes |
| Korean lash lift | NEW | + | n/a | + | rising HARD — **+20,082% YoY UK Fresha booking searches** (single biggest velocity number this routine has logged); topped Fresha 2026 in-demand-treatment list per Parlor Beauty + NewBeauty + Refinery29 UK + The London Brow Company; adjacent to skincare via "Korean routines + hydrating serum" frame |
| azelaic acid | NEW | + | n/a | + | rising — **60,500 avg monthly UK searches, +49% YoY** per Fresha 2026 trend report; #2 trend behind Korean lash lift; anti-inflammatory + antibacterial + exfoliating; dermatologist-coded ingredient pivot for rosacea-prone / sensitive-skin audience |

## Faded / contradicted carry-forwards

- **Centellian24** — **FADED.** Day 4 of fade clock (origin 2026-06-07). Yesterday's note flagged "Day 4 must produce fresh UK signal or drop." Today's sample returned only the Centellian24 Madeca Matcha Toning Peeling Gel "Best Peeling Gel" win at the **US** NewBeauty 16th Annual Beauty Awards 2026, no UK trade-press / UK retail-shelf hit. Dongkook Pharmaceutical's flagship line remains a strong KR brand on Olive Young but has not converted into UK retail / press surface area in this 4-day window. **Dropped from CARRY-FORWARD today.** Re-add as NEW only if a Boots UK / Sephora UK / John Lewis listing surfaces.

- **Yepoda — promoted off "watch" to active CF.** Yesterday flagged as thin signal pending Sephora UK editorial confirmation; today returned the Sephora UK exclusive K-Beauty Icons Set (5 products, £40) plus the missboux.com 2026 promo write-up. This is fresh UK retail signal (not just a brand-page listing). Stays as Day 4 CF, off watch.

No contradictions: nothing in today's sampling refutes a previously surfaced brand or category. PDRN moved further along the retail-commodification curve (Boots UK own-label PDRN serum now indexed on boots.com).

## Anomalies (>50% change)

- **Korean lash lift: +20,082% YoY UK Fresha booking searches** (Parlor Beauty / NewBeauty / Refinery29 UK) — single biggest velocity number this routine has logged. Not strictly a skincare term but adjacent enough that creator-side audiences overlap; flagged because the same IE 18-34 cohort that books salon treatments via Fresha is the K-skincare buyer.
- **Korean skincare +800% YoY searches on John Lewis specifically** (per John Lewis × Skin Cupid press release) — first time the routine has logged a single-retailer-search-volume figure; John Lewis explicitly tying the partnership to this number is the cleanest UK retail-side intent signal in the data set.
- **Spicules / liquid microneedling**: still holds +119% YoY (spicule skincare) and +535% YoY (liquid microneedling) UK search velocity. 38,000 UK monthly searches per Parlor Beauty. Carried unchanged from yesterday.
- **azelaic acid +49% YoY UK monthly searches** (60,500/mo) — Fresha 2026 #2 trend. Just under the >50% threshold but mentioned because the absolute UK search-volume number is the largest single-ingredient figure logged in this routine.
- **Mediheal PDRN Lifting Pad now showing as "temporarily unavailable" online at Boots UK** — implicit anomaly (no headline figure but the boots.com PDP no-stock state confirms the 4-of-6-SKUs-sold-out-in-3-days story has continued past the launch window).
- **TikTok Shop UK K-Beauty search +125%** and basket value ~35% above skincare average — carried forward unchanged (category-level anomaly the whole routine sits downstream of).
- *No other >50% movers in today's qualitative sample. Real anomaly detection resumes the moment pytrends is unblocked.*

## Notes for content strategy (IE 18-34 women)

1. **The John Lewis × Skin Cupid launch is the headline UK retail event to react to this week — and the IE-replication angle writes itself.** John Lewis is opening K-beauty shop-in-shops in Cambridge / Kingston / Leeds this summer with 20 brands (Beauty of Joseon, Medicube, Anua, Unove, Manyo, S.Nature, Dr Different the named cohort). John Lewis has no Irish presence, so the IE shoot angle is: *"the 20 K-brands UK shoppers are getting in John Lewis this summer — and where you can already buy them in Dublin"*. Pair each brand with its current Boots IE / Penneys IE / Sephora IE / Skin Cupid IE-shipping equivalent. This is the highest-priority shoot in today's sample because the news cycle is live AND IE-relevant (Irish viewers see the same UK press, want the same products, but don't have John Lewis).

2. **Korean bodycare is the SKU lane to film next — summer demand window is open NOW.** Marie Claire UK has now formally tagged Korean bodycare as the next UK K-beauty category, with explicit ingredient mapping (PDRN, bamboo, PHAs, ceramides, niacinamide, arbutin, tranexamic acid; KP, body-acne, neck-décolletage anti-ageing the named SKU lanes). IE 18-34 audience moves into sleeveless / shorts season through July–August. Pitch: a single 60-second piece — *"Glass skin from the neck down: the K-beauty body-care routine that lasts the summer"* — anchored on a body-PDRN SKU + a PHA body wash + a barrier-cream for KP. Pairs the NEW today term with PDRN (rising base) and skin barrier (Day 4 CF) — three rising terms in one shoot.

3. **Add Korean lash lift to the "treatment-adjacent" content lane — the velocity number is too big to ignore.** +20,082% YoY UK Fresha booking searches is the single biggest velocity figure this routine has ever logged; the IE 18-34 cohort that books Fresha treatments overlaps almost 1:1 with the K-skincare buyer. Format: a single explainer + before/after — *"The Korean lash lift Dublin salons are now offering — what it is, what it isn't, and the K-skincare aftercare that keeps it"* — close with a hyaluronic + glycerin serum (the Korean Skincare aftercare framing Parlor Beauty / The London Brow Company are already using).

4. **Centellian24 dropped today — re-allocate the slot to Manyo.** Centellian24 has now failed the 4-day UK signal test (only US NewBeauty award, no UK retail / UK press). Manyo is in the John Lewis × Skin Cupid 20-brand cohort, has a dedicated UK Facebook + Instagram presence, and is under-tracked by IE creators. First-mover window: a Manyo Galactomyces Niacinamide essence breakdown before the John Lewis Cambridge / Kingston / Leeds shop-in-shops open and UK creator-side discovery saturates.

## Data quality

**Status: PARTIAL — Google Trends fetch still blocked at the network-policy layer for the fourth consecutive day; qualitative `WebSearch` triage substituted again.**

Diagnosis (Day 4, unchanged from Day 3):
- `pytrends.TrendReq` constructs cleanly with `urllib3<2` (fix held).
- Single-keyword GB + IE `interest_over_time()` fetches both return `ResponseError: 403`.
- Direct `curl -sI -m 10 https://trends.google.com/trending/rss?geo=GB` → `HTTP/2 403`, `x-deny-reason: host_not_allowed`.
- Direct `curl` to `en.wikipedia.org` and `wikimedia.org` → same `HTTP/2 403 host_not_allowed`.
- `WebFetch` to `trends.google.com/trends/explore?...&geo=GB` → 403 at the network-policy layer.
- **`WebSearch` is unblocked** and was used today to triage UK/IE-press signal for each tracked keyword (John Lewis Partnership, Retail Bulletin, Retail Gazette, Retail Times, Retail Week, BeautyMatter, Global Cosmetics News, FashionNetwork, Cosmetics Business, Marie Claire UK, Hello! UK, TheIndustry.beauty, Parlor Beauty, NewBeauty, Refinery29 UK, The London Brow Company, missboux.com, Qogita, Beauty Geek UK, Brit + Co, Living360, Boots Ireland, Boots UK, Sephora UK, Mediheal). Same fallback as Day 3.

What that means for the table: UK avg / IE avg / Today-vs-7d-avg columns are a **qualitative** sample (`+`/`=`/`−`/`n/a`) sourced from `WebSearch`, **not** a Google-Trends 0–100 index. The bucket framework, the fade clock, and the anomaly column are still valid; cross-day velocity comparisons will not be quantitative until pytrends is unblocked.

Escalation status:
- **Day 4 of 403 → escalating.** Recommended action remains: open a session with the owner (Soomin) at https://code.claude.com/docs/en/claude-code-on-the-web and request the outbound network policy be loosened to allow `trends.google.com`, `news.google.com`, `wikimedia.org`, `reddit.com`. The "Standard" or "Custom" network policy on the environment is what controls this; the current policy is denying every relevant host with `host_not_allowed`. Without this, the routine has now been running on a qualitative proxy for 4/4 days.
- **Recommend formally re-scoping the routine** (file rename + briefing update) from "Google Trends UK & IE" → "K-Beauty UK/IE Demand Triage" until the policy lands. Today's deliverable is genuinely high-signal — the John Lewis × Skin Cupid event, the Korean bodycare category emergence, the Korean lash lift velocity number, the Centellian24 fade — but they are sourced from trade press + Fresha-volume + retailer announcements, not from Trends. Calling that "Google Trends data" is structurally misleading after 4 days.
- Worst-case substitute (continues to work): keep building on the `WebSearch` triage and pair it with `fastmoss_raw/` TikTok exports + Boots.ie / SkinShop.ie / John Lewis (when it opens) PDP review-count deltas. That gives the routine a usable demand proxy until the policy lands.

Tomorrow's run will: (a) re-attempt pytrends — if Day 5 of 403, formally re-scope this routine's name per the recommendation above; (b) advance the fade clock to Day 5 — Round Lab + TIRTIR are the two CF brands on watch and most at risk of being marked `faded` if they produce no fresh UK signal; (c) check if Manyo / Unove / Dr Different / S.Nature have any pre-launch UK editorial buzz now that the John Lewis × Skin Cupid cohort is public.

---

Sources sampled today (via `WebSearch`, all UK/IE-facing trade, consumer press, or retail announcements):

- [John Lewis bets big on beauty — John Lewis Partnership](https://www.johnlewispartnership.co.uk/media-centre/latest-news/2026/23887)
- [John Lewis steps up beauty push with Skin Cupid shop-in-shops — Retail Bulletin](https://www.theretailbulletin.com/health-and-beauty/john-lewis-steps-up-beauty-push-with-skin-cupid-shop-in-shops-29-04-2026/)
- [John Lewis unveils exclusive shop-in-shops Korean skincare partnership — Retail Gazette](https://www.retailgazette.co.uk/blog/2026/04/john-lewis-korean-skincare/)
- [John Lewis partners with Skin Cupid to expand Korean beauty offering in the UK — Global Cosmetics News](https://www.globalcosmeticsnews.com/john-lewis-partners-with-skin-cupid-to-expand-korean-beauty-offering-in-the-uk/)
- [John Lewis and Skin Cupid partner for exclusive Korean beauty launch — HPC MAG MEA](https://www.hpcmagmea.com/2026/05/04/john-lewis-and-skin-cupid-partner-for-exclusive-korean-beauty-launch/)
- [John Lewis Expands K-Beauty Through Skin Cupid Partnership — BeautyMatter](https://beautymatter.com/articles/skin-cupid-lands-major-uk-expansion-through-john-lewis-partnership)
- [Skin Cupid lands at John Lewis: a landmark moment for K-beauty in the UK — Retail Times](https://retailtimes.co.uk/skin-cupid-lands-at-john-lewis-a-landmark-moment-for-k-beauty-in-the-uk/)
- [Skin Cupid: The John Lewis beauty partner with ambitious expansion plans — Retail Week](https://www.retail-week.com/health-and-beauty/skin-cupid-the-john-lewis-beauty-partner-with-ambitious-expansion-plans/7051085.article)
- [John Lewis dives deeper into beauty — FashionNetwork](https://ww.fashionnetwork.com/news/John-lewis-dives-deeper-into-beauty-big-developments-and-skin-cupid-link-up,1828013.html)
- [K-Beauty Body Products Are Here: These Are The Best To Buy — Marie Claire UK](https://www.marieclaire.co.uk/beauty/k-beauty-body-products)
- [Korean Lash Lifts: The Most In Demand Beauty Treatment For 2026? — Parlor Beauty](https://parlorbeauty.co.uk/korean-lash-lifts-the-most-in-demand-beauty-treatment-for-2026/)
- [Korean Lash Lifts Are 2026's Gentler Lash Treatment Trend — NewBeauty](https://www.newbeauty.com/korean-lash-lifts/)
- [I Tried The Viral Korean Lash Lift — Refinery29 UK](https://www.refinery29.com/en-gb/korean-lash-lift-review)
- [5 Reasons Korean Lash Lifts Are Trending in UK Salons — The London Brow Company](https://londonbrowcompany.com/blogs/the-london-brow-company/korean-lash-lift-trend-uk-salons)
- [New Yepoda K-Beauty Icons Set at Sephora UK 2026 — missboux.com](https://www.missboux.com/new-yepoda-the-k-beauty-icons-set-at-sephora-uk-2026/)
- [YEPODA | Vegan Korean Skincare — Sephora UK](https://www.sephora.co.uk/brands/yepoda)
- [Top TikTok Beauty Trends 2026: What's Viral and Selling Now — Qogita](https://www.qogita.com/blog/tiktok-beauty-trends-2026/)
- [The K-beauty trends expected to explode in 2026 — Hello! UK](https://www.hellomagazine.com/hfm/beauty-trends/874525/k-beauty-trends-2026/)
- [4 predicted K-beauty trends for 2026 — Cosmetics Business](https://cosmeticsbusiness.com/4-predicted-k-beauty-trends-for-2026)
- [8 K-Beauty Trends & Products You'll Actually Use in 2026 — Brit + Co](https://www.brit.co/k-beauty/)
- [Mediheal — Boots Ireland](https://www.boots.ie/mediheal)
- [Mediheal PDRN Lifting Pad (100 pads) — Boots UK](https://www.boots.com/mediheal-pdrn-lifting-pad-170ml-100-pads-10382518)
- [Boots Hydrating PDRN Serum 30ml — Boots UK](https://www.boots.com/boots-pdrn-serum-30ml-10383077)
- [Mediheal brings K-beauty toner pads to Boots as UK demand surges — TheIndustry.beauty](https://theindustry.beauty/mediheal-brings-k-beauty-toner-pads-to-boots-as-uk-demand-surges/)
- [Mediheal Toner Pads (now at Boots) — Beauty Geek UK](https://beautygeekuk.com/2026/03/mediheal-toner-pads-now-at-boots.html)
- [Centellian24 — official site (Madeca Cream / TECA Technology)](https://centellian24.com/)
- [Manyo Factory UK — Facebook](https://www.facebook.com/manyofactory.uk/)
- [Manyo Factory UK — Instagram](https://www.instagram.com/manyofactory.uk/)
- [Sephora UK MD ramps up expansion plans: 20 UK stores by end of 2026 — Cosmetics Business](https://cosmeticsbusiness.com/sephora-uk-md-ramps-up-expansion-plans-20-stores-by-2026)

Saved to repo: `daily_data/2026_06_10/trends-uk-ie.md`
