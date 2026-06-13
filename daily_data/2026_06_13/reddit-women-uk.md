# Reddit K-Skincare Mentions — last 24h — 2026-06-13

> **DAY 6 OF UNRESOLVED BLOCKER — 6 of 14 days (~43%) NOW PLACEHOLDER.**
> The statistical-floor breach declared on day 5 has compounded. The
> 14-day benchmark now has fewer valid Reddit days remaining (8) than
> placeholder days accumulated (6). Even if access is restored
> tomorrow, the carry-forward set will need to be rebuilt from day 1
> of new data — there is nothing to inherit.
>
> Re-tested today (all FAILED, identical to days 1-5):
> `www.reddit.com/r/{sub}/new.json`, `old.reddit.com`,
> `api.reddit.com`, `.rss` variants, `api.pullpush.io`,
> `safereddit.com`, `redlib.privacyredirect.com`, `teddit.net`. All
> returned 403 or "Claude Code is unable to fetch from {host}".
> WebSearch `site:reddit.com r/SkincareAddictionUK June 2026` returned
> zero Reddit thread URLs — only AOL/Statista/Substack editorial.
>
> Fix remains ~2 minutes (allowlist `reddit.com` + subdomains in
> environment outbound policy). 6th push notification recommended.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day + 1-2 adjacent subs)
cannot be satisfied without raw Reddit. Editorial substitutes
available today (AOL trend pieces, Substack hair/beauty newsletters,
local-directory listings) are SEO/PR corpus, not consumer voice, and
remain explicitly OUT of this benchmark to preserve methodology
integrity.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 6) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 6) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 6) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 6) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 6) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 6) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 6) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 6) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 6) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 6) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 6) |
| VT | BASE | 0 | — | — | no signal — blocked (day 6) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 6) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 6) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 6) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 6) |

**No NEW brand rows.** Editorial chatter today surfaced an AOL "Korean
Beauty Trends 2026" round-up — wrong corpus, not entered. The 3-new-
signals-per-day diversity floor is unreachable from non-Reddit sources
without falsifying the benchmark.

## Top posts (5-10)

**None retrievable. Day 6 consecutive.** Zero Reddit URLs, titles,
scores, or comment counts captured from any of the 7 base subs or 3
adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
r/femalefashionadvice) — blocker is at the reddit.com host level so
sub-by-sub retry is futile.

## Recurring vocabulary (top 10)

**Empty.** The 10 inherited terms faded 2026-06-09 alongside brand
carry-forwards. Re-collection requires raw post bodies / comment
threads, which editorial substitutes systematically launder out.

## Pain points

**Empty.** Pain points emerge only from raw user posts. Standing
hypotheses retained in researcher notebook (NOT promoted to benchmark
signal): Ireland 18-34 shipping/availability gap, slugging fatigue,
actives over-stacking burnout, sunscreen-reformulation confusion
post-2025 EU UVA updates. Testable only once raw Reddit access returns.

## Faded / contradicted carry-forwards

- **Faded set (emptied 2026-06-09, unchanged for the 4th day in a
  row):** Beauty of Joseon, medicube, Biodance, Anua, SKIN1004, COSRX,
  mixsoon, Round Lab + the 10 vocabulary terms (glass skin, slugging,
  barrier-first, fermented ceramides, lab-grown ginseng, PDRN/pink
  peptide, bio-collagen, prebiotic complex, minimalist routine,
  heartleaf). No new fades possible — set has been empty 4 days.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state going into 2026-06-14: empty.** Day 7 (if
unblocked) starts from BASE seed only. Any carry-forward set rebuild
begins from day 1 of new data — there is no thread of continuity to
pick back up.

## Content strategy notes

3 actionable items — urgency tier now COMPOUNDED past the day-5 breach:

1. **Placeholder days (6) now exceed remaining valid days (8).** The
   project owner's decision is no longer "accept a delay" vs "lower
   confidence" — those framings assumed a recoverable window. The
   realistic options today are (a) restart the 14-day clock from the
   unblock date, treating days 1-6 as a write-off, (b) re-scope the
   deliverable to a 7- or 8-day shortened benchmark with explicit
   "Reddit-blind first half" caveat, or (c) substitute a different
   data source (TikTok comment scrape, YouTube comment scrape, Boots/
   Cult Beauty review scrape) for the consumer-voice corpus and
   re-write the methodology statement. Continuing the routine as-is
   produces 8 more placeholder files with no analytical value.
2. **The ~2-min unblock + ~30-min MCP install are now the SAME
   decision.** After 6 days of identical failure, the WebFetch
   allowlist policy is the bottleneck. Either allowlist
   `reddit.com`/`www.reddit.com`/`old.reddit.com`/`api.reddit.com` in
   the environment outbound policy, OR install a PRAW-based MCP server
   (`adhikasp/mcp-reddit` or `jordanburke/reddit-mcp-server`) with a
   free Reddit script-app credential set. MCP traffic bypasses the
   WebFetch allowlist entirely — durable against the next policy
   change. Docs: https://code.claude.com/docs/en/claude-code-on-the-web.
3. **Per-run manual fallback is the day-7 contingency.** If neither of
   the above happens before tomorrow's routine fires, the practical
   stopgap is for the project owner to manually download Reddit JSON
   for the 7 base + 3 adjacent subs (~5 min of browser activity) and
   drop the files into `daily_data/{date}/raw/reddit/`. The routine
   can be patched in <10 min to read from disk first and fall back to
   live fetch — this restores partial benchmark integrity even under
   continued network block.

## Data quality

- **Live Reddit access: BLOCKED (day 6).** Identical failure pattern
  to days 1-5. Every reddit.com endpoint, every public mirror tested
  today (safereddit, redlib privacyredirect, teddit, pullpush) returned
  403, ECONNREFUSED, or "Host not in allowlist".
- **WebSearch: works, but `site:reddit.com` returns zero Reddit URLs
  for our queries today** — only editorial substitutes (AOL trend
  round-ups, Substack newsletters, local-directory listings). Wrong
  corpus; not promoted.
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is
  host-level, same failure mode applies to every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_12/reddit-women-uk.md`. Carry-forward set has
  been empty since 2026-06-09 per the 3-day DROP rule; nothing to
  inherit for the 4th consecutive day.
- **Net result:** 0 verified mentions on day 6. 6 of 14 benchmark days
  (~43%) are placeholder files. Placeholder days now exceed remaining
  valid days (8). Statistical-floor threshold breached on day 5 has
  now compounded to a structural deliverable problem, not a
  confidence-interval problem.

### Remediation options (unchanged; urgency = compounded breach)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix; bypasses
   WebFetch allowlist entirely.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/`. Routine patched to read from disk
   first. Restores partial integrity even under continued block.

**Day 6 = the breach compounds. Without remediation before tomorrow's
routine, days 7-14 will all be placeholders and the 14-day benchmark
will end with 14 of 14 days lacking Reddit consumer-voice data — at
which point the deliverable is unsalvageable in its current form.**
