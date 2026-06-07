# TikTok Hashtag Tracker — 2026-06-07

*Day 1 of the tag-content-tracker routine. No prior `tag-content-tracker.md` exists in repo, so the formal CARRY-FORWARD slot ("hashtags identified yesterday not in base seed") = 0. To keep the spirit of the carry-forward rule on Day 1 (and matching the precedent set by `trends-uk-ie.md` earlier today), CARRY-FORWARD has been seeded from yesterday's `eod-briefing.md` "active hashtag inventory" line (the retail-tag set + the active K-cluster) for any tag not already in the base seed. From tomorrow, CARRY-FORWARD will read from this file directly.*

> **Data-quality flag — read first.** Every direct TikTok endpoint (`tiktok.com/tag/{tag}`, `ads.tiktok.com/business/creativecenter/hashtag/...`, `tokchart`, `display-purposes.com`, aggregators) returned **HTTP 403** to `WebFetch` — same network-policy block diagnosed in `trends-uk-ie.md` and `tiktok-sounds.md`. No total-view or 24h-new numbers could be scraped. The numeric columns below are filled with either `n/a (blocked)` or an `est.` value derived from text summaries in indexed reports (Spate / TikTok Newsroom / WWD / Stylist UK / Boots-UK 2026 Trends Report / Cosmetics Business). Direction columns are based on the same secondary evidence and on FastMoss-derived ER patterns recorded in yesterday's `eod-briefing.md` / `day1-brief.md`. Treat ranks as directional, not precise. Full diagnosis in `## Data quality`.

## Tracking distribution
BASE: 36 / CARRY-FORWARD: 5 / NEW: 5

- Base seed (36, from the routine brief): #gurwm, #grwm, #skintok, #morningroutine, #nightroutine, #firstimpressions, #verdict, #vs, #unboxing, #glassskin, #dollyskin, #glowyskin, #dewyskin, #wellageing, #skinlongevity, #skincareroutine, #skincaretips, #womenover30, #costcobeauty, #boots, #bootsbeauty, #bootsireland, #superdrug, #cultbeauty, #kbeauty, #koreanskincare, #medicube, #dralba, #cosrx, #beautyofjoseon, #pdrnskincare, #7stepskincare, #numbuzin, #nadplus, #anua, #mixsoon
- Carry-forward (5, from 2026-06-06 eod-briefing "active hashtag inventory" + retail-tag set, not in base seed): #pdrn (NB: distinct from #pdrnskincare — the bare-ingredient tag), #tiktokshopmademebuyit, #bootshenrystreet, #arnotts, #brownthomas
- NEW today (5, ≥3 required — picked from adjacent communities + sudden risers with sourced evidence): #skinbarrier, #kpharmacy, #jellycleanser, #cleantok, #slugging

## Format hashtags
| Hashtag | Bucket | Total views | 24h new | Direction |
|---|---|---|---|---|
| #grwm | BASE | est. ≥ 80 B (top-tier beauty/lifestyle tag, UK-large) | n/a (blocked) | → flat-large |
| #gurwm | BASE | est. low-single-digit B (still emerging) | n/a (blocked) | ↑ rising (FastMoss sample ER 8.54% — top ER in 28d K-skincare AD pool per `day1-brief.md`) |
| #skintok | BASE | est. ≥ 50 B (3rd most-used beauty hashtag UK per TikTok Newsroom) | n/a (blocked) | → flat-large |
| #morningroutine | BASE | est. ≥ 30 B | n/a (blocked) | → flat |
| #nightroutine | BASE | est. ≥ 20 B | n/a (blocked) | → flat |
| #firstimpressions | BASE | est. ≥ 15 B | n/a (blocked) | → flat |
| #verdict | BASE | est. mid-single-digit B (narrower) | n/a (blocked) | ↑ rising — H1 "verdict beats haul" SUPPORTED across 3 sources yesterday |
| #vs | BASE | est. ≥ 100 B (generic, but works as verdict-format proxy) | n/a (blocked) | → flat-large |
| #unboxing | BASE | est. ≥ 50 B | n/a (blocked) | → flat |
| #skincareroutine | BASE | est. ≥ 80 B (top WWD/TikTok Shop sales-driving tag) | n/a (blocked) | → flat-large |

## Look / Audience / Retail / K-beauty hashtags

### Look
| Hashtag | Bucket | Total views | 24h new | Direction |
|---|---|---|---|---|
| #glassskin | BASE | est. 10–15 B (TikTok Newsroom: K-Beauty surge anchor tag UK) | n/a (blocked) | ↑ rising (TikTok Shop UK K-Beauty +60% YoY 2025; "from Glass Skin to British Favourites") |
| #dollyskin | BASE | est. < 1 B (niche dewy/cute-aesthetic) | n/a (blocked) | → flat |
| #glowyskin | BASE | est. 3–5 B | n/a (blocked) | → flat |
| #dewyskin | BASE | est. 3–5 B | n/a (blocked) | → flat |
| #wellageing | BASE | est. < 500 M (UK editorial-driven, lags audience usage) | n/a (blocked) | → flat — copy lags vs. #skinbarrier (see NEW) |
| #skinlongevity | BASE | est. < 500 M (Boots UK 2026 Trends Report driver — editorial-led) | n/a (blocked) | ↑ rising in editorial, → flat in creator usage |

### Audience
| Hashtag | Bucket | Total views | 24h new | Direction |
|---|---|---|---|---|
| #skincaretips | BASE | est. ≥ 50 B | n/a (blocked) | → flat-large |
| #womenover30 | BASE | est. mid-single-digit B (skews older than the IE 18–34 target) | n/a (blocked) | → flat |

### Retail
| Hashtag | Bucket | Total views | 24h new | Direction |
|---|---|---|---|---|
| #costcobeauty | BASE | est. low-single-digit B (US-skewed; Gracesfaces 653k Costco-K-beauty video pegs this as high-velocity) | n/a (blocked) | ↑ rising |
| #boots | BASE | est. mid-single-digit B (UK-anchor) | n/a (blocked) | → flat-large |
| #bootsbeauty | BASE | est. < 1 B | n/a (blocked) | ↑ rising (Boots UK 2026 Trends Report push) |
| #bootsireland | BASE | est. low M (IE-specific, thin pool, but the IE 18–34 wedge) | n/a (blocked) | ↑ rising — only IE-mass retail tag with K-beauty depth |
| #superdrug | BASE | est. low-single-digit B | n/a (blocked) | → flat |
| #cultbeauty | BASE | est. mid-hundreds M | n/a (blocked) | → flat |
| #tiktokshopmademebuyit | CARRY-FORWARD | est. ≥ 5 B (TikTok-internal cohort tag) | n/a (blocked) | ↑ rising (TikTok Shop UK = 4th-largest beauty retailer per ChannelX) |
| #bootshenrystreet | CARRY-FORWARD | est. < 10 M (IE-hyperlocal — Dublin flagship) | n/a (blocked) | ↑ rising — IE creator-walk-through cluster opening |
| #arnotts | CARRY-FORWARD | est. < 50 M (IE dept-store) | n/a (blocked) | → flat |
| #brownthomas | CARRY-FORWARD | est. < 50 M (IE luxury dept-store) | n/a (blocked) | → flat |

### K-beauty
| Hashtag | Bucket | Total views | 24h new | Direction |
|---|---|---|---|---|
| #kbeauty | BASE | est. ≥ 30 B (3rd most-used beauty hashtag UK; ~2.5 B/week per Spate) | n/a (blocked) | ↑ rising |
| #koreanskincare | BASE | est. ≥ 25 B (top WWD/TikTok Shop sales-driving tag) | n/a (blocked) | ↑ rising (+125% UK search H2-2025) |
| #medicube | BASE | est. ~3 B (paid-push leader: 7.8 M UK paid views in 90d pool) | n/a (blocked) | ↑ rising |
| #dralba (d'Alba) | BASE | est. low B | n/a (blocked) | → flat |
| #cosrx | BASE | est. ≥ 5 B (perennial K-pillar; snail-mucin anchor) | n/a (blocked) | → flat-large |
| #beautyofjoseon | BASE | est. 3–5 B (organic-first GTM: 0 paid UK views 90d but Relief Sun sells out weekly at Sissel Lab IE) | n/a (blocked) | ↑ rising organic |
| #pdrnskincare | BASE | est. mid-hundreds M | n/a (blocked) | ↑ rising |
| #7stepskincare | BASE | est. low-single-digit B | n/a (blocked) | → flat |
| #numbuzin | BASE | est. < 1 B | n/a (blocked) | → flat |
| #nadplus | BASE | est. < 100 M (early ingredient cluster) | n/a (blocked) | ↑ rising (Medicube NAD+ duo launch surfaced in eod-briefing) |
| #anua | BASE | est. ~2 B (TikTok Shop UK launch; IE shelf presence at Sissel Lab + Boots IE) | n/a (blocked) | ↑ rising |
| #mixsoon | BASE | est. low-single-digit B | n/a (blocked) | → flat |
| #pdrn | CARRY-FORWARD | est. ~1.5–2 B (1.9 M *weekly* TikTok posts per Doctor Rogers / Spate citation) | n/a (blocked) | ↑ rising — "molecules too large" counter-meme proliferating UK editorial |

### NEW today (≥3 required)
| Hashtag | Bucket | Total views | 24h new | Direction | Why picked today |
|---|---|---|---|---|---|
| #skinbarrier | NEW | est. several-hundred M to low B ("hundreds of millions of views" per Spate-cited reporting; "skin barrier repair" Google search +29% YoY ≈ 71k/mo) | n/a (blocked) | ↑ rising | Adjacent wellness-tok / dermtok community; the gateway term for IE 18–34 audiences and the audience-side translation of #wellageing / #skinlongevity (which are editorial-led). Maps directly onto Anua / BOJ / Round Lab product pages already on IE shelves. |
| #kpharmacy | NEW | est. low-tens M (early, UK-specific cluster) | n/a (blocked) | ↑ rising | Stylist UK 2026: "K Pharmacy is the latest K Beauty trend to know" — Boots UK is expanding K-Pharmacy in 2026 alongside K-Fragrance and K-Haircare. UK-specific, IE-relevant via Boots IE adjacency. Sudden riser. |
| #jellycleanser | NEW | est. low-tens M (top-3 fastest-growing skincare hashtag June 2026 per WWD-cited Spate report) | n/a (blocked) | ↑ rising fast | Sudden riser (#1 of top-3 fastest-growing alongside #lipexfoliator and #neckcream). Direct K-beauty product fit: BOJ jelly-foam cleanser, Numbuzin, Pyunkang Yul. Easy verdict-format hook. |
| #cleantok | NEW | est. ≥ 50 B (mega adjacent community) | n/a (blocked) | → flat-large | Adjacent community named in routine brief. Cross-pollination with #skintok / #skinbarrier means brand-trust messaging carries; "clean ingredient" framing fits skinimalism 2026. |
| #slugging | NEW | est. ~3 B | n/a (blocked) | ↑ rising | Barrier-repair adjacent; K-origin (the Vaseline-overnight trick reframed via Aestura ATO Barrier Balm / Anua Heartleaf 80 Pore Control Cleansing Oil + occlusive). Reinforces the #skinbarrier wedge and gives a concrete demo format. |

## Faded / declining hashtags

**None this cycle.** No prior `tag-content-tracker.md` snapshot exists, so the 3-consecutive-day fade clock has not yet started. All 5 carry-forward tags above are at Day 1 of the fade clock; earliest possible `faded` call: 2026-06-10. Earliest possible `declining` flag on top-5 hashtags: 2026-06-09 (need at least Day-2 + Day-3 deltas).

Day-1 candidates to *watch* for early fade signals once data unblocks:
- **#dollyskin** — niche aesthetic; Refinery29 / Beauty Independent flagged "bloom skin" as the editorial 2026 successor (per yesterday's `eod-briefing.md` contradiction note H13). If #bloomskin overtakes #dollyskin in a creator-led video within 7 days, drop #dollyskin.
- **#wellageing** — copy-lag risk: it's an editorial term, not how 18–34 IE creators tag their barrier content. #skinbarrier (NEW) is the audience-side substitute. If #wellageing has zero Top-50 UK uses by Day 5, flag declining.
- **#nadplus** — early ingredient. If Medicube NAD+ duo paid push doesn't lift the tag past low M by Day 7, flag declining for the IE wedge (still hold for UK paid).

## Format × K-beauty intersection (top 5 combos)

Ranked by combination of (a) ER signal in yesterday's FastMoss 200+ video sample, (b) IE-retail groundability, and (c) discovery-page evidence on TikTok:

1. **#gurwm + #koreanskincare + #beautyofjoseon** — the top-ER combo in the day-1 sample (#gurwm ER 8.54%, BOJ organic-first GTM). The IE wedge: a Sissel Lab Dublin walk-through using #gurwm framing with BOJ Relief Sun as the protagonist. Highest expected ER per impression of any combo in the day-1 working set.
2. **#verdict + #pdrn + #anua + #vs** — "Anua niacinamide v BOJ glow serum" / "Round Lab v Medicube PDRN" verdict-format on the rising #pdrn meme-wave ("molecules too large"). H1 (verdict format) is now the highest-confidence finding of Day 1. Easiest format to ship in volume.
3. **#unboxing + #medicube + #bootsireland** — paid+organic balance leader. Medicube has the safest brand-partner profile (7.8 M UK paid + Frishta 446k organic). #bootsireland is the only IE-mass retail tag with K-beauty depth. UGC-feel haul of the Boots IE K-aisle in Dublin/Cork.
4. **#firstimpressions + #jellycleanser + #beautyofjoseon** — leverages the day's sudden-riser tag (#jellycleanser) on the most velocity-rich K-cleanser SKU on IE shelves. First-impression format is the lowest-resistance entry into the rising tag while it's still small enough that a UK/IE creator can dominate Top-9.
5. **#skintok + #skinbarrier + #anua + #cosrx** — long-tail evergreen combo, anchors on the NEW gateway term (#skinbarrier) and the two K-brands already established as barrier-repair anchors in UK chatter. Lower peak views but high comments-to-views ratio (audience self-skeptical, asks questions in comments per yesterday's "voice of the customer").

## #gurwm deep-dive (engagement vs #grwm)

| Metric | #grwm | #gurwm | Read |
|---|---|---|---|
| Estimated total views | ≥ 80 B (top-tier evergreen) | low-single-digit B (still emerging) | #grwm is the trunk, #gurwm is the new high-yield branch. |
| Day-1 FastMoss-sample ER (28d K-skincare pool, source: `day1-brief.md`) | low single-digit % | **8.54%** — top ER tag in the working set | #gurwm rewards per-video attention 2–4× harder than #grwm in K-skincare context. |
| Format intent | "get ready with me" — broad lifestyle/makeup; skincare often background | "getting un-ready with me" / "get unready with me" — explicitly nighttime, removal/cleanse-first, K-routine native | #gurwm is structurally a *cleanse + 7-step + serum* template. Made for K-skincare. |
| Audience overlap with IE 18–34 women | high but diffuse | high and tight — converts cleanly with K-skincare 7-step product line-ups, which is the lifecycle stage 18–34 IE women are at | The IE-relevant audience is concentrated where #gurwm already lives. |
| Saturation risk | very high (everybody tags #grwm) | low — Top-50 UK pool not yet locked | First-mover window still open for a serious UK/IE K-creator. |
| Brand-fit signal (from yesterday) | All K-brands | Strongest read-across to BOJ, Anua, COSRX (cleansing), Aestura (occlusive), nighttime-routine creators | #gurwm is the night-routine pair to #morningroutine; pairs naturally with #nightroutine + #skinbarrier (NEW). |

**Working recommendation**: Tag every nighttime-routine and barrier-repair piece with **`#gurwm` first, `#grwm` second** for the next 14 days. Lead-tagging matters for FYP attribution. Watch for #gurwm Top-50 lock-in by Day 7 — once locked, the leverage advantage halves.

## Content strategy notes (IE 18–34 women)

*All three actionable in the next 7 days; each grounded in a tag-pair surfaced above and a SKU buyable in Dublin/Cork.*

1. **Ship a #gurwm × #skinbarrier × #beautyofjoseon nighttime-routine cut from inside Sissel Lab Dublin within the week.** This stacks the day's highest-ER format tag (#gurwm at 8.54% ER), the day's NEW gateway audience tag (#skinbarrier — the audience-side translation of #wellageing that 18–34 IE women actually use), and the most velocity-rich SKU on the IE shelf (BOJ Relief Sun / Dynasty Cream, sells out weekly at Sissel Lab per `ireland-signal.md`). The structural lesson is the convergence rule: #gurwm is uncontested in the IE K-skincare cluster, #skinbarrier is rising fast, and BOJ has 0 UK paid views but organic groundswell — meaning a credible organic verdict piece will not collide with a paid push that would dilute it.

2. **Build the #verdict × #vs × #pdrn franchise around the "molecules too large" meme-line before the first IE creator gets there.** H1 (verdict beats haul) is now the highest-confidence Day-1 finding (3 of 4 source files), and #pdrn is the most-watched ingredient tag in the K-cluster (1.9 M weekly posts). The format is a 60-second "Anua niacinamide v BOJ glow serum v Medicube PDRN — which actually does what it says for IE 18-34 skin?" verdict, ideally with a dermatologist face card (Prof Ryan / Prof Ralph at Institute of Dermatologists — open outreach noted in `eod-briefing.md`). Tag order: `#verdict #pdrn #vs #pdrnskincare #kbeauty #bootsireland`. This locks the IE PDRN-credibility cluster before someone else does and converts the rising tag into a credentialed take rather than another "I tried it for a week" thinkpiece.

3. **Hijack the day's sudden-riser tag (#jellycleanser) with a #firstimpressions Penneys-vs-BOJ-vs-Numbuzin cleanser shoot for IE pharmacy + fast-fashion audience.** #jellycleanser is one of the top-3 fastest-growing skincare hashtags June 2026 (WWD-cited Spate). The hashtag is currently small enough that a single UK/IE creator video with strong watch-time can lock the Top-9 — but that window will close fast. Pair with Penneys PS… K-Beauty (IE fast-fashion own-label, available now), BOJ jelly-foam cleanser (Sissel Lab + Boots IE), and Numbuzin No.3 Soft Foam Cleanser (Cult Beauty IE) — three price ceilings, one bucket. Tag order: `#jellycleanser #firstimpressions #vs #bootsireland #kbeauty #skintok`. This is the lowest-effort piece that gets us first-mover on a rising tag while we set up the longer-arc verdict series in (2).

## Data quality

**Status: PARTIAL — direct hashtag fetches blocked, fell back to indexed reports.**

What was attempted:
1. `WebFetch https://www.tiktok.com/tag/{kbeauty,gurwm,glassskin}` → all 403.
2. `WebFetch https://ads.tiktok.com/business/creativecenter/hashtag/skincare/pc/en?countryCode=GB&period=7` → 403.
3. `WebFetch display-purposes.com/hashtag/glassskin` → ECONNREFUSED.
4. `WebFetch https://www.qogita.com/blog/tiktok-beauty-trends-2026/`, `accio.com`, `wwd.com`, `trendingus.com` → all 403.
5. `WebSearch` fallback worked for narrative confirmation but does not return numeric view-totals per hashtag.

What did land:
- Spate-cited rollup (via Stylist UK, TikTok Newsroom EN-GB, Cosmetics Business, WWD): "K-beauty / Korean skincare ~2.5 B weekly views; +125% UK search H2-2025; #kbeauty 3rd-most-used UK beauty hashtag."
- WWD-cited Spate report: top-3 fastest-growing skincare hashtags June 2026 = **#lipexfoliator, #jellycleanser, #neckcream**.
- Stylist UK: K-Pharmacy is the named Boots UK 2026 K-trend → #kpharmacy emerging.
- Spate-cited (via WorldHealth.net / Doctor Rogers): #pdrn at 1.9 M weekly TikTok posts.
- yesterday's `day1-brief.md` FastMoss 28d sample: #gurwm ER 8.54% (top ER tag in K-skincare working set), #grwm low single-digit % ER.
- yesterday's `eod-briefing.md` line 38: "active hashtag inventory" provided the 5-tag carry-forward seed.

Diagnosis (unchanged from `trends-uk-ie.md` earlier today): managed remote-execution container's outbound network policy 403s Google, TikTok, all aggregator hosts. Below `urllib` / `WebFetch`, not solvable in-process. See `trends-uk-ie.md ## Data quality` for the three-step fix path (loosen policy → self-hosted scrape-proxy → swap-in alternate signals).

Tomorrow's run will: (a) re-attempt TikTok tag pages in case the policy was loosened; (b) if still blocked, populate from FastMoss raw JSON (which is local-fetchable when Soomin pushes `fastmoss_raw/`) for view + ER deltas on the BASE + CARRY-FORWARD set; (c) start the 3-day fade clock at Day 2 for the 5 carry-forward tags; (d) snapshot the 5 NEW tags' Day-1 position so we can call rising / declining from Day 3.

Sources consulted today:
- [Stylist UK — K-Pharmacy is the latest K-Beauty trend to know](https://www.stylist.co.uk/beauty/skincare/k-pharmacy-k-beauty-at-boots/1060238)
- [TikTok Newsroom EN-GB — From Glass Skin to British Favourites](https://newsroom.tiktok.com/tiktokshopbeautycrush?lang=en-GB)
- [Cosmetics Business — TikTok Shop UK 60% beauty sales growth driven by K-beauty](https://cosmeticsbusiness.com/tiktok-shop-report-kbeauty-driven-sales-growth)
- [WWD — #Koreanskincare, #Perfume among top beauty hashtags on TikTok Shop](https://wwd.com/beauty-industry-news/beauty-features/tiktok-shop-beauty-sales-medicube-dr-melaxin-skincare-1238690578/)
- [Boots UK Newsroom — 2026 Beauty & Wellness Trends Report](https://www.boots-uk.com/newsroom/news/boots-releases-2026-beauty-wellness-trends-report-alongside-line-up-of-trending-new-brands/)
- [Qogita — Top TikTok Beauty Trends 2026](https://www.qogita.com/blog/tiktok-beauty-trends-2026/)
- [Doctor Rogers Skin Care — Slugging: the TikTok trend with dermatologic roots](https://www.doctorrogers.com/blogs/blog/slugging-the-tiktok-trend-with-dermatologic-roots)
- [WorldHealth.net — Study ranks TikTok's most viral skincare ingredients](https://worldhealth.net/news/most-viral-skincare-ingredients-best-to-worst/)
- Internal: `daily_data/2026_06_06/eod-briefing.md`, `day1-brief.md`, `ireland-signal.md`, `content-hypothesis.md`; `daily_data/2026_06_07/trends-uk-ie.md`, `tiktok-sounds.md`.

---

Saved to repo: `daily_data/2026_06_07/tag-content-tracker.md`
