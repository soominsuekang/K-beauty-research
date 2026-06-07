# K-Beauty Google Trends — UK & Ireland — 2026-06-07

*Day 1 of the trends-uk-ie routine. No prior `trends-uk-ie.md` to inherit from, so CARRY-FORWARD has been seeded from `daily_data/2026_06_06/eod-briefing.md` + `ireland-signal.md` (brands surfaced there that are not in the base seed).*

> **CRITICAL DATA QUALITY ISSUE — read first.**
> The Google Trends fetch could not run today. The container's outbound network policy 403s every request to `trends.google.com`, `news.google.com`, `wikimedia.org`, `reddit.com`, `duckduckgo.com`, and `bing.com` — both via direct `urllib` and via the `WebFetch` proxy. `pytrends.TrendReq` itself works (the `urllib3` `method_whitelist` incompatibility was fixed by pinning `urllib3<2`), but every `interest_over_time()` call returns `ResponseError: 403`. The RSS fallback is blocked at the same layer. **No UK/IE trends values were captured this cycle.** The table below records the bucket framework only; numeric columns are `n/a`. See `## Data quality` for environment-policy details and the fix path.

## Tracking distribution
BASE: 23 / CARRY-FORWARD: 7 / NEW: 4

- Base brands (14): medicube, Dr.Melaxin, d'Alba, COSRX, Beauty of Joseon, AXISY, mixsoon, INKEY List, Wonderskin, Halara, Numbuzin, Anua, VT, Purito
- Base categories (9): Korean skincare, k-beauty, glass skin, tiktok skincare, kbeauty haul, well ageing, skin longevity, PDRN, NAD+
- Carry-forward brands (7, from yesterday's eod-briefing + ireland-signal): Round Lab, SKIN1004, Biodance, Laneige, TIRTIR, HaruHaru Wonder, Centellian24
- NEW today (4 — required ≥3): Yepoda (brand, European-based K-skincare house with rising TikTok presence), snail mucin (ingredient, perennial K-skincare hook), rice toner (category — Penneys PS… K-Beauty launched a Cica + Niacinamide rice toner at the Dublin SS26 preview per yesterday's ireland-signal), skin barrier (category — well-ageing / longevity adjacent term picking up in UK press)

## Brands (last 7 days)
| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| medicube | BASE | n/a | n/a | n/a | blocked |
| Dr.Melaxin | BASE | n/a | n/a | n/a | blocked |
| d'Alba | BASE | n/a | n/a | n/a | blocked |
| COSRX | BASE | n/a | n/a | n/a | blocked |
| Beauty of Joseon | BASE | n/a | n/a | n/a | blocked |
| AXISY | BASE | n/a | n/a | n/a | blocked |
| mixsoon | BASE | n/a | n/a | n/a | blocked |
| INKEY List | BASE | n/a | n/a | n/a | blocked |
| Wonderskin | BASE | n/a | n/a | n/a | blocked |
| Halara | BASE | n/a | n/a | n/a | blocked |
| Numbuzin | BASE | n/a | n/a | n/a | blocked |
| Anua | BASE | n/a | n/a | n/a | blocked |
| VT | BASE | n/a | n/a | n/a | blocked |
| Purito | BASE | n/a | n/a | n/a | blocked |
| Round Lab | CARRY-FORWARD | n/a | n/a | n/a | blocked |
| SKIN1004 | CARRY-FORWARD | n/a | n/a | n/a | blocked |
| Biodance | CARRY-FORWARD | n/a | n/a | n/a | blocked |
| Laneige | CARRY-FORWARD | n/a | n/a | n/a | blocked |
| TIRTIR | CARRY-FORWARD | n/a | n/a | n/a | blocked |
| HaruHaru Wonder | CARRY-FORWARD | n/a | n/a | n/a | blocked |
| Centellian24 | CARRY-FORWARD | n/a | n/a | n/a | blocked |
| Yepoda | NEW | n/a | n/a | n/a | blocked |

## Categories (last 7 days)
| Keyword | Bucket | UK avg | IE avg | Today vs 7d avg | Direction |
|---|---|---|---|---|---|
| Korean skincare | BASE | n/a | n/a | n/a | blocked |
| k-beauty | BASE | n/a | n/a | n/a | blocked |
| glass skin | BASE | n/a | n/a | n/a | blocked |
| tiktok skincare | BASE | n/a | n/a | n/a | blocked |
| kbeauty haul | BASE | n/a | n/a | n/a | blocked |
| well ageing | BASE | n/a | n/a | n/a | blocked |
| skin longevity | BASE | n/a | n/a | n/a | blocked |
| PDRN | BASE | n/a | n/a | n/a | blocked |
| NAD+ | BASE | n/a | n/a | n/a | blocked |
| snail mucin | NEW | n/a | n/a | n/a | blocked |
| rice toner | NEW | n/a | n/a | n/a | blocked |
| skin barrier | NEW | n/a | n/a | n/a | blocked |

## Faded / contradicted carry-forwards
None this cycle. No prior trends-uk-ie.md exists, so the 3-consecutive-day fade rule has not yet started counting. All 7 carry-forward brands above are at day 1 of the fade clock; if Day 4 (2026-06-10) still has no data for any of them, they will be marked `faded` and dropped.

## Anomalies (>50% change)
None — no values captured.

## Notes for content strategy (IE 18-34 women)
*Provisional, since today's trends fetch is empty. These are carried forward from yesterday's `ireland-signal.md` + `eod-briefing.md` and flagged for re-confirmation once trends data lands.*

1. **Rice toner is the lowest-hanging IE-specific franchise.** Penneys' PS… K-Beauty Cica + Niacinamide rice toner is the first own-label IE-mass K-product on shelves. There is currently no UK equivalent at the same price ceiling, and "rice toner" as a search term is generic enough that a first-mover IE creator can own it. Pitch: a Penneys-haul unboxing crossed with a Sissel Lab / Anua / BOJ "is it actually the same thing?" verdict. Re-confirm "rice toner" trend direction in tomorrow's run.
2. **PDRN credibility war stays the headline opening.** PDRN is a base seed term, and the Institute of Dermatologists (Profs Ralph & Ryan) was identified yesterday as the credentialed IE voice with no K-beauty endorsement yet. The first creator to broker an on-record PDRN take from them owns the IE PDRN cluster. Watch PDRN trend direction in Wed's data.
3. **Skin barrier > well-ageing as the IE 18-34 entry term.** "Well-ageing" and "skin longevity" are aspirational and skew older; "skin barrier" is the gateway term for 18-34 audiences that maps directly onto Anua + BOJ + Round Lab product pages. Worth tracking divergence between these two terms once data is unblocked.
4. **Yepoda is the European-based K-house worth pre-screening.** Built in Berlin, ships across the EU including IE, leans hard into TikTok. If today's fetch had worked we would already know whether IE search volume is non-trivial. Day 1 hypothesis: Yepoda will index higher in IE than UK, because IE consumers shopping via EU warehouses face fewer post-Brexit shipping frictions than UK consumers do.

## Data quality

**Status: FAILED — Google Trends fetch blocked at the network-policy layer.**

What was attempted:
1. `pip install pytrends` → ok.
2. First fetch attempt → 34/34 keywords errored with `Retry.__init__() got an unexpected keyword argument 'method_whitelist'`. Diagnosed as `pytrends` (latest) calling a `urllib3` API that was removed in `urllib3>=2`.
3. Pinned `urllib3<2`. `pytrends.TrendReq` now constructs cleanly.
4. Retry on a single keyword (`Korean skincare`, `geo=GB`, `now 7-d`) → `pytrends.exceptions.ResponseError: The request failed: Google returned a response with code 403`.
5. RSS fallback (`https://trends.google.com/trending/rss?geo=GB`, `https://trends.google.com/trends/api/dailytrends?geo=GB`) → 403.
6. Cross-domain probe (en.wikipedia.org, duckduckgo.com, reddit.com, bing.com, news.ycombinator.com) → 403 on **all** of them.
7. WebFetch proxy on `trends.google.com/trends/explore` and `en.wikipedia.org/wiki/COSRX` → 403 on both.

Diagnosis: this routine is running in a managed remote-execution container whose **network policy** (see https://code.claude.com/docs/en/claude-code-on-the-web) does not allow outbound to Google / Wikipedia / general web hosts. The block is below pytrends — it cannot be worked around by changing libraries, headers, retries, or sleep intervals. RSS and Wikipedia-pageviews proxies, the two documented fallbacks for this task, both fail at the same layer.

Fix paths (in priority order):
1. **Loosen the environment network policy** to permit `trends.google.com`, `news.google.com`, `wikimedia.org`, and `reddit.com`. This is the only durable fix. (Owner: Soomin, via Claude Code on the web env settings.)
2. If a wider policy isn't acceptable, route this routine through a self-hosted scraping proxy (e.g. a tiny Cloudflare Worker on a known-allowed domain that proxies `trends.google.com` calls).
3. Worst-case substitute: replace Google Trends with a UK/IE-segmentable signal that the policy *does* allow — TikTok creator-side API exports (which are already in `fastmoss_raw/`), Boots.ie / SkinShop.ie product-detail-page review-count deltas, or RTÉ / Irish Examiner article-publish counts. None of these are 1:1 substitutes for search-interest velocity, but together they would let the trends-uk-ie routine run as a "demand proxy" pipeline.

Tomorrow's run will: (a) re-attempt pytrends in case the policy has been loosened; (b) if still blocked, populate the same table from whichever fallback Soomin enables; (c) start the 3-day fade clock for the 7 carry-forward brands above.

---

Saved to repo: `daily_data/2026_06_07/trends-uk-ie.md`
