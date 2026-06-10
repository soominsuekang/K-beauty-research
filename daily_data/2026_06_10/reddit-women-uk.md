# Reddit K-Skincare Mentions — last 24h — 2026-06-10

> **DAY 4 OF UNRESOLVED BLOCKER. CARRY-FORWARD SET IS EMPTY
> (aged out on 06-09). Day 4 begins from BASE seed only and ends
> at zero — same failure mode as 06-07, 06-08, 06-09.**
>
> Re-tested today: `www.reddit.com/r/{sub}/new.json`,
> `old.reddit.com`, `www.reddit.com/r/{sub}/.rss`, `api.pullpush.io`,
> `libreddit.privacydev.net`, `redlib.catsarch.com`,
> `safereddit.com`, `teddit.net`, `eu.redlib.privacyredirect.com`.
> All returned 403 / "unable to fetch" / ECONNREFUSED.
> WebSearch: 2 `site:reddit.com` variants today — "no links found"
> on both.
>
> **4 of 14 benchmark days lost (~29%).** One day from the
> ≥35% statistical-floor breach. Push notification re-sent.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (set empty since 06-09) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals + 1-2 adjacent subs) cannot
be satisfied. Editorial / news / TikTok sources are not Reddit and
inheriting their signal into this file would corrupt the benchmark
the user explicitly framed as "Reddit = unfiltered consumer voice."

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal surfaced (blocked) |
| COSRX | BASE | 0 | — | — | no signal surfaced (blocked) |
| Beauty of Joseon | BASE | 0 | — | — | no signal surfaced (blocked) |
| d'Alba | BASE | 0 | — | — | no signal surfaced (blocked) |
| AXISY | BASE | 0 | — | — | no signal surfaced (blocked) |
| mixsoon | BASE | 0 | — | — | no signal surfaced (blocked) |
| Dr.Melaxin | BASE | 0 | — | — | no signal surfaced (blocked) |
| Anua | BASE | 0 | — | — | no signal surfaced (blocked) |
| Isntree | BASE | 0 | — | — | no signal surfaced (blocked) |
| Numbuzin | BASE | 0 | — | — | no signal surfaced (blocked) |
| Round Lab | BASE | 0 | — | — | no signal surfaced (blocked) |
| VT | BASE | 0 | — | — | no signal surfaced (blocked) |
| Purito | BASE | 0 | — | — | no signal surfaced (blocked) |
| SKIN1004 | BASE | 0 | — | — | no signal surfaced (blocked) |
| Biodance | BASE | 0 | — | — | no signal surfaced (blocked) |
| Laneige | BASE | 0 | — | — | no signal surfaced (blocked) |

**No NEW or CARRY-FORWARD rows today.** Carry-forward set was emptied
on 06-09 by the 3-day fade rule. Diversity floor cannot be met from
non-Reddit sources without inflating confidence.

## Top posts (5-10)

**None retrievable.** Day 4 in a row. Zero Reddit URLs, titles,
scores, or comment counts captured from any of the 7 base subs or
any of the 3 adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
r/femalefashionadvice).

## Recurring vocabulary (top 10)

**Empty.** All 10 editorial-inherited terms (glass skin, slugging,
barrier-first, fermented ceramides, lab-grown ginseng, PDRN/pink
peptide, bio-collagen, prebiotic complex, minimalist routine,
heartleaf) faded on 06-09. No Reddit replacements possible while
blocked.

## Pain points

**Empty.** Pain points require raw user posts. None verifiable on
days 1-4.

Standing hypotheses retained in notebook (NOT carry-forward, NOT
benchmark): shipping/availability gap for Ireland 18-34, slugging
fatigue, actives over-stacking burnout. Testable only once raw
Reddit access is restored.

## Faded / contradicted carry-forwards

- **Faded:** All 8 brands and 10 vocabulary terms already aged out on
  06-09. Nothing new fades today (nothing left to fade).
- **Contradicted:** None — contradiction requires raw threads.

**Net carry-forward state going into 2026-06-11: still empty.**

## Content strategy notes

3 actionable items (unchanged across 4 days; the asks have not been
acted on, so the asks have not changed):

1. **Allowlist `reddit.com` + subdomains in environment outbound
   policy.** ~2 minutes via Claude Code on the web → environment
   settings. Reddit JSON read endpoints are unauthenticated. Docs:
   https://code.claude.com/docs/en/claude-code-on-the-web. **This
   is now the single highest-leverage action on the project** —
   1 day from breaching the 35% lost-day floor.
2. **Install a PRAW-based Reddit MCP server as the durable fix.**
   MCP traffic bypasses the WebFetch allowlist entirely. Candidates:
   `adhikasp/mcp-reddit`, `jordanburke/reddit-mcp-server`. ~30 min
   one-time including registering a free Reddit script app
   (client_id + client_secret + UA).
3. **Re-baseline the 14-day window from the unblock date.** With
   the carry-forward set empty and 4 zero days banked, a mixed
   window (4 empty + 10 real) will skew every running average,
   trend slope, and percentile produced. Recommend explicit
   re-baseline once access returns — e.g. "14 days from unblock
   date" — and treat 06-07 → 06-10 as a documented gap, not
   imputed.

## Data quality

- **Live Reddit access: BLOCKED (day 4).** Endpoints re-tested
  today: `www.reddit.com/r/{sub}/new.json`, `old.reddit.com`,
  `www.reddit.com/r/{sub}/.rss`, `api.pullpush.io`,
  `libreddit.privacydev.net`, `redlib.catsarch.com`,
  `safereddit.com`, `teddit.net`,
  `eu.redlib.privacyredirect.com`. All failed (403, "unable to
  fetch", or ECONNREFUSED).
- **WebSearch: works, but does NOT surface `site:reddit.com` hits.**
  2 query variants today — both "no links found."
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker
  is at the reddit.com host level, identical failure mode applies.
- **Yesterday's carry-forward source** (`daily_data/2026_06_09/
  reddit-women-uk.md`): loaded successfully. Carry-forward set was
  declared empty yesterday → no inheritance possible today.
- **Net result:** 0 verified mentions on day 4. 4 of 14 benchmark
  days (~29%) are placeholder files. Next day (06-11) would
  breach the 35% lost-day floor — at that point the benchmark
  should be paused or re-scoped rather than continued.

### Remediation options (unchanged across 4 days; urgency: critical)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/`; the routine can read from disk.

**Without any of the above, the remaining 10 benchmark days will
be the same placeholder file with the BASE-only table and an empty
carry-forward state.**
