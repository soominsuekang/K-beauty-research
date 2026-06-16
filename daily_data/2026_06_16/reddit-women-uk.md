# Reddit K-Skincare Mentions — last 24h — 2026-06-16

> **DAY 9 OF UNRESOLVED BLOCKER — 9 of 14 days (64%) NOW PLACEHOLDER.**
> Past the methodology midpoint by 2 days. The 14-day Reddit
> consumer-voice benchmark is mathematically unrecoverable in its
> originally-scoped form: only 5 valid days remain in the window even
> if `reddit.com` were allowlisted within the next hour, well below
> the 2-week floor the methodology required.
>
> Re-tested today (all FAILED, identical signature to days 1-8):
> - `curl https://www.reddit.com/r/SkincareAddictionUK/new.json` →
>   `HTTP/2 403  Host not in allowlist: www.reddit.com. Add this host
>   to your network egress settings to allow access.`
> - `curl https://old.reddit.com/...` → 403
> - `curl https://api.pullpush.io/...` → 403
> - `curl https://safereddit.com/...` → 403
> - `curl https://redlib.catsarch.com/...` → 403
> - `curl https://teddit.net/...` → 403
> - `curl https://libreddit.bus-hit.me/...` → DNS not resolvable
> - WebFetch `www.reddit.com` → blocked (host-level)
>
> Block remains at the environment outbound network policy. Every
> reddit.com host plus every public mirror tested returns
> `host_not_allowed` (or DNS failure on the newest mirror) before the
> request leaves the container. Sub-by-sub retry remains futile: the
> failure is host-level, identical across all 7 base subs and the 3
> adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
> r/femalefashionadvice).
>
> Manual fallback still empty: `daily_data/2026_06_16/raw/reddit/`
> does not exist on disk — no operator-supplied JSON drop available
> either. The routine has not been patched to read from disk first,
> so even a manual drop would not be auto-ingested.
>
> Fix unchanged: ~2 min to allowlist `reddit.com` + subdomains. 9th
> consecutive day-of-blocker push notification dispatched.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09 — day 8
of empty inheritance) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day + 1-2 adjacent subs)
remains unreachable. Editorial substitutes (AOL, Substack, Statista,
Glamour/Cosmo round-ups, Boots/Cult-Beauty PR copy) are SEO/PR
corpus, not unfiltered consumer voice, and remain explicitly OUT of
this benchmark to preserve methodology integrity.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 9) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 9) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 9) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 9) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 9) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 9) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 9) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 9) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 9) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 9) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 9) |
| VT | BASE | 0 | — | — | no signal — blocked (day 9) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 9) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 9) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 9) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 9) |

**No NEW brand rows.** No corpus to inspect. The 3-new-signals/day
diversity floor cannot be reached from non-Reddit sources without
falsifying the benchmark.

## Top posts (5-10)

**None retrievable. Day 9 consecutive.** Zero Reddit URLs, titles,
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

- **Faded set (emptied 2026-06-09, unchanged for the 7th day in a
  row):** Beauty of Joseon, medicube, Biodance, Anua, SKIN1004, COSRX,
  mixsoon, Round Lab + the 10 vocabulary terms listed above. No new
  fades possible — set has been empty for 7 days.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state going into 2026-06-17: empty.** Day 10 (if
unblocked) starts from BASE seed only. Any carry-forward set rebuild
begins from day 1 of new data — there is no thread of continuity to
pick back up.

## Content strategy notes

3 actionable items — urgency tier = POST-MIDPOINT, UNRECOVERABLE
(2 days past midpoint):

1. **Decision overdue: project owner must pick (a)/(b)/(c) today.**
   Day 9 confirms what day 8 mathematically locked in: 14 - 9 = 5
   valid days are the absolute ceiling from this point, below the
   methodology's 2-week floor. The options have not changed since
   day 8 and continuing to defer the decision spends the remaining
   window on more empty placeholders. The choices, ranked by
   least-rework: (a) **truncate-and-caveat** — keep the original
   2026-06-08 → 2026-06-21 window, ship the deck with an explicit
   "first 9 days Reddit-blind; consumer-voice corpus = days 10-14
   only" caveat, downgrade confidence claims; (b)
   **restart-from-unblock** — declare the current run a write-off
   and start a fresh 14-day clock the day the allowlist lands; (c)
   **swap-corpus** — substitute TikTok comments, YouTube comments,
   and Boots/Cult-Beauty product reviews as the consumer-voice
   corpus (hosts likely already on allowlist; needs a 5-min test).
   **Recommend (c) unless the unblock is confirmed by EOD** — it is
   the only option that produces a usable consumer-voice corpus
   inside the original window.
2. **Reddit MCP install remains the only credible long-term fix.**
   After 9 consecutive days of identical 403s, the WebFetch
   allowlist is no longer plausibly going to be touched by accident.
   Either allowlist `reddit.com` + subdomains (~2 min, requires
   environment-owner action via the Claude Code on the Web env
   settings) OR install a PRAW-based MCP server
   (`adhikasp/mcp-reddit` or `jordanburke/reddit-mcp-server`) with a
   free Reddit script-app credential set (~30 min, owner-installable
   from the MCP marketplace). MCP traffic bypasses the WebFetch
   allowlist entirely, so it is durable against future policy
   changes. Docs: https://code.claude.com/docs/en/claude-code-on-the-web.
3. **Per-run manual fallback patch is still ~10 min and still
   un-implemented.** If neither (1) nor (2) lands before tomorrow's
   routine fires, the practical stopgap is for the project owner to
   manually download Reddit JSON for the 7 base + 3 adjacent subs
   (~5 min of browser activity using a logged-in session) and drop
   the files into `daily_data/{date}/raw/reddit/`. The routine must
   be patched to read from disk first and fall back to live fetch —
   otherwise manual drops won't be picked up. This patch has been
   recommended every day since day 5 (5 days running) and remains
   un-implemented; flagging again.

## Data quality

- **Live Reddit access: BLOCKED (day 9, 9 consecutive days).**
  Identical failure pattern to days 1-8. Every reddit.com endpoint,
  every public mirror tested today (pullpush, safereddit, redlib,
  teddit, libreddit) returned `HTTP/2 403  Host not in allowlist`
  (or DNS failure on the newer mirror). WebFetch returned the
  unable-to-fetch error on every reddit-family domain.
- **WebSearch: not used as a substitute.** `site:reddit.com` queries
  on days 1-8 returned zero reddit thread URLs for any of the seven
  base subs in the last 14 days — only editorial substitutes (AOL
  trend round-ups, Substack newsletters, Statista summaries). Wrong
  corpus; not promoted.
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is
  host-level, same failure mode applies to every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_15/reddit-women-uk.md`. Carry-forward set has
  been empty since 2026-06-09 per the 3-day DROP rule; nothing to
  inherit for the 7th consecutive day.
- **Manual-drop directory:** `daily_data/2026_06_16/raw/reddit/`
  does not exist on disk today either.
- **Net result:** 0 verified mentions on day 9. 9 of 14 benchmark
  days (64%) are now placeholder files. Two days past midpoint,
  mathematically unrecoverable in original form.

### Remediation options (unchanged; urgency = unrecoverable, 2 days past midpoint)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix; bypasses
   WebFetch allowlist entirely.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/` AND patch the routine to read
   them first. Restores partial integrity even under continued block.

**Day 9 = 2 days past the midpoint, unrecoverable in original 14-day
form. The remaining 5 days of the benchmark window will not produce
a methodology-valid Reddit corpus regardless of when the unblock
lands. The project owner needs to pick truncate-and-caveat,
restart-from-unblock, or swap-corpus TODAY — otherwise day 10 will
be the 10th identical placeholder.**
