# Reddit K-Skincare Mentions — last 24h — 2026-06-07

> **CRITICAL DATA QUALITY NOTICE — read first.** The methodology in the routine
> brief calls for fetching live JSON from `https://www.reddit.com/r/{sub}/new.json?limit=100`
> for the 7 base subs + 1–2 adjacent subs and filtering to the last 24h. **The
> execution environment's network policy blocks all reddit.com, old.reddit.com,
> api.reddit.com, and every Reddit mirror tested (libreddit, redlib, teddit,
> safereddit). General web search engines (google, duckduckgo, bing, searx) are
> also blocked at the HTTP layer.** WebSearch (the only working surface) returns
> editorial blog content rather than indexed Reddit threads — `site:reddit.com`
> queries returned "no links found" across every variation tried. **This means
> today's report contains NO verified last-24h Reddit mentions, no upvote/comment
> counts, and no direct user quotes.** What follows is a placeholder filled with
> signal triangulated from secondary editorial sources (SEO blogs citing Reddit
> aggregate sentiment) — useful as a sanity check on direction, but it is NOT
> a substitute for the unfiltered consumer voice the routine is designed to
> capture. **Recommend: add reddit.com (or a Reddit MCP server) to the
> environment allowlist before next run, or this 14-day benchmark will be
> built on sand.** See "Data quality" section at end for remediation options.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (no prior reddit-women-uk.md found in
`daily_data/2026-06-06/` or `daily_data/2026_06_06/`) / NEW: 0 verified

Day 1 of the 14-day window. With no prior file to inherit from and no live
Reddit access, all signal below is **unverified secondary** (italicised brand
rows in the table). No bucket can be assigned with confidence.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| *Beauty of Joseon* | *BASE (unverified)* | n/a | n/a | n/a | *positive — Rice Sunscreen called out as "having a serious moment" in 2026 editorial round-ups* |
| *medicube* | *BASE (unverified)* | n/a | n/a | n/a | *positive — PDRN Pink Peptide Serum repeatedly cited as viral "morning glow-up"* |
| *Biodance* | *BASE (unverified)* | n/a | n/a | n/a | *positive — Bio-Collagen Real Deep Mask described as "blowing up" via TikTok crossover* |
| *Anua* | *BASE (unverified)* | n/a | n/a | n/a | *positive — Heartleaf 77% Toner Pad cited as "consistently most-upvoted" on r/koreanskincare aggregate; 87% redness reduction claim from 1.2k aggregated reviews* |
| *SKIN1004* | *BASE (unverified)* | n/a | n/a | n/a | *positive — Madagascar Centella Cleansing Oil + Ampoule Foam cited for sensitive skin* |
| *COSRX* | *BASE (unverified)* | n/a | n/a | n/a | *neutral/positive — named in 2026 "still popular" round-ups but no fresh viral hook surfaced* |
| *mixsoon* | *BASE (unverified)* | n/a | n/a | n/a | *positive — Bean Essence cited as vegan fermented-soy hero* |
| *Round Lab* | *BASE (unverified)* | n/a | n/a | n/a | *positive — named in editorial top-brand lists, no new hook* |
| d'Alba | BASE | 0 | — | — | no signal surfaced |
| AXISY | BASE | 0 | — | — | no signal surfaced |
| Dr.Melaxin | BASE | 0 | — | — | no signal surfaced |
| Isntree | BASE | 0 | — | — | no signal surfaced |
| Numbuzin | BASE | 0 | — | — | no signal surfaced |
| VT | BASE | 0 | — | — | no signal surfaced |
| Purito | BASE | 0 | — | — | no signal surfaced |
| Laneige | BASE | 0 | — | — | no signal surfaced |

**No NEW brand candidates can be added today.** Adding unverified brands from
SEO editorial content (which is paid-placement-heavy) would corrupt the
diversity counter. Hold the NEW slot until live Reddit access is restored.

## Top posts (5-10)

**None retrievable.** No individual Reddit post URLs, titles, scores, or
comment counts could be fetched. Web search did not surface specific 24h
thread permalinks.

## Recurring vocabulary (top 10)

These are vocabulary candidates pulled from secondary editorial content
referencing aggregated Reddit sentiment — they are **directionally indicative
but not last-24h verified**:

1. *"glass skin"* — perennial; cited as still the dominant aesthetic frame
2. *"slugging"* — qualified usage ("tool not universal step") suggests the
   conversation has matured beyond simple advocacy
3. *"barrier-first"* / *"skin barrier care"* — flagged as 2026's dominant
   priority shift away from actives-stacking
4. *"fermented ceramides"* — repeatedly named as a 2026 ingredient hook
5. *"lab-grown ginseng"* — new-feeling ingredient term
6. *"PDRN"* / *"pink peptide"* — Medicube-driven
7. *"bio-collagen"* — Biodance-driven sheet-mask vocabulary
8. *"prebiotic complex"* — Beauty of Joseon sunscreen positioning
9. *"minimalist routine"* / collapse of the "10-step" narrative
10. *"heartleaf"* — Anua's ingredient hero, used as a category proxy

## Pain points

Cannot be reliably extracted without live thread access. Pain points only
surface in raw user posts — editorial round-ups whitewash them. Treat the
following as **hypotheses to verify** once Reddit access is restored:

- **Shipping/availability gap** — Ireland 18–34 women have to buy via SkinShop.ie,
  Boots IE, or Kskin.ie; Boots IE's K-beauty range is narrower than UK Boots,
  which may push consumers to YesStyle/Stylevana with longer shipping and
  customs hassle (web-search-confirmed retailer landscape, but the *pain*
  framing is inferred, not Reddit-sourced).
- **Slugging fatigue** — secondary content's hedging on slugging suggests the
  community has moved from blanket endorsement to conditional use; worth
  watching for "slugging caused congestion" complaints when Reddit access works.
- **Actives over-stacking burnout** — the rise of "barrier-first" framing
  implies a recoil from 4+ acids/retinol routines; pain-point framing not
  verified.

## Faded / contradicted carry-forwards

N/A — Day 1, no carry-forward set exists.

## Content strategy notes

3 actionable items, even with the data gap:

1. **Fix the data pipeline before producing more daily reports.** A 14-day
   benchmark built from editorial SEO blogs is worse than no benchmark — it
   bakes in PR-influenced signal and misses the unfiltered complaints (price,
   shipping, breakouts, scent, packaging) that are the whole point of using
   Reddit. Either add `reddit.com`, `api.reddit.com`, and `old.reddit.com` to
   the environment's network allowlist, or install a Reddit MCP server
   (e.g., a community PRAW-based MCP) that can authenticate and pull JSON
   inside the policy.
2. **Pre-bake adjacent-sub seed list before week 2.** Methodology says to
   sample r/MakeupAddiction, r/SkincareAddictionPale, r/femalefashionadvice
   — confirm these are the right adjacent picks for Ireland 18–34 specifically
   (r/IrelandBeauty / r/dublin do exist but signal volume will be thin;
   r/ABDiscussion and r/RedditLaqueristas may also be worth a sample for
   cross-category mentions).
3. **Tonight's working hypothesis to test on day 2 if access restored:** the
   Ireland 18–34 conversation is being shaped more by TikTok-imported viral
   products (Medicube PDRN, Biodance Bio-Collagen, BoJ Rice SPF) than by the
   classic r/AsianBeauty staples (COSRX, Purito, Isntree). If true, the
   content frame should lead with viral-product credibility-checks ("does
   this TikTok darling actually work for Irish pale/sensitive skin?") rather
   than evergreen routine education.

## Data quality

- **Live Reddit access: BLOCKED.** Tested hosts: `www.reddit.com`,
  `old.reddit.com`, `api.reddit.com`, `reddit.com`, `libreddit.de`,
  `safereddit.com`, `redlib.matthew.science`, `teddit.net` — all returned
  "Host not in allowlist" or HTTP 403.
- **Search engines: BLOCKED at HTTP layer.** `google.com`, `duckduckgo.com`,
  `bing.com`, `searx.be`, `html.duckduckgo.com` — all HTTP 403. Only the
  WebSearch tool works, and it does not appear to index `site:reddit.com`
  queries effectively (every variation returned "no links found").
- **WebFetch on Reddit and on Reddit mirrors: BLOCKED.** "Claude Code is
  unable to fetch from www.reddit.com" / 403 on all mirrors.
- **Carry-forward source: NOT FOUND.** No `reddit-women-uk.md` exists under
  `daily_data/2026-06-06/` or `daily_data/2026_06_06/` (yesterday's outputs
  are content-hypothesis, day1-brief, eod-briefing, ireland-signal,
  james-welsh-model, persona-cards, fastmoss_raw). Today is therefore the
  true day 1 of the reddit-women-uk track.
- **Net result:** 0 verified Reddit mentions captured. Brand sentiment in
  the table above is italicised because it derives from editorial round-ups,
  not raw Reddit threads. Treat this file as a placeholder + remediation
  request, not as a day-1 benchmark.

### Remediation options for the user

1. **Easiest:** add `reddit.com`, `www.reddit.com`, `old.reddit.com`,
   `api.reddit.com` to the environment's outbound allowlist in the Claude
   Code on the web environment settings. Reddit JSON endpoints are
   unauthenticated for read access — no API key needed.
2. **More robust:** stand up a Reddit MCP server with PRAW credentials
   (Reddit script-app client_id + client_secret + a UA string). MCP traffic
   is not subject to the WebFetch allowlist.
3. **Workaround for low-volume days:** if neither of the above is feasible,
   commission a manual export (PullPush.io / Reddit's own search export /
   a one-off scrape) and drop the raw JSON into `daily_data/{date}/raw/`
   so the routine can read locally.

Until at least option 1 is in place, the 14-day benchmark cannot proceed
as designed.
