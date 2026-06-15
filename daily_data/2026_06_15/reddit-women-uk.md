# Reddit K-Skincare Mentions — last 24h — 2026-06-15

> **DAY 8 OF UNRESOLVED BLOCKER — 8 of 14 days (57%) NOW PLACEHOLDER.**
> The midpoint declared on day 7 has been passed. The 14-day Reddit
> consumer-voice benchmark is now mathematically unrecoverable in its
> originally-scoped form: with 8 days lost, only 6 days of valid
> Reddit data remain possible even if the network policy is fixed
> within the next hour. The original methodology required a 2-week
> floor; that floor is gone.
>
> Re-tested today (all FAILED, identical signature to days 1-7):
> - `curl https://www.reddit.com/r/SkincareAddictionUK/new.json` →
>   `HTTP/2 403  Host not in allowlist: www.reddit.com. Add this host
>   to your network egress settings to allow access.`
> - `curl https://old.reddit.com/...` → 403
> - `curl https://api.pullpush.io/...` → 403
> - `curl https://safereddit.com/...` → 403
> - `curl https://redlib.catsarch.com/...` → 403
> - `curl https://teddit.net/...` → 403
> - `curl https://libreddit.bus-hit.me/...` → DNS not resolvable
> - WebFetch `www.reddit.com` → "Claude Code is unable to fetch from
>   www.reddit.com"
>
> Block remains at the environment outbound network policy. Every
> reddit.com host plus every public mirror tested returns
> `host_not_allowed` (or, for newly-tried mirrors, DNS failure) before
> the request leaves the container. Sub-by-sub retry remains futile:
> the failure is host-level, identical across all 7 base subs and the
> 3 adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
> r/femalefashionadvice).
>
> Manual fallback also still empty: `daily_data/2026_06_15/raw/reddit/`
> does not exist — no operator-supplied JSON drop available either.
>
> Fix unchanged: ~2 min to allowlist `reddit.com` + subdomains. 8th
> consecutive day-of-blocker push notification dispatched.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09 — day 7
of empty inheritance) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day + 1-2 adjacent subs)
remains unreachable. Editorial substitutes available today (AOL,
Substack, Statista, Glamour/Cosmo round-ups, Boots/Cult-Beauty PR
copy) are SEO/PR corpus, not unfiltered consumer voice, and are
explicitly OUT of this benchmark to preserve methodology integrity.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 8) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 8) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 8) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 8) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 8) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 8) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 8) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 8) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 8) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 8) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 8) |
| VT | BASE | 0 | — | — | no signal — blocked (day 8) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 8) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 8) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 8) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 8) |

**No NEW brand rows.** No corpus to inspect. The 3-new-signals/day
diversity floor cannot be reached from non-Reddit sources without
falsifying the benchmark.

## Top posts (5-10)

**None retrievable. Day 8 consecutive.** Zero Reddit URLs, titles,
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
post-2025 EU UVA updates, "dupe culture" backlash. Testable only once
raw Reddit access returns.

## Faded / contradicted carry-forwards

- **Faded set (emptied 2026-06-09, unchanged for the 6th day in a
  row):** Beauty of Joseon, medicube, Biodance, Anua, SKIN1004, COSRX,
  mixsoon, Round Lab + the 10 vocabulary terms listed above. No new
  fades possible — set has been empty for 6 days.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state going into 2026-06-16: empty.** Day 9 (if
unblocked) starts from BASE seed only. Any carry-forward set rebuild
begins from day 1 of new data — there is no thread of continuity to
pick back up.

## Content strategy notes

3 actionable items — urgency tier now at POST-MIDPOINT, UNRECOVERABLE:

1. **The 14-day Reddit benchmark in its original form is dead.**
   Day 8 confirms it: 14 - 8 = 6 valid days are the absolute ceiling
   from this point even with an immediate unblock, below the
   methodology's 2-week floor. The remaining choices, in order of
   least-rework: (a) **truncate-and-caveat** — keep the original
   2026-06-08 → 2026-06-21 window but ship the deck with an explicit
   "first 8 days Reddit-blind; consumer-voice corpus = days 9-14
   only" caveat and reduce confidence claims accordingly; (b)
   **restart-from-unblock** — declare the current run a write-off and
   start a fresh 14-day clock the day the allowlist lands; (c)
   **swap-corpus** — substitute TikTok comments, YouTube comments,
   Boots/Cult-Beauty product reviews as the consumer-voice corpus
   (these hosts are likely already on the allowlist; needs a 5-min
   test). Continuing the routine as-is for 6 more days produces 6
   more empty files and still ends with a structurally-invalid
   deliverable. **Recommend the project owner pick one of (a)/(b)/(c)
   in the next 24h** so the remaining 6 days are spent productively.
2. **Reddit MCP install is now the only credible long-term fix.**
   After 8 consecutive days of identical 403s, the WebFetch
   allowlist is no longer plausibly going to be touched by accident.
   Either allowlist `reddit.com` + subdomains (~2 min, requires
   environment-owner action via the Claude Code on the Web env
   settings) OR install a PRAW-based MCP server
   (`adhikasp/mcp-reddit` or `jordanburke/reddit-mcp-server`) with a
   free Reddit script-app credential set (~30 min, owner-installable
   from the MCP marketplace). MCP traffic bypasses the WebFetch
   allowlist entirely, so it is durable against future policy
   changes. Docs: https://code.claude.com/docs/en/claude-code-on-the-web.
3. **Per-run manual fallback is still the day-9 contingency, and
   needs ~10 min of one-time routine patching to actually function.**
   If neither (1) nor (2) lands before tomorrow's routine fires, the
   practical stopgap is for the project owner to manually download
   Reddit JSON for the 7 base + 3 adjacent subs (~5 min of browser
   activity using a logged-in session) and drop the files into
   `daily_data/{date}/raw/reddit/`. The routine should be patched to
   read from disk first and fall back to live fetch — this restores
   partial benchmark integrity even under continued network block.
   This patch has been recommended every day since day 5 and remains
   un-implemented; flagging again that without it, manual drops won't
   automatically be picked up.

## Data quality

- **Live Reddit access: BLOCKED (day 8, 8 consecutive days).**
  Identical failure pattern to days 1-7. Every reddit.com endpoint,
  every public mirror tested today (pullpush, safereddit, redlib,
  teddit, libreddit) returned `HTTP/2 403  Host not in allowlist`
  (or DNS failure on the newer mirror). WebFetch returned `Claude
  Code is unable to fetch from {host}` on every reddit-family domain.
- **WebSearch: not used as a substitute.** `site:reddit.com` queries
  on days 1-7 returned zero reddit thread URLs for any of the seven
  base subs in the last 14 days — only editorial substitutes (AOL
  trend round-ups, Substack newsletters, Statista summaries). Wrong
  corpus; not promoted.
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is
  host-level, same failure mode applies to every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_14/reddit-women-uk.md`. Carry-forward set has
  been empty since 2026-06-09 per the 3-day DROP rule; nothing to
  inherit for the 6th consecutive day.
- **Manual-drop directory:** `daily_data/2026_06_15/raw/reddit/`
  does not exist on disk today either.
- **Net result:** 0 verified mentions on day 8. 8 of 14 benchmark
  days (57%) are now placeholder files. Past midpoint, mathematically
  unrecoverable in original form.

### Remediation options (unchanged; urgency = unrecoverable)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix; bypasses
   WebFetch allowlist entirely.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/` AND patch the routine to read
   them first. Restores partial integrity even under continued block.

**Day 8 = past the midpoint, unrecoverable in original 14-day form.
The remaining 6 days of the benchmark window will not produce a
methodology-valid Reddit corpus regardless of when the unblock lands.
The project owner needs to decide between truncate-and-caveat,
restart-from-unblock, or swap-corpus before tomorrow's routine
otherwise day 9 will be the 9th identical placeholder.**
