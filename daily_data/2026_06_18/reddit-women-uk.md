# Reddit K-Skincare Mentions — last 24h — 2026-06-18

> **DAY 11 OF UNRESOLVED BLOCKER — 11 of 14 days (79%) NOW PLACEHOLDER.**
> Four days past methodology midpoint. Only **3 days** of the original
> 14-day window remain. The benchmark in its originally-scoped form is
> mathematically dead: even if `reddit.com` were allowlisted in the
> next minute, the corpus would top out at 3/14 = 21% of nominal
> coverage — below any reasonable consumer-voice integrity floor.
>
> Re-tested today (2026-06-18 08:04 UTC, all FAILED, identical signature
> to days 1-10):
> - `curl https://www.reddit.com/r/SkincareAddictionUK/new.json` →
>   `HTTP/2 403  x-deny-reason: host_not_allowed`
> - `curl https://old.reddit.com/r/AsianBeauty/new.json` → `HTTP/2 403`
> - `curl https://api.pullpush.io/...` → `HTTP/2 403`
> - WebFetch on reddit.com → "Claude Code is unable to fetch"
>
> Block remains at the environment outbound network policy
> (`x-deny-reason: host_not_allowed` — same byte-for-byte response as
> days 1-10). Sub-by-sub retry remains futile: the failure is
> host-level, identical across all 7 base subs and the 3 adjacent subs.
>
> Manual fallback still empty: `daily_data/2026_06_18/raw/reddit/`
> does not exist on disk — no operator-supplied JSON drop available.
> Routine still not patched to read from disk first.
>
> Fix unchanged: ~2 min to allowlist `reddit.com` + subdomains.
> 11th consecutive day-of-blocker push notification dispatched.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09 — day 10
of empty inheritance) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day + 1-2 adjacent subs)
remains unreachable. Editorial substitutes (AOL, Substack, Statista,
Glamour/Cosmo round-ups, Boots/Cult-Beauty PR copy) are SEO/PR
corpus, not unfiltered consumer voice, and remain explicitly OUT of
this benchmark to preserve methodology integrity.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 11) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 11) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 11) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 11) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 11) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 11) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 11) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 11) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 11) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 11) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 11) |
| VT | BASE | 0 | — | — | no signal — blocked (day 11) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 11) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 11) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 11) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 11) |

**No NEW brand rows.** No corpus to inspect. The 3-new-signals/day
diversity floor cannot be reached from non-Reddit sources without
falsifying the benchmark.

## Top posts (5-10)

**None retrievable. Day 11 consecutive.** Zero Reddit URLs, titles,
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

- **Faded set (emptied 2026-06-09, unchanged for the 9th day in a
  row):** Beauty of Joseon, medicube, Biodance, Anua, SKIN1004, COSRX,
  mixsoon, Round Lab + the 10 vocabulary terms listed above. No new
  fades possible — set has been empty for 9 days.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state going into 2026-06-19: empty.** Day 12 (if
unblocked) starts from BASE seed only. Any carry-forward set rebuild
begins from day 1 of new data — there is no thread of continuity to
pick back up.

## Content strategy notes

3 actionable items — urgency tier = TERMINAL, 3 DAYS LEFT IN WINDOW:

1. **The pivot decision is now retrospective, not prospective.** Day 11
   makes the choice for the project owner by elimination: 14 − 11 = 3
   valid days remain even if unblock landed in the next hour. That is
   below any defensible consumer-voice threshold. The three live
   options collapse to: (a) **swap-corpus NOW** — substitute TikTok
   comments, YouTube comments, and Boots / Cult-Beauty / LookFantastic
   product reviews as the consumer-voice corpus for the remaining 3
   days; allowlist-test first (~5 min). (b) **truncate-and-caveat** —
   keep window, ship with "first 11 days Reddit-blind; consumer-voice
   corpus = 3 days" caveat, which renders the benchmark
   non-publishable as a 14-day study. (c) **restart-from-unblock** —
   write off the run, restart a 14-day clock once `reddit.com` is
   allowlisted. **Recommend (a) today; (c) if (a) hits the same
   allowlist wall on the substitute hosts.**
2. **Reddit MCP install is the only durable long-term fix.** After 11
   consecutive days of identical 403s, the WebFetch allowlist will not
   move without explicit owner action. Either allowlist `reddit.com`
   + subdomains (~2 min, environment-owner action via Claude Code on
   the Web env settings) OR install a PRAW-based MCP server
   (`adhikasp/mcp-reddit` or `jordanburke/reddit-mcp-server`) with a
   free Reddit script-app credential set (~30 min, owner-installable
   from the MCP marketplace). MCP traffic bypasses the WebFetch
   allowlist entirely, so it is durable against future policy changes.
   Docs: https://code.claude.com/docs/en/claude-code-on-the-web.
3. **Per-run manual fallback patch is still ~10 min and still
   un-implemented.** Flagged every day since day 5 (7 days running).
   If the owner can drop Reddit JSON exports for the 7 base + 3
   adjacent subs (~5 min logged-in browser activity) into
   `daily_data/{date}/raw/reddit/`, AND the routine is patched to
   read from disk first, the remaining 3 days of the window can still
   collect partial signal under the original methodology. This
   recovers ~3/14 = 21% of nominal coverage — small but
   methodology-clean.

## Data quality

- **Live Reddit access: BLOCKED (day 11, 11 consecutive days).**
  Identical failure pattern to days 1-10. Every reddit.com endpoint
  and every public mirror tested today (pullpush, old.reddit) returned
  `HTTP/2 403 x-deny-reason: host_not_allowed`. WebFetch returned the
  unable-to-fetch error on every reddit-family domain.
- **WebSearch: not used as a substitute.** `site:reddit.com` queries
  on days 1-10 returned zero reddit thread URLs for any of the seven
  base subs in the last 14 days — only editorial substitutes. Wrong
  corpus; not promoted.
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is
  host-level, same failure mode applies to every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_17/reddit-women-uk.md`. Carry-forward set has
  been empty since 2026-06-09 per the 3-day DROP rule; nothing to
  inherit for the 9th consecutive day.
- **Manual-drop directory:** `daily_data/2026_06_18/raw/reddit/` does
  not exist on disk today either.
- **Net result:** 0 verified mentions on day 11. 11 of 14 benchmark
  days (79%) are now placeholder files. Four days past midpoint, three
  days from end-of-window, mathematically unrecoverable in original
  form.

### Remediation options (unchanged; urgency = TERMINAL, 3 days left)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix; bypasses
   WebFetch allowlist entirely.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/` AND patch the routine to read them
   first. Restores partial integrity even under continued block.

**Day 11 = 4 days past midpoint, 3 days from end-of-window. The
benchmark in its original form is dead — even an immediate unblock
caps coverage at 21%. The project owner must either authorise the
swap-corpus pivot or accept that the 14-day Reddit study restarts from
day-1 of next unblock. Continuing to file placeholders past day 11 is
no longer a holding pattern; it is the record of a study that did not
run.**
