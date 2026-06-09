# K-Beauty Google Trends — UK & Ireland — 2026-06-09

> **DATA QUALITY — read first.** Day 3 of the `trends.google.com` block. `pytrends.TrendReq` still constructs cleanly (urllib3<2 pin held), but every `interest_over_time()` call returns `ResponseError: 403`. Direct `urllib` to `trends.google.com/trending/rss?geo=GB`, `wikimedia.org/api/rest_v1/metrics/pageviews/...`, and `en.wikipedia.org/api/rest_v1/...` all return `HTTP Error 403`. `WebFetch` to the same hosts also 403s. **No numerical UK/IE Google-Trends values were captured this cycle.** `WebSearch` remains the only working web-side signal in the container; UK avg / IE avg columns hold a qualitative `+`/`=`/`−`/`n/a` triage sampled from UK/IE trade press + TikTok newsroom, NOT a 0–100 Trends index. See `## Data quality` for the full diagnosis and the fix path. **Day 3 of the carry-forward fade clock for the eight 2026-06-07-origin brands — no faded drops today; signal located for each.** Two carry-forward brands (Yepoda, Centellian24) downgraded to "thin signal — watch" status.

## Tracking distribution
BASE: 23 / CARRY-FORWARD: 15 / NEW: 4

- BASE brands (14): medicube, Dr.Melaxin, d'Alba, COSRX, Beauty of Joseon, AXISY, mixsoon, INKEY List, Wonderskin, Halara, Numbuzin, Anua, VT, Purito
- BASE categories (9): Korean skincare, k-beauty, glass skin, tiktok skincare, kbeauty haul, well ageing, skin longevity, PDRN, NAD+
- CARRY-FORWARD brands (10):
  - Day 3 of fade clock (origin 2026-06-07): Round Lab, SKIN1004, Biodance, Laneige, TIRTIR, HaruHaru Wonder, Centellian24, Yepoda
  - Day 1 of fade clock (promoted from NEW yesterday): BIOHEAL BOH, Mediheal
- CARRY-FORWARD categories / ingredients (5):
  - Day 3 (origin 2026-06-07): snail mucin, rice toner, skin barrier
  - Day 1 (promoted from NEW yesterday): spicules, exosome *(liquid microneedling logged as the consumer-facing search term that resolves to spicules — not a separate bucket entry)*
- NEW today (4 — required ≥3):
  1. **hanbang / "Hanbang 2.0"** (category) — Hello! UK and TheIndustry.beauty both led 2026 K-beauty predictions with "modernised hanbang formulas" as the umbrella term; pairs traditional ginseng / mugwort / bamboo sap with peptide + encapsulation tech. Distinct from "Korean skincare" — it is the heritage / longevity-coded retail tag UK trade press is now using.
  2. **ectoin** (ingredient) — Korean Skincare Coach lists ectoin as "one of the hottest emerging ingredients in Korean skincare right now and you're going to see a lot more of it in 2026". A hybrid humectant + barrier-protective extremolyte molecule; positioned as the sensitive-skin pivot for the barrier-repair audience.
  3. **polyglutamic acid (PGA)** (ingredient) — featured in Korean Skincare Coach + VITA's 2026 ingredient edit; holds 4× more moisture than hyaluronic acid; forms a breathable film layer that enhances any active layered underneath. Lines up cleanly behind the "glass skin" / hydration thesis.
  4. **glazed donut skin** (aesthetic category) — `#glazeddonutskin` >1.8M views on TikTok per Kiehl's editorial; the "milky / honeyed" finish vernacular is being used interchangeably with "glass skin" by UK creators and is the consumer-friendly tag for the same goal state. Worth tracking as a TikTok-native synonym for glass skin in IE creator content.

## Brands (last 7 days)

*UK avg / IE avg columns hold qualitative signal (`+` rising, `=` flat, `−` falling, `n/a` no signal). They are NOT Google-Trends 0–100 indices — they are a `WebSearch` triage. Replace with pytrends values the moment the policy is loosened.*

| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| medicube | BASE | + | + | + | rising (AGE-R device + PDRN Pink Peptide Serum still the most-cited UK-viral K-device pair; Ulta US launch reinforces global retail thesis) |
| Dr.Melaxin | BASE | = | n/a | = | flat (no fresh UK/IE press hit today) |
| d'Alba | BASE | n/a | n/a | n/a | no fresh signal |
| COSRX | BASE | = | = | = | flat (still cited as the K-beauty benchmark in UK trade press) |
| Beauty of Joseon | BASE | + | + | + | rising (named in Hello! UK as a 2026 explosion brand alongside Laneige + Anua; remains the "default" K-brand in IE coverage) |
| AXISY | BASE | n/a | n/a | n/a | no fresh signal |
| mixsoon | BASE | + | n/a | + | rising (cited again in TikTok Shop UK cohort; Ulta US launch confirms cross-Atlantic distribution thesis) |
| INKEY List | BASE | n/a | n/a | n/a | UK-origin brand, off-thesis — no fresh K-beauty-context hit |
| Wonderskin | BASE | n/a | n/a | n/a | no fresh signal |
| Halara | BASE | n/a | n/a | n/a | apparel, off-thesis |
| Numbuzin | BASE | = | n/a | = | flat (US Target listing — no UK launch announcement found today) |
| Anua | BASE | + | + | + | rising (named alongside Laneige + BOJ in Hello! UK 2026 K-beauty predictions; remains the IE heart-leaf-toner anchor) |
| VT | BASE | + | + | + | rising (Reedle Shot 300 named in Parlor Beauty as the established UK liquid-microneedling entry-point product — the consumer-facing wrapper for the spicules trend) |
| Purito | BASE | = | n/a | = | flat |
| Round Lab | CARRY-FORWARD (Day 3) | = | n/a | = | flat-positive — Birch Juice Sun Cream named in Seoul Sister's March 2026 Olive Young top-10; **NOT faded** — signal located, stays for Day 4 review |
| SKIN1004 | CARRY-FORWARD (Day 3) | = | n/a | = | flat-positive — Madagascar Centella line named in Seoul Sister Olive Young top-10 + Sephora UK K-beauty section; **NOT faded** |
| Biodance | CARRY-FORWARD (Day 3) | = | n/a | = | flat — Sephora US launch + active TikTok Shop SKU page (`Bio-Collagen Real Deep Mask` still circulating); **NOT faded** (was 0/0 yesterday — Day 3 broke the streak) |
| Laneige | CARRY-FORWARD (Day 3) | + | + | + | rising (named in Hello! UK 2026 predictions + Boots IE consistently stocks Lip Sleeping Mask; **NOT faded**) |
| TIRTIR | CARRY-FORWARD (Day 3) | = | n/a | = | thin — Ulta US launch + Boots UK stock per ChannelX retro of 2025; **NOT faded** but watch (no fresh UK-press hit today specifically) |
| HaruHaru Wonder | CARRY-FORWARD (Day 3) | = | n/a | = | flat-positive — Glossy reports $360M → $600M FY2026 target (60% YoY) driven by digital + international + brick-and-mortar; **NOT faded** |
| Centellian24 | CARRY-FORWARD (Day 3) | = | n/a | = | thin — Madeca Cream named in Seoul Sister Olive Young top-10 (KR-side); no UK-press hit today. **NOT faded but downgraded to watch** — Day 4 must produce fresh UK signal or drop |
| Yepoda | CARRY-FORWARD (Day 3) | = | n/a | = | thin — Sephora UK K-beauty section listing; no fresh editorial / sales signal. **NOT faded but downgraded to watch** — Day 4 must produce fresh UK signal or drop |
| BIOHEAL BOH | CARRY-FORWARD (Day 1) | + | n/a | + | rising (TikTok Shop UK trial cohort confirmed in Cosmetics Business; positioned as Olive Young's anti-ageing TikTok Shop UK beachhead) |
| Mediheal | CARRY-FORWARD (Day 1) | + | + | + | rising HARD (Boots Ireland posted PDRN Lifting Pad launch video on Facebook Official; UK launch hit "4 out of 6 SKUs sold out in 3 days" per TheIndustry.beauty / Beauty Geek; **first explicit Boots IE signal for the PDRN line in this routine**) |

## Categories (last 7 days)
| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| Korean skincare | BASE | + | + | + | rising — Boots reports 5× sales growth, "a Korean skincare product selling every 11 seconds"; LookFantastic search volume tripled YoY → +174% category revenue |
| k-beauty | BASE | + | + | + | rising — TikTok Shop UK reports 125% K-Beauty search surge; basket value ~35% above skincare average |
| glass skin | BASE | + | + | + | rising — still the headline frame in TikTok Newsroom UK; glazed-donut hashtag (1.8M views) is the consumer-facing synonym |
| tiktok skincare | BASE | + | + | + | rising — TikTok Shop is now the UK's 4th-largest beauty retailer per ChannelX retro |
| kbeauty haul | BASE | = | = | = | flat (steady creator-side format, no inflection) |
| well ageing | BASE | = | n/a | = | flat — losing share-of-voice to "skin longevity" + "hanbang 2.0" as 2026 umbrella terms |
| skin longevity | BASE | + | + | + | rising — still framed as the umbrella term in Olive Young's 2026 trend report and TheIndustry.beauty K-beauty 2026 predictions |
| PDRN | BASE | + | + | + | rising — confirmed by Boots Ireland's own PDRN Lifting Pad announcement video; PDRN is now retail-shelf reality in IE, not just press buzz |
| NAD+ | BASE | n/a | n/a | n/a | no fresh K-beauty-context hit today (NAD+ coverage remains wellness-side) |
| snail mucin | CARRY-FORWARD (Day 3) | = | = | = | flat-positive — perennial UK staple, still in COSRX cohort; **NOT faded** |
| rice toner | CARRY-FORWARD (Day 3) | = | + | + | rising in IE — Penneys PS… K-Beauty Cica + Niacinamide rice toner from SS26 preview continues to roll out; **NOT faded** |
| skin barrier | CARRY-FORWARD (Day 3) | + | + | + | rising — Hello! UK + TheIndustry.beauty both lead 2026 predictions on barrier-first products with fermented ceramides; remains the IE 18-34 gateway term. **NOT faded** |
| spicules | CARRY-FORWARD (Day 1) | + | n/a | + | rising — Parlor Beauty / Marie Claire UK / NBC / Mamabella UK / Get the Gloss all still actively publishing; "liquid microneedling" search +535% YoY, 38,000 UK searches last month |
| exosome | CARRY-FORWARD (Day 1) | + | n/a | + | rising — paired with PDRN as the 2026 dual-active in Seoul derm protocols per Korean Skincare Coach + GreyB; UK trade press positioning as PDRN's sibling |
| hanbang | NEW | + | n/a | + | rising — Hello! UK + TheIndustry.beauty + K-Trend + KnokGlobal + Coveteur all leading 2026 trend pieces with "Hanbang 2.0"; ginseng + mugwort + bamboo sap is the named ingredient trio |
| ectoin | NEW | + | n/a | + | rising — flagged as "hottest emerging ingredient" by Korean Skincare Coach; NBC Select wrote a long-form ectoin sensitive-skin explainer; hybrid humectant + barrier protect → maps to the IE 18-34 barrier-first thesis |
| polyglutamic acid | NEW | + | n/a | + | rising — VITA 2026 ingredient edit + Korean Skincare Coach 2026 predictions name PGA; SkinSort listing 10 best PGA treatments / moisturizers of 2026 → consumer-discovery infrastructure already in place |
| glazed donut skin | NEW | + | + | + | rising — Kiehl's editorial: `#glazeddonutskin` >1.8M TikTok views; the consumer-facing tag for the same goal state as "glass skin", more native to TikTok-led IE 18-34 audience |

## Faded / contradicted carry-forwards

**None dropped this cycle.** Day 3 of the 3-day fade clock for the eight 2026-06-07-origin carry-forward brands has produced at least secondary signal for every one of them — including the five (Biodance, TIRTIR, HaruHaru Wonder, Centellian24, Yepoda) that returned no fresh hit yesterday. Detail:

- **Biodance** — broke the 0/0 streak via Sephora US launch confirmation + active TikTok Shop product listing. Not retail-fresh in UK/IE but globally alive. Stays.
- **TIRTIR** — Ulta US launch + Boots UK 2025 stock per ChannelX retro. Thin UK-fresh signal. Stays on watch.
- **HaruHaru Wonder** — Glossy: $360M → $600M FY2026 target. Healthy global momentum. Stays.
- **Centellian24** — Olive Young KR-side top-10 hit (Madeca Cream). No UK press hit. **Downgraded to watch — Day 4 (2026-06-10) must produce fresh UK signal or drop.**
- **Yepoda** — Sephora UK K-beauty section listing only. **Downgraded to watch — Day 4 must produce fresh UK signal or drop.**

No contradictions: nothing in today's sampling refutes a previously surfaced brand. PDRN's promotion to a Boots Ireland-shelf reality (vs. UK-only yesterday) is the strongest positive confirmation in the data set.

## Anomalies (>50% change)

- **PDRN at Boots Ireland (confirmed today)**: Mediheal's PDRN Lifting Pads have launched at Boots Ireland (Boots Ireland Facebook video). This converts the PDRN base-seed term from a UK-only retail story into a UK + IE retail story within ~30 days of the UK launch — the IE-specific replication window flagged in yesterday's note (2026-06-08 strategy note #2) materialised. Single biggest positive signal in today's data set for the IE-replication thesis.
- **Spicules / liquid microneedling**: holds the +119% YoY (spicule skincare) and +535% YoY (liquid microneedling) UK search velocity from yesterday — confirmed by Mamabella UK + NBC Select + Parlor Beauty publishing in the same cycle. 38,000 UK searches in the last month per Parlor Beauty. Still the largest single-trend velocity in the routine.
- **TikTok Shop UK K-Beauty search +125%** (per Cosmetics Business / Supply Chain Digital) and basket value ~35% above the platform-wide skincare average — a category-level anomaly that the entire routine is downstream of.
- **HaruHaru Wonder revenue ~+60% YoY ($360M → $600M FY26 target, per Glossy)** — brand-level financial anomaly that justifies keeping HaruHaru Wonder in the carry-forward bucket even without fresh UK editorial signal.
- *No other >50% movers in today's qualitative sample. Real anomaly detection resumes the moment pytrends is unblocked.*

## Notes for content strategy (IE 18-34 women)

1. **Boots IE PDRN replication has landed — pivot the Mediheal angle from "watch UK" to "they're here now".** Yesterday's note #2 flagged a 7-day window to confirm Mediheal PDRN sell-through on Henry Street; Boots Ireland have now posted the launch themselves. The scarcity-marketing pitch shifts from anticipation to active demand: "Boots UK sold out 4/6 SKUs in 3 days — here's how to find them in Dublin before the same thing happens here." This is the single highest-priority shoot to schedule this week — the news cycle is live.
2. **Spicules + glazed donut skin is the IE-native pair to lead with on TikTok.** "Glazed donut skin" is the consumer-facing tag (1.8M hashtag views) that IE 18-34 actually search for; "spicules / liquid microneedling" is the ingredient story that drives the finish. Pitch: a single 60-second piece — "How to get glazed donut skin without a £200 clinic appointment" — using VT Reedle Shot 300 as the hero product (named in Parlor Beauty as the established UK entry point) and PGA / polyglutamic acid as the layer-it-over finishing step. Pairs two NEW today terms with two rising base / CF terms, all in one shoot.
3. **Add ectoin to the "sensitive skin / barrier" content lane before the rest of IE creator-side catches up.** Ectoin maps directly onto the existing "skin barrier" / "rice toner" / "Anua heart-leaf" rotation that already serves IE 18-34, but it is described as "the hottest emerging ingredient" with NO dominant IE creator on it yet. Six-week head-start window. Format: a single explainer ("the desert molecule that's replacing niacinamide for reactive skin") before the trend reaches Boots IE shelves.
4. **Hanbang 2.0 is the heritage-coded narrative to reserve for autumn (Aug-Oct).** Ginseng + mugwort + bamboo sap pairs with the seasonal pivot to warmer / richer textures and a heritage-storytelling frame that IE audiences over-index on. Do NOT push it ahead of the summer barrier-first / PDRN / spicules cycle — those are the warmer-weather demand drivers. Sequence: now → spicules + PDRN + glazed donut, autumn → hanbang + skin longevity + well-ageing flip.

## Data quality

**Status: PARTIAL — Google Trends fetch still blocked at the network-policy layer for the third consecutive day; qualitative `WebSearch` triage substituted again.**

Diagnosis (Day 3, unchanged from Day 2):
- `pytrends.TrendReq` constructs cleanly with `urllib3<2` (fix held).
- Single-keyword GB + IE `interest_over_time()` fetches both return `ResponseError: 403`.
- `trends.google.com/trending/rss?geo=GB`, `wikimedia.org/api/rest_v1/metrics/pageviews/...`, and the equivalent `en.wikipedia.org` endpoint all return `HTTP Error 403: Forbidden` via direct `urllib`.
- `WebFetch` to `trends.google.com/trends/explore?...&geo=GB&q=Korean+skincare` and to the Wikimedia pageviews URL: 403 on both.
- **`WebSearch` is unblocked** and was used today to triage UK/IE-press signal for each tracked keyword (Marie Claire UK, Cosmetics Business, Hello! UK, TheIndustry.beauty, Beauty Geek, NBC Select, Parlor Beauty, Mamabella UK, Get the Gloss, Kiehl's editorial, K-Trend, KnokGlobal, Glossy, ChannelX, Boots Ireland Facebook, Seoul Sister, Korean Skincare Coach, GreyB, VITA, SkinSort, Cosmetify, Supply Chain Digital, Cosmetics & Toiletries, Coveteur). Same fallback as Day 2.

What that means for the table: UK avg / IE avg / Today-vs-7d-avg columns are a **qualitative** sample (`+`/`=`/`−`/`n/a`) sourced from `WebSearch`, **not** a Google-Trends 0–100 index. The bucket framework, the fade clock, and the anomaly column are still valid; cross-day velocity comparisons will not be quantitative until pytrends is unblocked.

Escalation status:
- **Day 3 of 403 → escalate the network-policy ask.** Recommended action: open a session with the owner (Soomin) at https://code.claude.com/docs/en/claude-code-on-the-web and request outbound allowlist for `trends.google.com`, `news.google.com`, `wikimedia.org`, `reddit.com`. Without this, the routine has been running on a qualitative proxy for 3/3 days. The triage is useful, but the named output ("Google Trends data for UK and Ireland") is structurally undelivered.
- Worst-case substitute (continues to work): keep building on the `WebSearch` triage and pair it with `fastmoss_raw/` TikTok exports + Boots.ie / SkinShop.ie PDP review-count deltas. That gives the routine a usable demand proxy until path (1) lands.

Tomorrow's run will: (a) re-attempt pytrends — if Day 4 of 403, the recommendation is to formally re-scope this routine's name to "K-Beauty UK/IE Demand Triage" until the policy lands; (b) advance the fade clock to Day 4 — Centellian24 and Yepoda are the two brands on watch and most at risk of being marked `faded` if they produce no fresh UK signal; (c) re-check Boots IE PDRN sell-through (a Henry Street stock-check is the cleanest IE-specific data point we can substitute for missing IE Trends data).

---

Sources sampled today (via `WebSearch`, all UK/IE-facing trade, consumer press, or platform announcements):

- [Mediheal Toner Pads (now at Boots) — Beauty Geek UK](https://beautygeekuk.com/2026/03/mediheal-toner-pads-now-at-boots.html)
- [Mediheal PDRN Lifting Pad (100 pads) — Boots UK](https://www.boots.com/mediheal-pdrn-lifting-pad-170ml-100-pads-10382518)
- [Mediheal brings K-beauty toner pads to Boots as UK demand surges — TheIndustry.beauty](https://theindustry.beauty/mediheal-brings-k-beauty-toner-pads-to-boots-as-uk-demand-surges/)
- [New Mediheal PDRN Lifting Pads have landed — Boots Ireland Facebook](https://www.facebook.com/BootsIrelandOfficial/videos/new-mediheal-pdrn-lifting-pads-have-landed-containing-the-viral-ingredient-pdrn-/862155643525609/)
- [K-Skincare brand Mediheal has just dropped for their first UK launch — Boots UK TikTok](https://www.tiktok.com/@bootsuk/video/7558808152771267862)
- [TikTok Shop now UK's fourth largest beauty retailer — ChannelX](https://channelx.world/2026/01/tiktok-shop-now-uks-fourth-largest-beauty-retailer/)
- [TikTok Shop UK reports 60% beauty sales growth driven by K-beauty — Cosmetics Business](https://cosmeticsbusiness.com/tiktok-shop-report-kbeauty-driven-sales-growth)
- [From 'Glass Skin' to British Favourites — TikTok Newsroom UK](https://newsroom.tiktok.com/tiktokshopbeautycrush?lang=en-GB)
- [Boots reveals top beauty + wellness trends 2025](https://www.boots-uk.com/newsroom/news/boots-reveals-the-top-beauty-and-wellness-trends-and-best-selling-products-of-2025/)
- [Boots releases 2026 Beauty & Wellness Trends Report](https://www.boots-uk.com/newsroom/news/boots-releases-2026-beauty-wellness-trends-report-alongside-line-up-of-trending-new-brands/)
- [Boots taps into K-beauty trend with brand expansion — TheIndustry.beauty](https://theindustry.beauty/boots-taps-into-k-beauty-trend-with-brand-expansion/)
- [The K-beauty trends expected to explode in 2026 — Hello! UK](https://www.hellomagazine.com/hfm/beauty-trends/874525/k-beauty-trends-2026/)
- [K-beauty in 2026: Expert predictions on AI, barrier care and sensorial skincare — TheIndustry.beauty](https://theindustry.beauty/k-beauty-in-2026-expert-predictions-on-ai-barrier-care-and-sensorial-skincare/)
- [Hanbang 2.0 — Korean Herbal Skincare Gets a High-Tech Makeover in 2026 — K-Trend](https://k-trend.me/hanbang-skincare-2026-korean-herbal/)
- [Hanbang 2.0: How Modern Korean Skincare Reinvents Herbal Traditions — KnokGlobal](https://knokglobal.com/blog/hanbang-2-0-modern-korean-herbal-skincare-innovation-2026)
- [Meet Hanbang: The Latest K-Beauty Trend That'll Level Up Your Skin — Coveteur](https://coveteur.com/hanbang-skin-k-beauty-trend)
- [Top Skincare Trends for 2026 and the Ingredients Driving the Shift — Korean Skincare Coach](https://www.koreanskincarecoach.com/blog/top-skincare-trends-for-2026-and-the-ingredients-driving-the-shift)
- [Ectoin in K-Beauty — jellyko](https://jellyko.com/blogs/news/ectoin-in-k-beauty)
- [Calling all sensitive skin types: It's time you learn about ectoin — NBC Select](https://www.nbcnews.com/select/shopping/best-ectoin-skin-care-products-rcna206589)
- [10 Best Treatments With Polyglutamic Acid In 2026 — SkinSort](https://skinsort.com/products/treatments-with-polyglutamic-acid)
- [The Ingredient Edit: 10 Skincare Power Players We're Bringing Into 2026 — VITA Daily](https://vitamagazine.com/2026/01/02/the-ingredient-edit-10-skincare-power-players-were-bringing-into-2026/)
- [What is "Glazed Donut" Skin and How Do You Get It? — Kiehl's](https://www.kiehls.com/skincare-advice/glazed-donut-face-skin.html)
- [Liquid microneedling explained – does it really work? — Mamabella UK](https://mamabella.uk/what-is-liquid-microneedling-work-worth-it-products/)
- [Spicule Skincare: The K-Beauty Secret to Glass Skin — Marie Claire UK](https://www.marieclaire.co.uk/beauty/skincare/spicules-skincare)
- [What is "liquid microneedling?" — NBC News Select](https://www.nbcnews.com/select/shopping/spicules-skin-care-rcna264100)
- [Liquid Microneedling: The Viral Skincare Trend and Reedle Shot — Parlor Beauty](https://parlorbeauty.co.uk/liquid-microneedling-the-viral-skincare-trend-and-reedle-shot/)
- [What are Microspicules - aka the seasponge needle facial — Get the Gloss](https://www.getthegloss.com/beauty/skincare/what-are-microspicules/)
- [Top 10 Trending K-Beauty Products in March 2026 — Seoul Sister](https://www.seoulsister.com/blog/trending-k-beauty-products-2026-03)
- [Exclusive: Target continues to lean into K-Beauty with the addition of Haruharu Wonder — Glossy](https://www.glossy.co/beauty/exclusive-target-continues-to-lean-into-k-beauty-with-the-addition-of-haruharu-wonder/)
- [Is TikTok Shop Driving Consumer Trends and K-Beauty Demand? — Supply Chain Digital](https://supplychaindigital.com/news/is-tiktok-shop-driving-consumer-trends-and-k-beauty-demand)
- [Sephora UK Skin1004 brand page](https://www.sephora.co.uk/brands/Skin1004)

Saved to repo: `daily_data/2026_06_09/trends-uk-ie.md`
