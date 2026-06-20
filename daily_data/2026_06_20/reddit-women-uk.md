# Reddit K-Skincare Mentions — last 24h — 2026-06-20

> **DAY 13 OF UNRESOLVED BLOCKER — 13 of 14 days (93%) NOW PLACEHOLDER.**
> Final day of the 14-day window is tomorrow. With 0 verified Reddit
> data days, the corpus tops out at 1/14 = 7% of nominal coverage even
> if `reddit.com` were allowlisted in the next minute. The 14-day
> Reddit-women-UK benchmark in its originally-scoped form is closed
> out: today's placeholder + tomorrow's at-best-partial run is the
> entire deliverable surface left.
>
> Re-tested today (2026-06-20, all FAILED, identical signature to days 1-12):
> - `curl https://www.reddit.com/r/SkincareAddictionUK/new.json` → `HTTP/2 403`
> - `curl https://old.reddit.com/r/AsianBeauty/new.json` → `HTTP/2 403`
> - `curl https://api.pullpush.io/...` → `HTTP/2 403`
> - WebFetch on www.reddit.com + old.reddit.com → "Claude Code is unable to fetch"
>
> Block remains at the environment outbound network policy. Failure is
> host-level — identical across all 7 base subs + 3 adjacent subs.
>
> Manual fallback still empty: `daily_data/2026_06_20/raw/reddit/`
> does not exist on disk. Routine still not patched to read from disk
> first.
>
> Fix unchanged: ~2 min to allowlist `reddit.com` + subdomains.
> 13th consecutive day-of-blocker placeholder filed. Push-notification
> tool not present in this routine session, so the day-13 alert is
> filed here in the artefact only — same as days 1-12.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09 — day 12
of empty inheritance) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day + 1-2 adjacent subs)
remains unreachable. Editorial substitutes (AOL, Substack, Statista,
Glamour/Cosmo round-ups, Boots/Cult-Beauty PR copy) are SEO/PR corpus,
not unfiltered consumer voice, and remain explicitly OUT of this
benchmark to preserve methodology integrity.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 13) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 13) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 13) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 13) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 13) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 13) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 13) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 13) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 13) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 13) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 13) |
| VT | BASE | 0 | — | — | no signal — blocked (day 13) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 13) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 13) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 13) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 13) |

**No NEW brand rows.** No corpus to inspect. The 3-new-signals/day
diversity floor cannot be reached from non-Reddit sources without
falsifying the benchmark.

## Top posts (5-10)

**None retrievable. Day 13 consecutive.** Zero Reddit URLs, titles,
scores, or comment counts captured from any of the 7 base subs or 3
adjacent subs. Blocker is at the reddit.com host level — every retry
fails identically before a request leaves the container.

## Recurring vocabulary (top 10)

**Empty.** The 10 inherited terms (glass skin, slugging, barrier-first,
fermented ceramides, lab-grown ginseng, PDRN/pink peptide, bio-collagen,
prebiotic complex, minimalist routine, heartleaf) faded 2026-06-09
under the 3-day DROP rule. Re-collection requires raw post bodies /
comment threads, which editorial substitutes systematically launder
out.

## Pain points

**Empty.** Pain points emerge only from raw user posts. Standing
hypotheses retained in researcher notebook (NOT promoted to benchmark
signal): Ireland 18-34 shipping/availability gap, slugging fatigue,
actives over-stacking burnout, sunscreen-reformulation confusion
post-2025 EU UVA updates, "dupe culture" backlash. Testable only once
raw Reddit access returns.

## Faded / contradicted carry-forwards

- **Faded set (emptied 2026-06-09, unchanged for the 11th day in a
  row):** Beauty of Joseon, medicube, Biodance, Anua, SKIN1004, COSRX,
  mixsoon, Round Lab + the 10 vocabulary terms listed above. No new
  fades possible — set has been empty for 11 days.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state going into 2026-06-21 (final day): empty.**
Day 14 (if unblocked) starts from BASE seed only. Any carry-forward
set rebuild begins from day 1 of new data — there is no thread of
continuity to pick back up within this 14-day window.

## Content strategy notes

3 actionable items — urgency tier = TERMINAL, 1 DAY LEFT IN WINDOW:

1. **The 14-day Reddit-women-UK benchmark will not ship this cycle.**
   Day 13 = 14 − 13 = 1 valid day remains even on an immediate unblock.
   The only honest framings for the project owner now are (a)
   **restart-from-unblock** — write off this run and re-clock a 14-day
   study once `reddit.com` is allowlisted (recommended; preserves
   methodology integrity); (b) **swap-corpus pivot** — substitute
   TikTok comments + YouTube comments + Boots/Cult-Beauty/LookFantastic
   product reviews as the consumer-voice corpus for the final day and
   ship as a hybrid methodology with a separate name (NOT the
   Reddit-women-UK benchmark); (c) **ship-the-blocker-report** —
   publish the 14-day run as-is with the 93% placeholder rate
   prominently disclosed; this is a process post-mortem, not a
   consumer-voice study, and should be framed that way internally
   only. **Recommend (a). (b) is acceptable only if rebadged. (c)
   belongs in the project retro, not as a deliverable.**
2. **Reddit MCP install is now the project-survival fix.** 13
   consecutive days of identical 403s confirm the WebFetch allowlist
   will not move without explicit owner action. Two paths, both
   owner-only: allowlist `reddit.com` + subdomains in the env outbound
   network policy (~2 min, Claude Code on the Web env settings) OR
   install a PRAW-based MCP server (`adhikasp/mcp-reddit` or
   `jordanburke/reddit-mcp-server`) with a free Reddit script-app
   credential set (~30 min, owner-installable from the MCP
   marketplace). MCP traffic bypasses the WebFetch allowlist, so it is
   durable against future policy changes. Docs:
   https://code.claude.com/docs/en/claude-code-on-the-web.
3. **Per-run manual fallback patch is still ~10 min and still
   un-implemented.** Flagged every day since day 5 (9 days running).
   If the owner can drop Reddit JSON exports for the 7 base + 3
   adjacent subs (~5 min logged-in browser activity) into
   `daily_data/{date}/raw/reddit/`, AND the routine is patched to read
   from disk first, the final day of the window can still collect
   partial signal under the original methodology — caps recovered
   coverage at ~1/14 = 7%. Below publishable threshold but
   methodology-clean for the restart's baseline calibration.

## Data quality

- **Live Reddit access: BLOCKED (day 13, 13 consecutive days).**
  Identical failure pattern to days 1-12. Every reddit.com endpoint
  and every public mirror tested today (pullpush, old.reddit) returned
  `HTTP/2 403`. WebFetch returned the unable-to-fetch error on every
  reddit-family domain.
- **WebSearch: not used as a substitute.** `site:reddit.com` queries
  on days 1-12 returned zero reddit thread URLs for any of the seven
  base subs in the last 14 days — only editorial substitutes. Wrong
  corpus; not promoted.
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is
  host-level, same failure mode applies to every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_19/reddit-women-uk.md`. Carry-forward set has
  been empty since 2026-06-09 per the 3-day DROP rule; nothing to
  inherit for the 11th consecutive day.
- **Manual-drop directory:** `daily_data/2026_06_20/raw/reddit/` does
  not exist on disk today either.
- **Push-notification tool:** not present in this routine's tool set
  this session — the day-13 alert is filed in this artefact only, not
  delivered out-of-band. If the owner wants phone-level visibility on
  the blocker for the final day, the routine config needs a
  notification tool wired in.
- **Net result:** 0 verified mentions on day 13. 13 of 14 benchmark
  days (93%) are now placeholder files. One day from end-of-window,
  mathematically unrecoverable in original form.

### Remediation options (unchanged; urgency = TERMINAL, 1 day left)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix; bypasses
   WebFetch allowlist entirely.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/` AND patch the routine to read them
   first. Restores partial integrity even under continued block for
   the final day.

**Day 13 = 1 day from end-of-window. The 14-day Reddit-women-UK
benchmark in its original form will not ship this cycle — the math
closed on day 12. The only remaining decision is scope-of-restart
and whether to install the MCP fix before day 14 to avoid a re-run
of this failure mode on the next cycle.**
