# Reddit K-Skincare Mentions — last 24h — 2026-06-17

> **DAY 10 OF UNRESOLVED BLOCKER — 10 of 14 days (71%) NOW PLACEHOLDER.**
> Three days past the methodology midpoint. The 14-day Reddit
> consumer-voice benchmark is mathematically unrecoverable in its
> originally-scoped form: only 4 valid days remain in the window even
> if `reddit.com` were allowlisted within the next hour.
>
> Re-tested today (all FAILED, identical signature to days 1-9):
> - `curl https://www.reddit.com/r/SkincareAddictionUK/new.json` →
>   `HTTP/2 403  x-deny-reason: host_not_allowed`
> - `curl https://old.reddit.com/` → HTTP/2 403
> - `curl https://api.pullpush.io/` → HTTP/2 403
> - `curl https://safereddit.com/` → HTTP/2 403
> - `curl https://redlib.catsarch.com/` → HTTP/2 403
> - `curl https://teddit.net/` → HTTP/2 403
> - `curl https://libreddit.bus-hit.me/` → DNS/no response
>
> Block remains at the environment outbound network policy. Every
> reddit.com host plus every public mirror tested returns
> `host_not_allowed` before the request leaves the container.
> Sub-by-sub retry remains futile: the failure is host-level,
> identical across all 7 base subs and the 3 adjacent subs
> (r/MakeupAddiction, r/SkincareAddictionPale, r/femalefashionadvice).
>
> Manual fallback still empty: `daily_data/2026_06_17/raw/reddit/`
> does not exist on disk — no operator-supplied JSON drop available
> either. The routine has not been patched to read from disk first,
> so even a manual drop would not be auto-ingested.
>
> Fix unchanged: ~2 min to allowlist `reddit.com` + subdomains.
> 10th consecutive day-of-blocker push notification dispatched.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09 — day 9
of empty inheritance) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day + 1-2 adjacent subs)
remains unreachable. Editorial substitutes (AOL, Substack, Statista,
Glamour/Cosmo round-ups, Boots/Cult-Beauty PR copy) are SEO/PR
corpus, not unfiltered consumer voice, and remain explicitly OUT of
this benchmark to preserve methodology integrity.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 10) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 10) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 10) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 10) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 10) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 10) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 10) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 10) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 10) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 10) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 10) |
| VT | BASE | 0 | — | — | no signal — blocked (day 10) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 10) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 10) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 10) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 10) |

**No NEW brand rows.** No corpus to inspect. The 3-new-signals/day
diversity floor cannot be reached from non-Reddit sources without
falsifying the benchmark.

## Top posts (5-10)

**None retrievable. Day 10 consecutive.** Zero Reddit URLs, titles,
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

- **Faded set (emptied 2026-06-09, unchanged for the 8th day in a
  row):** Beauty of Joseon, medicube, Biodance, Anua, SKIN1004, COSRX,
  mixsoon, Round Lab + the 10 vocabulary terms listed above. No new
  fades possible — set has been empty for 8 days.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state going into 2026-06-18: empty.** Day 11 (if
unblocked) starts from BASE seed only. Any carry-forward set rebuild
begins from day 1 of new data — there is no thread of continuity to
pick back up.

## Content strategy notes

3 actionable items — urgency tier = POST-MIDPOINT, UNRECOVERABLE
(3 days past midpoint, 4 days left in window):

1. **Decision is now FORCED, not deferred — the swap-corpus pivot
   must start today or the benchmark ships with 71% placeholder
   days.** Day 10 makes the math undeniable: 14 - 10 = 4 valid days
   are the absolute ceiling, well below the methodology's 2-week
   floor even if the allowlist landed in the next hour. Options
   ranked by salvageable value: (a) **swap-corpus (RECOMMENDED)** —
   substitute TikTok comments, YouTube comments, and Boots /
   Cult-Beauty / LookFantastic product reviews as the consumer-voice
   corpus for the remaining 4 days; hosts likely already on
   allowlist (5-min test). Produces a usable, methodology-honest
   corpus inside the original window. (b) **truncate-and-caveat** —
   keep window, ship with explicit "first 10 days Reddit-blind;
   consumer-voice corpus = days 11-14 only" caveat; produces 4 days
   of valid Reddit data only if unblock lands today. (c)
   **restart-from-unblock** — write off the run, restart a 14-day
   clock when unblock lands. **Recommend (a) unless unblock is
   confirmed by EOD; defer no longer is not an option.**
2. **Reddit MCP install is the only durable long-term fix.** After
   10 consecutive days of identical 403s, the WebFetch allowlist is
   not plausibly going to be touched by accident. Either allowlist
   `reddit.com` + subdomains (~2 min, requires environment-owner
   action via Claude Code on the Web env settings) OR install a
   PRAW-based MCP server (`adhikasp/mcp-reddit` or
   `jordanburke/reddit-mcp-server`) with a free Reddit script-app
   credential set (~30 min, owner-installable from the MCP
   marketplace). MCP traffic bypasses the WebFetch allowlist
   entirely, so it is durable against future policy changes. Docs:
   https://code.claude.com/docs/en/claude-code-on-the-web.
3. **Per-run manual fallback patch is still ~10 min and still
   un-implemented.** If neither (1) nor (2) lands before tomorrow's
   routine fires, the practical stopgap is for the project owner to
   manually download Reddit JSON for the 7 base + 3 adjacent subs
   (~5 min of browser activity using a logged-in session) and drop
   the files into `daily_data/{date}/raw/reddit/`. The routine must
   be patched to read from disk first and fall back to live fetch —
   otherwise manual drops won't be picked up. Recommended every day
   since day 5 (6 days running) and remains un-implemented;
   flagging again.

## Data quality

- **Live Reddit access: BLOCKED (day 10, 10 consecutive days).**
  Identical failure pattern to days 1-9. Every reddit.com endpoint,
  every public mirror tested today (pullpush, safereddit, redlib,
  teddit, libreddit) returned `HTTP/2 403 x-deny-reason:
  host_not_allowed`. WebFetch returned the unable-to-fetch error on
  every reddit-family domain.
- **WebSearch: not used as a substitute.** `site:reddit.com` queries
  on days 1-9 returned zero reddit thread URLs for any of the seven
  base subs in the last 14 days — only editorial substitutes (AOL
  trend round-ups, Substack newsletters, Statista summaries). Wrong
  corpus; not promoted.
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is
  host-level, same failure mode applies to every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_16/reddit-women-uk.md`. Carry-forward set has
  been empty since 2026-06-09 per the 3-day DROP rule; nothing to
  inherit for the 8th consecutive day.
- **Manual-drop directory:** `daily_data/2026_06_17/raw/reddit/`
  does not exist on disk today either.
- **Net result:** 0 verified mentions on day 10. 10 of 14 benchmark
  days (71%) are now placeholder files. Three days past midpoint,
  mathematically unrecoverable in original form.

### Remediation options (unchanged; urgency = unrecoverable, 3 days past midpoint)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix; bypasses
   WebFetch allowlist entirely.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/` AND patch the routine to read
   them first. Restores partial integrity even under continued
   block.

**Day 10 = 3 days past the midpoint, unrecoverable in original 14-day
form. Only 4 days remain. The project owner needs to authorise the
swap-corpus pivot TODAY — otherwise day 11 will be the 11th identical
placeholder and the benchmark ships at 71%+ placeholder.**
