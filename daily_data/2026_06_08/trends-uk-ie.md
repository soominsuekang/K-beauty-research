# K-Beauty Google Trends — UK & Ireland — 2026-06-08

> **DATA QUALITY — read first.** The `trends.google.com` block from yesterday is still in force. `pytrends.TrendReq` constructs cleanly (urllib3<2 pin held), but every `interest_over_time()` call returns `ResponseError: 403`. Same outcome for the `trends.google.com/trending/rss`, `wikimedia.org/api/rest_v1/metrics/pageviews/...`, and `en.wikipedia.org/api/rest_v1/...` fallbacks (all 403 at the network-policy layer). `WebFetch` to those hosts also 403s. **No numerical UK/IE Google-Trends values were captured this cycle.** The tables below carry the bucket framework forward and replace the numeric columns with a qualitative signal sampled via `WebSearch` (which the policy *does* permit) on UK/IE-facing trade press and TikTok newsroom posts. See `## Data quality` for the full diagnosis and the fix path. Day 2 of the carry-forward fade clock — no drops yet.

## Tracking distribution
BASE: 23 / CARRY-FORWARD: 11 / NEW: 4

- BASE brands (14): medicube, Dr.Melaxin, d'Alba, COSRX, Beauty of Joseon, AXISY, mixsoon, INKEY List, Wonderskin, Halara, Numbuzin, Anua, VT, Purito
- BASE categories (9): Korean skincare, k-beauty, glass skin, tiktok skincare, kbeauty haul, well ageing, skin longevity, PDRN, NAD+
- CARRY-FORWARD brands (8 — Day 2 of fade clock): Round Lab, SKIN1004, Biodance, Laneige, TIRTIR, HaruHaru Wonder, Centellian24, Yepoda *(promoted from NEW yesterday)*
- CARRY-FORWARD categories (3 — Day 2): snail mucin, rice toner, skin barrier
- NEW today (4 — required ≥3):
  1. **spicules** (ingredient) — Google searches for `spicule skincare` up 119% YoY and `liquid microneedling` up 535% YoY per Cosmetics Business / Marie Claire UK; primed to break through in UK in H2 2026.
  2. **BIOHEAL BOH** (brand) — Olive Young's own anti-ageing line launched a TikTok Shop UK storefront in the last few months and is being trialled on UK consumers; surfaced in TikTok's own UK newsroom recap.
  3. **exosome** (ingredient) — Seoul derms now pair PDRN (repair) + exosome (cell-to-cell messaging) in a dual-active protocol; UK trade press is positioning exosome as PDRN's logical sibling for 2026.
  4. **Mediheal** (brand) — Mediheal's PDRN-soaked toner pads "instantly sold out" at Boots UK on launch per Yahoo Beauty / Grazia UK; not in base seed and absent from yesterday's tracking.

## Brands (last 7 days)

*UK avg / IE avg columns hold qualitative signal (`+` rising, `=` flat, `−` falling, `n/a` no signal). They are NOT Google-Trends 0–100 indices — they are a `WebSearch` triage. Replace with pytrends values the moment the policy is loosened.*

| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| medicube | BASE | + | + | + | rising (AGE-R device >100M TikTok views; PDRN Pink Peptide Serum cited as viral retail item) |
| Dr.Melaxin | BASE | = | n/a | = | flat (named in TikTok UK launch cohort, no fresh signal) |
| d'Alba | BASE | n/a | n/a | n/a | blocked / no fresh signal |
| COSRX | BASE | = | = | = | flat (still a benchmark name in UK trade press, no inflection) |
| Beauty of Joseon | BASE | = | = | = | flat-positive (continues as the K-beauty default in Marie Claire / Coree pieces) |
| AXISY | BASE | n/a | n/a | n/a | blocked / no fresh signal |
| mixsoon | BASE | + | n/a | + | rising (named alongside Medicube/BOJ in TikTok Shop UK cohort) |
| INKEY List | BASE | n/a | n/a | n/a | blocked / no fresh signal (UK-origin brand, not K-) |
| Wonderskin | BASE | n/a | n/a | n/a | blocked / no fresh signal |
| Halara | BASE | n/a | n/a | n/a | blocked / no fresh signal (apparel, off-thesis) |
| Numbuzin | BASE | = | n/a | = | flat |
| Anua | BASE | + | + | + | rising (heart-leaf toner still cited as the BOJ alternative in IE coverage) |
| VT | BASE | + | = | + | rising (Cica/Reedle Shot pulled into "liquid microneedling" coverage) |
| Purito | BASE | = | n/a | = | flat |
| Round Lab | CARRY-FORWARD | = | n/a | = | flat (no fresh UK/IE press hit today) |
| SKIN1004 | CARRY-FORWARD | = | n/a | = | flat (named as cruelty-free K-brand in Brit+Co list) |
| Biodance | CARRY-FORWARD | n/a | n/a | n/a | no fresh signal — Day 2 of fade clock |
| Laneige | CARRY-FORWARD | = | = | = | flat (Lip Sleeping Mask remains LookFantastic IE staple) |
| TIRTIR | CARRY-FORWARD | n/a | n/a | n/a | no fresh signal — Day 2 of fade clock |
| HaruHaru Wonder | CARRY-FORWARD | n/a | n/a | n/a | no fresh signal — Day 2 of fade clock |
| Centellian24 | CARRY-FORWARD | n/a | n/a | n/a | no fresh signal — Day 2 of fade clock |
| Yepoda | CARRY-FORWARD | n/a | n/a | n/a | no fresh signal — Day 2 of fade clock (was NEW yesterday) |
| spicules | NEW | + | n/a | + | rising sharply (119% YoY UK search per Cosmetics Business; viral on TikTok) |
| BIOHEAL BOH | NEW | + | n/a | + | rising (TikTok Shop UK launch in last few months, Olive Young promotion) |
| Mediheal | NEW | + | n/a | + | rising (Boots UK PDRN-pad sell-out cited in Yahoo Beauty / Grazia UK) |

## Categories (last 7 days)
| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| Korean skincare | BASE | = | = | = | flat-positive (steady UK retail momentum, TikTok Shop = 4th-largest UK beauty retailer) |
| k-beauty | BASE | = | = | = | flat-positive (60% YoY beauty growth on TikTok Shop UK with K-beauty as a named driver) |
| glass skin | BASE | + | = | + | rising (TikTok UK newsroom led with "Glass Skin to British Favourites" headline; spicules coverage piggybacks on it) |
| tiktok skincare | BASE | + | + | + | rising (UK + IE both expanding TikTok Shop categories) |
| kbeauty haul | BASE | = | = | = | flat |
| well ageing | BASE | = | n/a | = | flat — being out-cited by "skin longevity" + "barrier-repair" |
| skin longevity | BASE | + | n/a | + | rising (Olive Young 2026 trend report frames it as the umbrella term) |
| PDRN | BASE | + | + | + | rising (cited by Yahoo Beauty, Grazia UK, Cosmetics Business — strongest single ingredient in coverage) |
| NAD+ | BASE | n/a | n/a | n/a | no fresh K-beauty-context hit today (NAD+ coverage is wellness-side) |
| snail mucin | CARRY-FORWARD | = | = | = | flat-positive (still a UK staple, no inflection) |
| rice toner | CARRY-FORWARD | = | + | + | rising in IE (Penneys PS… K-Beauty Cica+Niacinamide rice toner from SS26 preview is rolling out) |
| skin barrier | CARRY-FORWARD | + | + | + | rising (Boots 2026 Beauty + Wellness Trends Report leads on barrier-repair; the IE 18-34 gateway term) |
| exosome | NEW | + | n/a | + | rising (paired with PDRN in dual-active 2026 protocols per Korean Skincare Coach + GreyB) |
| liquid microneedling | NEW *(adjacent to spicules)* | + | n/a | + | rising (535% YoY UK search per Parlor Beauty / Cosmetics Business) |

*Note: `liquid microneedling` is logged as a NEW adjacency under spicules rather than a separate fifth bucket entry — it is the consumer-facing search term that the same trend resolves to.*

## Faded / contradicted carry-forwards
**None this cycle.** Day 2 of the 3-day fade clock on all 8 carry-forward brands + 3 carry-forward categories. Five carry-forward brands (Biodance, TIRTIR, HaruHaru Wonder, Centellian24, Yepoda) returned **no fresh UK/IE-press signal today** — if Day 3 (2026-06-09) also produces nothing, they will be flagged `faded` for review and dropped on Day 4 (2026-06-10). No contradictions: nothing in today's sampling refutes the yesterday-surfaced brands.

## Anomalies (>50% change)
- **spicules / liquid microneedling**: +119% YoY (spicule skincare) and +535% YoY (liquid microneedling) in UK search per Cosmetics Business / Parlor Beauty. This is by far the largest movement in today's sampling and is the single ingredient story most likely to overtake "rice toner" as the IE 18-34 entry point in H2 2026.
- **PDRN cluster (Mediheal Boots sell-out)**: Mediheal's PDRN-soaked toner pads "instantly sold out" at Boots UK on launch — a discrete sell-through anomaly, not a search-velocity anomaly, but worth recording because it confirms the PDRN base-seed term has converted to UK retail demand, not just press buzz.
- *No other >50% movers visible in today's qualitative sample. Real anomaly detection resumes the moment pytrends is unblocked.*

## Notes for content strategy (IE 18-34 women)

1. **Spicules is the highest-velocity ingredient story you can claim now.** +119% YoY UK search and +535% YoY for the consumer-facing term "liquid microneedling" — and there is currently no dominant IE creator on it. Pitch: a side-by-side of a £35 spicule ampoule (e.g. VT Reedle Shot) vs. a £200 in-clinic microneedling session, filmed in Dublin, with derm voice-over. This is the most ownable green-field niche in today's data set, and it slots cleanly into the existing "rice toner → barrier → glass skin" funnel.
2. **Mediheal × Boots IE replication watch.** Mediheal's PDRN toner pads sold out at Boots UK on launch. Boots IE stocks the same SKU range. If you can confirm the same sell-through pattern on Henry Street within 7 days of UK launch, that is an IE-specific scarcity-marketing angle (`"They sold out in UK in days — Boots Dublin still has stock"`) that does NOT exist for Penneys' rice toner.
3. **PDRN is graduating from ingredient to category — rebrand internal coverage.** PDRN is now consistently mentioned alongside exosomes as a paired dual-active in 2026 Seoul derm protocols. The internal content map should stop treating PDRN as a single ingredient and start treating "PDRN + exosome" as a category. That reframing matches how Boots, Olive Young, and Marie Claire UK are positioning it for H2 2026 — and it gives you a longer-form "explainer" angle that competitors still treating PDRN as a single hero molecule cannot match.
4. **BIOHEAL BOH is the first-mover Olive-Young-owned brand on TikTok Shop UK.** Yesterday we added Yepoda as the European-built K-house to watch. BIOHEAL BOH is the inverse trade: a Korean-built, Olive-Young-owned brand using TikTok Shop UK as its EU beachhead. Pre-screen for IE TikTok Shop availability (TikTok Shop went live in IE late 2024). If it is shippable to IE, this is a "before it lands at Boots" early-adopter pitch with a finite window.

## Data quality

**Status: PARTIAL — Google Trends fetch still blocked at the network-policy layer; qualitative `WebSearch` triage substituted.**

Diagnosis vs. yesterday:
- `pytrends.TrendReq` constructs cleanly with `urllib3<2` (fix held).
- Single-keyword GB + IE fetches both still return `ResponseError: 403`.
- `trends.google.com/trending/rss?geo=GB`, `wikimedia.org/api/rest_v1/metrics/pageviews/...`, and the equivalent `en.wikipedia.org` endpoint all return `HTTP Error 403: Forbidden` via direct `urllib`.
- `WebFetch` to `trends.google.com/trends/explore?...&geo=GB&q=Korean+skincare` and to the Wikimedia pageviews URL: 403 on both.
- **`WebSearch` is unblocked** and was used today to triage UK/IE-press signal for each tracked keyword (Marie Claire UK, Cosmetics Business, Grazia UK, Yahoo Beauty, TikTok newsroom, Brit+Co, Boots UK, LookFantastic, Korean Skincare Coach, GreyB). This is the only working web-side signal in the container today.

What that means for the table: UK avg / IE avg / Today-vs-7d-avg columns are a **qualitative** sample (`+`/`=`/`−`/`n/a`) sourced from `WebSearch`, **not** a Google-Trends 0–100 index. The bucket framework, the fade clock, and the anomaly column are still valid, but velocity comparisons across days will not be quantitative until pytrends is unblocked.

Fix paths (priority order, unchanged):
1. **Loosen the environment network policy** to allow outbound to `trends.google.com`, `news.google.com`, `wikimedia.org`, and `reddit.com`. Owner: Soomin, via Claude Code on the web env settings → https://code.claude.com/docs/en/claude-code-on-the-web.
2. Route the routine through a self-hosted proxy on an allowed domain (e.g. a Cloudflare Worker fronting `trends.google.com`).
3. Worst-case substitute: keep building on the `WebSearch` triage that worked today and pair it with `fastmoss_raw/` TikTok exports + Boots.ie / SkinShop.ie PDP review-count deltas. That is not a search-interest substitute, but together with the bucket framework here it gives the routine a usable demand proxy until path (1) lands.

Tomorrow's run will: (a) re-attempt pytrends; (b) if still blocked, keep the `WebSearch` triage and tighten which UK/IE outlets it samples; (c) advance the carry-forward fade clock to Day 3 — five brands (Biodance, TIRTIR, HaruHaru Wonder, Centellian24, Yepoda) are the most at risk of being marked `faded` on 2026-06-10.

---

Sources sampled today (via `WebSearch`, all UK/IE-facing trade or consumer press):

- [Spicules: The Prickly K-Beauty Trend Going Viral For Its Glass Skin Effects — Marie Claire UK](https://www.marieclaire.co.uk/beauty/skincare/spicules-skincare)
- [Spicules: the K-beauty skin care ingredient primed to break through in 2026 — Cosmetics Business](https://cosmeticsbusiness.com/spicules-the-k-beauty-skin-care-ingredient-primed)
- [Liquid Microneedling: The Viral Skincare Trend and Reedle Shot — Parlor Beauty](https://parlorbeauty.co.uk/liquid-microneedling-the-viral-skincare-trend-and-reedle-shot/)
- [From 'Glass Skin' to British Favourites: TikTok Shop Drives Double Digit Beauty Growth — TikTok Newsroom UK](https://newsroom.tiktok.com/tiktokshopbeautycrush?lang=en-GB)
- [TikTok Shop emerges as UK's fourth largest beauty retailer — Retail Times](https://retailtimes.co.uk/tiktok-shop-emerges-as-uks-fourth-largest-beauty-retailer-with-60-yoy-growth-and-k-beauty-surge/)
- [The K-beauty trends expected to explode in 2026 — Hello! UK](https://www.hellomagazine.com/hfm/beauty-trends/874525/k-beauty-trends-2026/)
- [Boots releases 2026 Beauty & Wellness Trends Report — Boots UK Newsroom](https://www.boots-uk.com/newsroom/news/boots-releases-2026-beauty-wellness-trends-report-alongside-line-up-of-trending-new-brands/)
- [Best PDRN K-beauty viral products — Grazia UK](https://graziadaily.co.uk/beauty-hair/skin/best-pdrn-k-beauty-products/)
- [PDRN is trending. Some dermatologists call it a legit anti-aging ingredient. — Yahoo Beauty](https://shopping.yahoo.com/beauty/skincare/article/what-is-pdrn-155024557.html)
- [Top Skincare Trends for 2026 — Korean Skincare Coach](https://www.koreanskincarecoach.com/blog/top-skincare-trends-for-2026-and-the-ingredients-driving-the-shift)
- [Olive Young reveals K-Beauty trends for 2026 — Personal Care Insights](https://www.personalcareinsights.com/news/olive-young-k-beauty-trends.html)
- [Top TikTok Beauty Trends 2026 — Qogita](https://www.qogita.com/blog/tiktok-beauty-trends-2026/)
- [5 Korean Beauty Trends in 2026 for R&D Leaders — GreyB](https://greyb.com/blog/korean-beauty-trends)
- [Why Everyone on TikTok Is Talking About Spicule Skincare — KPTOWN](https://www.kptown.com/blogs/blog/why-everyone-on-tiktok-is-talking-about-spicule-skincare)

Saved to repo: `daily_data/2026_06_08/trends-uk-ie.md`
