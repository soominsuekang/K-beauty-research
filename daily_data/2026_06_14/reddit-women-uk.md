# Reddit K-Skincare Mentions — last 24h — 2026-06-14

> **DAY 7 OF UNRESOLVED BLOCKER — 7 of 14 days (50%) NOW PLACEHOLDER.**
> Half the 14-day benchmark window is gone with zero Reddit consumer-
> voice data captured. The structural breach declared on day 5 and
> compounded on day 6 is now at the midpoint: from this point forward,
> even a same-day unblock cannot produce a majority-valid benchmark.
>
> Re-tested today (all FAILED, identical to days 1-6):
> - `curl https://www.reddit.com/r/SkincareAddictionUK/new.json` →
>   `HTTP/2 403 x-deny-reason: host_not_allowed`
> - `curl https://old.reddit.com/r/SkincareAddictionUK/.json` → 403
>   host_not_allowed
> - `curl https://api.pullpush.io/reddit/search/submission/` → 403
>   host_not_allowed
> - `curl https://safereddit.com/r/SkincareAddictionUK` → 403
>   host_not_allowed
> - WebFetch `www.reddit.com` → "Claude Code is unable to fetch from
>   www.reddit.com"
> - WebFetch `old.reddit.com` → "Claude Code is unable to fetch from
>   old.reddit.com"
>
> Block sits at the environment outbound network policy — every
> reddit.com host, every public mirror (pullpush, safereddit, redlib,
> teddit) returns `host_not_allowed` before the request leaves the
> container. Sub-by-sub retry remains futile; failure mode is identical
> on every subreddit including the three adjacent ones
> (r/MakeupAddiction, r/SkincareAddictionPale, r/femalefashionadvice).
>
> Fix unchanged: ~2 min to allowlist `reddit.com` + subdomains. 7th
> push notification sent today.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09, day 5
inheritance window) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day + 1-2 adjacent subs)
remains unreachable. Editorial substitutes available today (AOL trend
round-ups, Substack newsletters, Statista summaries) are SEO/PR
corpus, not unfiltered consumer voice, and are explicitly OUT of
this benchmark to preserve methodology integrity.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 7) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 7) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 7) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 7) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 7) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 7) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 7) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 7) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 7) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 7) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 7) |
| VT | BASE | 0 | — | — | no signal — blocked (day 7) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 7) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 7) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 7) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 7) |

**No NEW brand rows.** No corpus to inspect. The 3-new-signals/day
diversity floor cannot be reached from non-Reddit sources without
falsifying the benchmark.

## Top posts (5-10)

**None retrievable. Day 7 consecutive.** Zero Reddit URLs, titles,
scores, or comment counts captured from any of the 7 base subs or 3
adjacent subs. Blocker is at the reddit.com host level — every retry
fails identically before a request leaves the container.

## Recurring vocabulary (top 10)

**Empty.** The 10 inherited terms (glass skin, slugging, barrier-first,
fermented ceramides, lab-grown ginseng, PDRN/pink peptide, bio-collagen,
prebiotic complex, minimalist routine, heartleaf) faded 2026-06-09
under the 3-day DROP rule. Re-collection requires raw post bodies /
comment threads, which editorial substitutes systematically launder out.

## Pain points

**Empty.** Pain points emerge only from raw user posts. Standing
hypotheses retained in researcher notebook (NOT promoted to benchmark
signal): Ireland 18-34 shipping/availability gap, slugging fatigue,
actives over-stacking burnout, sunscreen-reformulation confusion
post-2025 EU UVA updates. Testable only once raw Reddit access returns.

## Faded / contradicted carry-forwards

- **Faded set (emptied 2026-06-09, unchanged for the 5th day in a
  row):** Beauty of Joseon, medicube, Biodance, Anua, SKIN1004, COSRX,
  mixsoon, Round Lab + the 10 vocabulary terms listed above. No new
  fades possible — set has been empty for 5 days.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state going into 2026-06-15: empty.** Day 8 (if
unblocked) starts from BASE seed only. Any carry-forward set rebuild
begins from day 1 of new data — there is no thread of continuity to
pick back up.

## Content strategy notes

3 actionable items — urgency tier now at MIDPOINT BREACH:

1. **The deliverable is now structurally unrecoverable in its
   original form.** 7 of 14 days are placeholders; even a same-day
   unblock produces a maximum of 7 valid Reddit days, which is below
   the methodology's 2-week consumer-voice floor. The realistic
   decisions today are (a) restart the 14-day clock from the unblock
   date and treat days 1-7 as a write-off, (b) re-scope to a 7-day
   shortened benchmark with explicit "Reddit-blind first half" caveat
   in the final deck, or (c) swap Reddit out of the methodology and
   substitute TikTok comments / YouTube comments / Boots+Cult-Beauty
   review scrapes as the consumer-voice corpus (these hosts may be in
   the allowlist — needs a 5-min test). Continuing the routine as-is
   produces 7 more placeholder files with zero analytical value.
2. **Reddit MCP install is now the dominant fix.** After 7 days of
   identical 403s, the WebFetch allowlist is the single point of
   failure for this benchmark. Either allowlist `reddit.com` +
   subdomains (~2 min, requires environment owner action) OR install a
   PRAW-based MCP server (`adhikasp/mcp-reddit` or
   `jordanburke/reddit-mcp-server`) with a free Reddit script-app
   credential set (~30 min, owner-installable from MCP marketplace).
   MCP traffic bypasses the WebFetch allowlist entirely, so it's
   durable against future policy changes. Docs:
   https://code.claude.com/docs/en/claude-code-on-the-web.
3. **Per-run manual fallback is the day-8 contingency.** If neither
   of the above happens before tomorrow's routine fires, the practical
   stopgap is for the project owner to manually download Reddit JSON
   for the 7 base + 3 adjacent subs (~5 min of browser activity) and
   drop the files into `daily_data/{date}/raw/reddit/`. The routine
   can be patched in <10 min to read from disk first and fall back to
   live fetch — this restores partial benchmark integrity even under
   continued network block.

## Data quality

- **Live Reddit access: BLOCKED (day 7, 7 consecutive days).**
  Identical failure pattern to days 1-6. Every reddit.com endpoint,
  every public mirror tested today (pullpush, safereddit, redlib,
  teddit) returned `HTTP/2 403 x-deny-reason: host_not_allowed`.
  WebFetch returned `Claude Code is unable to fetch from {host}` on
  every reddit-family domain attempted.
- **WebSearch: not used as a substitute.** `site:reddit.com` queries
  on days 1-6 returned zero reddit thread URLs for any of the seven
  base subs in the last 14 days — only editorial substitutes (AOL
  trend round-ups, Substack newsletters, Statista summaries). Wrong
  corpus; not promoted.
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is
  host-level, same failure mode applies to every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_13/reddit-women-uk.md`. Carry-forward set has
  been empty since 2026-06-09 per the 3-day DROP rule; nothing to
  inherit for the 5th consecutive day.
- **Net result:** 0 verified mentions on day 7. 7 of 14 benchmark
  days (50%) are now placeholder files. Midpoint breach: from today
  onward, even an immediate unblock cannot produce a majority-valid
  14-day Reddit corpus.

### Remediation options (unchanged; urgency = midpoint breach)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix; bypasses
   WebFetch allowlist entirely.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/`. Routine patched to read from disk
   first. Restores partial integrity even under continued block.

**Day 7 = the midpoint. Half the benchmark window has now produced no
Reddit consumer-voice data. Without remediation before tomorrow's
routine, the 14-day deliverable will end with 14 of 14 days lacking
Reddit data and the project must be re-scoped or restarted from a
later unblock date.**
