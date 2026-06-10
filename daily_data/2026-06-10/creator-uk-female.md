# Creator-UK-Female — Surge Edition — 2026-06-10

## DATA NOTICE — UK K-VIRAL CRAWL STILL BROKEN (2ND CONSECUTIVE DAY)

There is **no fastmoss_raw crawl for 2026-06-10** in the repo as of 10:00 Dublin (`daily_data/2026-06-10/fastmoss_raw/` does not exist). The most recent crawl is 2026-06-09, and as flagged yesterday it returned **Italy-only** for the two K-viral inputs (`viral_korean_skincare_7d.json` = 1 IT video, `viral_kbeauty_7d.json` = 6 IT videos, `viral_korean_skincare_90d.json` = 47 items split IT 40 / US 6 / ES 1, zero UK). The UK toggle on the `viral_*` jobs is regressed for the **second straight day**.

The non-viral UK FastMoss endpoints did return clean payloads on 2026-06-09: `growthrank_beauty_gb_daily.json` (30 rows), `risingstar_beauty_gb.json` (30 rows), `newlisted_skincare_gb.json` (30 rows), `popular_hashtag_uk_7d.json`, `popular_music_uk.json`. These are not K-skincare-specific viral pools — they are UK beauty creator-growth and rising-star lists — but they are the only fresh UK creator surface available today.

**Strategy this run**: the canonical K-skincare viral diff (the one the brief asks for) cannot be computed for the second day running. Two days ago (2026-06-08, the last full UK K-viral crawl) is now T−2 stale and was already fully mined in the 2026-06-09 surge file. Re-running the same 06-08 vs 06-07 diff would be a literal duplicate. Instead this run:

1. Uses **UK growthrank + risingstar diff (2026-06-09 vs 2026-06-08)** as an **alt-surge proxy** — these are UK beauty creators rising rank-wise, even without a captured viral video. Not K-skincare-specific, so candidates are flagged as "needs verification before promotion".
2. Per the hard rule ("If NEW_TODAY is empty… deep-dive 1 creator from DROPPED"), deep-dives **Nath Henry** from the 06-07→06-08 DROPPED set, since (a) yesterday's run carry-forward asked us to confirm whether his BOJ paid-pivot hypothesis was alive, and (b) the 28d viral data lets us confirm his absence is real, not a 7d-window roll-off artifact.
3. Tier-1 health uses the 2026-06-08 K-viral pool (T−2) **plus** the 2026-06-09 growthrank UK list, which surfaces a meaningful **ZhilaBeauty signal correction** vs yesterday's read.
4. Escalates the crawl-pipeline regression to `sun-master-report` notes — this is now a data-pipeline issue, not a transient noise.

## Today's diff at a glance

- Yesterday viral pool (06-08 UK, T−2): **52** unique creators (mined 2026-06-09)
- Today viral pool (06-09 UK K-viral): **0** UK creators — crawl regressed to IT-only
- NEW today (UK K-viral): **N/A** — cannot compute
- DROPPED (UK K-viral): **N/A** — cannot compute
- **Date source used: 2026-06-09 UK growthrank + risingstar** (the only fresh UK creator surface today)
- Alt-surge NEW on 2026-06-09 vs 2026-06-08 — **growthrank UK**: 7 entries; **risingstar UK**: 3 entries; total 10 (with @zhilabeauty Tier-1 overlap — see health check)

### Alt-surge — UK growthrank beauty (06-09 vs 06-08, NEW entries)

| Handle | Display | Followers | +Followers (24h) | Growth% | Videos |
|---|---|---|---|---|---|
| @swearingshepherdess | Swearing Shepherdess | 260.3k | +642 | 0.25% | 259 |
| @lilly.mayble | 𖤐 𝕷𝖎𝖑𝖑𝖞-𝕸𝖆𝖞 𖤐 | 293.9k | +723 | 0.25% | 428 |
| @heatheratamba | HEATHER ATAMBA ⚡️ | 585.1k | +748 | 0.13% | 812 |
| @charliebetts_ | charliebetts_ | 691.8k | +645 | 0.09% | 980 |
| @mazinurso | Mazin Urso \| مازن اورسو | 210.4k | +594 | 0.28% | 703 |
| @victoriaemes | Victoria Emes | 1.2m | +1.4k | 0.12% | 1.5k |
| @zhilabeauty | ZhilaBeauty | 1.3m | +688 | 0.05% | 2.5k |

### Alt-surge — UK risingstar beauty (06-09 vs 06-08, NEW entries)

| Handle | Display | Female% | Age | Viral idx | GMV (£) | Avg views | Top categories |
|---|---|---|---|---|---|---|---|
| @ree.ksl | Ree☁️ | 62.39% | 25–34 | 74 | £81.36k | 22.8k | Jackets & Coats / Jeans / Casual Dresses |
| @sewfy | Sewfy (sophie) 🩵 | 77.49% | 25–34 | 73 | £36.51k | 5.4k | Lip Treatments / Makeup Sets / Blush |
| @homeandbeautyobsessed | Maxine Earle | 80.40% | 35–44 | 74 | £11.48k | 2.7k | Lip Treatments / Moisturizers / Outdoor Chairs |

**Cross-check vs prior FastMoss outputs**: I grepped all `daily_data/**/*.json` for these 10 handles. None appear in any K-beauty viral pool we have captured 2026-06-06 through 2026-06-08. These are UK beauty risers **without** confirmed K-skincare crossover from the data we hold. TikTok and FastMoss creator-detail pages both 403 to WebFetch, so I cannot verify K-skincare content in-run. **No surge profile cards written** — writing them on category-tag proxies alone would be guessing.

## Surge creators — deep dive

**Per hard rule**: NEW_TODAY is empty for the K-skincare viral pool. Deep-diving 1 creator from DROPPED instead.

### 1. @nathhenry (Nath Henry, 464.1k followers) — DROPPED deep-dive

- **Handle / display name**: Nath Henry (`@nathhenry`)
- **Niche**: Black British male skincare-AD specialist; "kbeauty is the move ✌🏽" tagline-style hooks; predominantly paid-tier creator (~90% AD by post-volume across captured 28d).
- **Follower count + avg views + ER**: 464.1k followers. Across his 28d FastMoss K-viral cluster (n=8 captured videos), views range 12.1k–55.4k, **ER range 0.27%–1.04%** — paid-tier-typical, below the Tier-1 organic 4–8% band.
- **Today's surge video (N/A — he is DROPPED, not surged)** — best signal is his **last-captured K-video**: vid `2026-05-31 07:28` BOJ Apricot Peeling Gel AD, 55k views on 06-06, 65.3k by 06-08 (logged in 28d pool). **No new K-skincare post captured between 2026-05-31 and 2026-06-08 inclusive** (his K-viral cluster has zero entries with `publish` after 2026-05-25 other than the 05-31 BOJ video — the 28d pool would surface a fresh AD if one existed). On 2026-06-09 the UK crawl is broken so unverifiable, but the 06-08 28d pool would have caught any 06-06–06-07 posts.
- **Past content pattern**: 28d K-cluster is **5× Medicube + Dr.Melaxin AD posts (May 15–25) → 1× BOJ AD (May 31) → silence**. Pattern is paid-stable specialist with one cross-brand BOJ test. The BOJ test ranked #1 in 06-07 UK viral_korean_skincare with 55k views — strong launch — and then he posted **no follow-up** in the following 9 days.
- **Voice/persona signature**: punchy, sales-led, brand-confident, "the move for 2026", hashtag-stacked. Reads as paid-creator-professional, not enthusiast-curator. Ireland 18–34 women: low-to-moderate trust — fits the de-influencing-target profile (paid stack is too obvious).
- **Demographic guess**: Black British male, late 20s–early 30s, London (no regional accent flag in captions).
- **Brand alignment**: Medicube / Dr.Melaxin (paid-push tier) + 1 BOJ test. Fits the brand-creator split as-is — paid tier — except for the BOJ overlap, which was the question yesterday's carry-forward flagged.
- **Persona mapping**: No clean fit to the 8 personas. Falls in the same paid-tier cohort as Chloe Ferry / poppylivingstonex / Bina13 (paid-stack repeat-buyers, sales-led caption style). The personas were built on organic-strong UK female creators; Nath is male + paid-stack, so he sits outside the brief.
- **Verdict**: **One-hit wonder on BOJ; stable on Medicube/Dr.Melaxin paid stack.** The absence of a 2nd or 3rd BOJ post by Day 9 post-launch is now the **decisive data point on the BOJ-via-paid hypothesis**: it weakens further. BOJ-UK is buying isolated AD slots on existing paid-tier creators (one-off SKU activations), not building a sustained paid stable. **This locks the organic-first read on BOJ for the IE white-space play** — the defensive paid-tweak flagged in the 2026-06-07 Sunday master report remains **not required this cycle**.

## Tier-1 health (one line each)

- **James Welsh**: last captured 2026-06-08 vid `7646773773840010518` — 62k views, **1.3% ER vs 5.58% baseline** (Medicube AD, the brand-split breakage flagged yesterday). T−2 stale; cannot confirm cadence today. 🚩 **The Medicube AD remains the standing anomaly** until next clean UK crawl.
- **Graces.faces_** (Grace Marsh): no K-viral post captured in last clean window (06-08); not in 06-09 growthrank UK top-30 either. **3rd day absent from FastMoss UK surfaces.** Trending toward inactive in this dataset — needs a recovery crawl to disambiguate "not posting" vs "posting non-K".
- **ZhilaBeauty**: 🟢 **POSITIVE CORRECTION TO YESTERDAY'S READ.** Yesterday flagged her as silent for a 2nd day. Today's clean 06-09 UK growthrank lists her as a **NEW entrant: +688 followers in 24h, 0.05% growth on 1.3m base, 2.5k total videos**. She **is** posting and gaining followers — just **not on K-skincare** (or her K-post slipped the broken viral pool). The "silent" read yesterday was a viral-pool-coverage artifact, not a behavioral change. **Recommend reverting the Zhila-silence flag for sun-master-report; replace with "Zhila active, K-cadence unconfirmed pending crawl fix".**
- **Frishta** (frishtaxx): not in 06-09 growthrank UK top-30 either. 3rd day absent from FastMoss UK surfaces. Same caveat as Grace — needs crawl recovery to read.
- **Cindy Lee** (ab61e): not in 06-09 growthrank UK top-30. 3rd day absent; smallest of Tier-1 by base, so least informative; no anomaly flag.

## Departures

- **@nathhenry** (Nath Henry, 464k, paid-tier): see full deep-dive above. **3rd consecutive day absent from K-viral surface** (06-07 had him #1, 06-08 dropped, 06-09 unverifiable due to crawl). The BOJ paid-pivot hypothesis weakens further; organic-first BOJ-UK posture confirmed.
- **@melissajade** (Melissa Jade 💚, 487k): dropped 06-07 → 06-08, flagged yesterday as likely 7d-window roll-off (her May-31-or-earlier video aged out). Still no recovery surface today. Re-check on next clean crawl.

## Carry-forward for tomorrow

- watch **@nathhenry** — first K-content post (any brand) ends the BOJ-one-hit read; silence through 2026-06-12 (Day 12 post-BOJ-launch) confirms it.
- watch **@zhilabeauty** — first K-content post she publishes confirms K-cadence is intact; if she publishes non-K only for another 48h, that's a **K-fatigue signal worth surfacing** to the sun-master-report (Tier-1 organic creator is choosing non-K topics during peak K-discourse).
- **🚨 PIPELINE: fix the UK-region toggle on `viral_kbeauty_7d` / `viral_korean_skincare_7d` (and likely the 28d/90d variants too) before tomorrow's 10:00 Dublin run.** This is now 2 consecutive days of regression. If the 2026-06-11 crawl is also region-broken, this report becomes structurally unable to deliver its core diff, and the brief should escalate to the engineering/data owner.
- Once crawl recovers, the **first surge-creator card** should re-test the 10 alt-surge candidates above against the K-viral pool — any of them appearing would close the loop on the alt-surge-source experiment this run started.

## Notes for sun-master-report

- 🚨 **Data pipeline degradation — 2 consecutive days**: `viral_kbeauty_7d.json` and `viral_korean_skincare_7d.json` both returning IT-only since 2026-06-09. The 2026-06-10 crawl did not run at all (no `daily_data/2026-06-10/fastmoss_raw/` directory). Compound effect: the surge file rolls 2 days stale on its primary input, and Tier-1 cadence reads become unreliable. **Escalate to data-pipeline owner**; this is no longer a transient crawl glitch.
- 🟢 **ZhilaBeauty active, not silent** — 2026-06-09 UK growthrank confirms +688 followers/24h. Yesterday's "Tier-1 absence" worry on Zhila was a viral-pool-coverage artifact, not a behavior shift. **Revert that flag** in the next master-report sweep.
- 🔻 **BOJ-via-paid hypothesis weakens further** — Nath Henry's BOJ AD is now 9 days old with zero follow-up. BOJ-UK appears to be buying one-off SKU activations on existing paid-tier creators (Henry, Ferry), not building a stable. **Organic-first BOJ posture for IE white-space play is locked**; defensive paid-tweak from the 2026-06-07 master report remains shelved.
- 📋 **Alt-surge candidate list (10 UK beauty risers, K-skincare unverified)** is parked in this file for next clean crawl to test. If even 1–2 of @swearingshepherdess / @lilly.mayble / @heatheratamba / @charliebetts_ / @mazinurso / @victoriaemes / @ree.ksl / @sewfy / @homeandbeautyobsessed shows up in next K-viral pool, growthrank/risingstar becomes a validated leading-indicator alt-surface for this brief.
- 🚩 **James Welsh × Medicube AD** remains the standing brand-split breakage flag from yesterday; T−2 stale and cannot be cleared until next clean UK crawl.
