# Reddit K-Skincare Mentions — last 24h — 2026-06-11

> **DAY 4 OF UNRESOLVED BLOCKER. CARRY-FORWARD ALREADY EMPTY (faded
> 2026-06-09 per the 3-day DROP rule).** All reddit.com endpoints
> (www, old, api, redditmedia, .rss), every public mirror tested
> (libreddit.privacydev.net, redlib.catsarch.com, safereddit.com,
> teddit.adminforge.de, eu.redlib.privacyredirect.com), and the
> Pushshift mirror `api.pullpush.io` returned 403, ECONNREFUSED, or
> "Host not in allowlist" today. WebSearch returns no `site:reddit.com`
> hits for any of 4 query variants.
>
> **4 of 14 benchmark days now lost (~29%).** The 5-day statistical-
> floor breach point is tomorrow. Push notification sent today as
> well — fix is still ~2 minutes (allowlist `reddit.com` + subdomains
> in the environment outbound policy) and unlocks the remaining 10 days.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (set was emptied 06-09) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day) cannot be satisfied
without raw Reddit. Editorial sources would corrupt the benchmark.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 4) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 4) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 4) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 4) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 4) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 4) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 4) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 4) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 4) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 4) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 4) |
| VT | BASE | 0 | — | — | no signal — blocked (day 4) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 4) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 4) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 4) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 4) |

**No NEW brand rows.** The diversity floor cannot be met from non-Reddit
sources without inflating the benchmark's confidence falsely.

## Top posts (5-10)

**None retrievable.** Day 4 in a row. Zero Reddit URLs, titles, scores,
or comment counts captured from any of the 7 base subs or the 3
adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
r/femalefashionadvice). The methodology's primary deliverable is empty
for the fourth consecutive day.

## Recurring vocabulary (top 10)

**Empty.** The 10 inherited vocabulary terms faded 06-09 alongside the
brand carry-forwards. Re-collecting vocabulary requires raw post bodies
and comment threads; editorial substitutes systematically launder out
the colloquial phrasing the benchmark exists to capture.

## Pain points

**Empty.** Pain points only emerge from raw user posts. None could be
verified on days 1-4.

Standing hypotheses retained in the notebook (NOT promoted to benchmark
signal): shipping/availability gap for Ireland 18-34, slugging fatigue,
actives over-stacking burnout. Testable only once raw Reddit access
returns.

## Faded / contradicted carry-forwards

- **Faded set (already emptied 2026-06-09):** Beauty of Joseon, medicube,
  Biodance, Anua, SKIN1004, COSRX, mixsoon, Round Lab plus the 10
  vocabulary terms (glass skin, slugging, barrier-first, fermented
  ceramides, lab-grown ginseng, PDRN/pink peptide, bio-collagen,
  prebiotic complex, minimalist routine, heartleaf). No new fades
  possible today — there is nothing left to fade.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state going into 2026-06-12: empty.** Day 5 (if
unblocked) starts from the BASE seed only.

## Content strategy notes

3 actionable items (same three as days 2-3; the urgency, not the fix,
is what has changed):

1. **Tomorrow is the 5-day statistical-floor breach.** 5/14 = 36% of
   benchmark days as placeholder files. Above this threshold, no
   running average, trend line, or sentiment shift produced from the
   completed window can be presented to a stakeholder without a
   caveat that voids most of its operational value. Decision point
   for the project owner: continue, re-baseline the window from
   unblock-date, or pause the routine until access is restored.
2. **The fix is 2 minutes, the cost of inaction is the benchmark.**
   Add `reddit.com`, `www.reddit.com`, `old.reddit.com`,
   `api.reddit.com` to the environment's outbound allowlist (Claude
   Code on the web → environment settings → network policy). Reddit
   JSON read endpoints are unauthenticated; no API key required. Docs:
   https://code.claude.com/docs/en/claude-code-on-the-web.
3. **Install a PRAW-based Reddit MCP server as the durable fix.** MCP
   traffic isn't gated by the WebFetch allowlist, so it bypasses this
   failure mode entirely. Candidates: `adhikasp/mcp-reddit`,
   `jordanburke/reddit-mcp-server`. Free Reddit script-app credential
   set, ~30 min one-time setup. Pays back the first time this
   benchmark is re-run.

## Data quality

- **Live Reddit access: BLOCKED (day 4).** Re-tested today:
  `www.reddit.com/r/{sub}/new.json`, `old.reddit.com/.json`,
  `api.reddit.com`, `www.redditmedia.com/.json`, `.rss` variants,
  `api.pullpush.io`, `libreddit.privacydev.net`, `redlib.catsarch.com`,
  `safereddit.com`, `teddit.adminforge.de`,
  `eu.redlib.privacyredirect.com`. All 403 / ECONNREFUSED /
  "Host not in allowlist".
- **WebSearch: works, does NOT index `site:reddit.com`.** 4 query
  variants today (sub + brand + year; brand + reddit + UK;
  sub + Korean skincare + year; sub + skin barrier + month/year) —
  all returned "no links found".
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is at
  the reddit.com host level, identical failure for every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_09/reddit-women-uk.md`. Carry-forward set was
  explicitly emptied yesterday per the 3-day DROP rule; nothing to
  inherit today.
- **Net result:** 0 verified mentions on day 4. 4 of 14 benchmark days
  (~29%) are placeholder files. 5-day breach is tomorrow.

### Remediation options (unchanged; urgency = critical)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/`; the routine can read from disk.

**Without any of these by tomorrow, the benchmark crosses its
statistical floor.**
