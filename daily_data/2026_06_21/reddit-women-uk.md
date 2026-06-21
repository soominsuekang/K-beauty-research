# Reddit K-Skincare Mentions — last 24h — 2026-06-21

> **DAY 14 — FINAL DAY OF THE 14-DAY WINDOW.**
> **14 of 14 days (100%) blocked. Benchmark closed out as placeholder.**
>
> Re-tested today (2026-06-21, all FAILED, identical signature to days 1-13):
> - `curl https://www.reddit.com/r/AsianBeauty/new.json` → `HTTP/2 403`
> - `curl https://old.reddit.com/r/SkincareAddictionUK/new.json` → `HTTP/2 403`
> - `curl https://api.pullpush.io/reddit/search/submission/?subreddit=SkincareAddictionUK` → `HTTP/2 403`
> - WebFetch on www.reddit.com + old.reddit.com → "Claude Code is unable to fetch"
>
> Block remains at the environment outbound network policy. Failure is
> host-level — identical across all 7 base subs + 3 adjacent subs +
> every public mirror tested across 14 days.
>
> Manual fallback never landed: `daily_data/2026_06_21/raw/reddit/`
> does not exist on disk. Routine still not patched to read from disk
> first. Per-run manual-drop pathway flagged daily since day 5 (10
> consecutive days flagged) — never adopted.
>
> Push-notification tool not present in this routine session — day-14
> close-out alert is filed here in the artefact only, same as days
> 1-13. This means the project owner has received zero out-of-band
> escalations across the entire 14-day blocker; the unblock decision
> has sat unread in 14 successive artefact files.
>
> **Window math is now closed**: 0 of 14 (0%) verified-Reddit days.
> The 14-day Reddit-women-UK benchmark as originally scoped has shipped
> 0% of its intended corpus.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09, day 13 of
empty inheritance) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day + 1-2 adjacent subs) was
unreachable on all 14 days. Editorial substitutes (AOL, Substack,
Statista, Glamour/Cosmo round-ups, Boots/Cult-Beauty PR copy) are
SEO/PR corpus, not unfiltered consumer voice, and were correctly held
OUT of this benchmark across all 14 days to preserve methodology
integrity. That decision is reaffirmed today.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| VT | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 14, FINAL) |

**No NEW brand rows.** No corpus to inspect on the final day either.
The 3-new-signals/day diversity floor was never met on any of the 14
days because every method to reach it required raw Reddit threads.

## Top posts (5-10)

**None retrievable. Day 14 = same as days 1-13.** Zero Reddit URLs,
titles, scores, or comment counts captured from any of the 7 base subs
or 3 adjacent subs across the entire window. Blocker is at the
reddit.com host level — every retry across 14 days has failed
identically before a request leaves the container.

## Recurring vocabulary (top 10)

**Empty.** The 10 inherited terms (glass skin, slugging, barrier-first,
fermented ceramides, lab-grown ginseng, PDRN/pink peptide, bio-collagen,
prebiotic complex, minimalist routine, heartleaf) faded 2026-06-09
under the 3-day DROP rule and were never re-collected. Re-collection
requires raw post bodies / comment threads, which editorial substitutes
systematically launder out.

## Pain points

**Empty.** Pain points emerge only from raw user posts. Standing
hypotheses retained in researcher notebook (NOT promoted to benchmark
signal across any of the 14 days): Ireland 18-34 shipping/availability
gap, slugging fatigue, actives over-stacking burnout, sunscreen-
reformulation confusion post-2025 EU UVA updates, "dupe culture"
backlash. None were testable in this cycle. Carry these forward to the
restart's day-1 hypothesis sheet.

## Faded / contradicted carry-forwards

- **Faded set (emptied 2026-06-09, unchanged for the 12th day in a
  row):** Beauty of Joseon, medicube, Biodance, Anua, SKIN1004, COSRX,
  mixsoon, Round Lab + the 10 vocabulary terms listed above. No new
  fades possible — set has been empty for 12 days.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state at window close: empty.** Nothing inherits
from this cycle into the next. The restart begins from BASE seed only.

## Content strategy notes

3 actionable items — urgency tier = **END-OF-WINDOW, RESTART
DECISION REQUIRED**:

1. **The 14-day Reddit-women-UK benchmark closed at 0% verified
   coverage. The deliverable, in its originally-scoped form, did not
   ship.** Recommended path (unchanged from days 12-13): **(a)
   restart-from-unblock** — write off this run, install the Reddit
   access fix (allowlist OR MCP), then re-clock a fresh 14-day study.
   This preserves methodology integrity and is the only path that
   produces the asked-for deliverable. The other framings — **(b)
   swap-corpus pivot** (TikTok + YouTube comments + Boots/Cult-Beauty
   reviews under a different name) and **(c) ship-the-blocker-report**
   (publish the 14-day window as a 0%-coverage process post-mortem) —
   remain available but only (c) requires no further work; it is a
   retro artefact, not a consumer-voice study, and should be framed
   internally only. **Recommend (a).** **(b)** is acceptable only if
   re-badged as a hybrid corpus and only after the restart is also
   scheduled. **(c)** is the closing summary of this cycle and can be
   filed today.
2. **The unblock is still ~2 min of owner time.** Allowlist
   `reddit.com` + subdomains in the Claude Code on the Web environment
   outbound network policy. Docs:
   https://code.claude.com/docs/en/claude-code-on-the-web. This is the
   single highest-leverage action for the next cycle. If the next
   14-day window is to start without re-running this failure, the
   allowlist edit must precede day 1.
3. **Durable fix: install a PRAW-based Reddit MCP server.** `~30 min`
   of one-time setup (`adhikasp/mcp-reddit` or
   `jordanburke/reddit-mcp-server`, free Reddit script-app credential
   set). MCP traffic bypasses the WebFetch allowlist entirely, so the
   research routine becomes durable against future network-policy
   changes. Recommended for any project that depends on Reddit corpus.
   Combine with item 2 for belt-and-braces.

## Data quality

- **Live Reddit access: BLOCKED (day 14 of 14, 100% of the window).**
  Identical failure pattern to days 1-13. Every reddit.com endpoint
  and every public mirror tested today (`pullpush`, `old.reddit`,
  `www.reddit`) returned `HTTP/2 403`. WebFetch returned the
  unable-to-fetch error on every reddit-family domain.
- **WebSearch: not used as a substitute.** `site:reddit.com` queries
  on days 1-13 returned zero reddit thread URLs for any of the seven
  base subs in the last 14 days — only editorial substitutes. Wrong
  corpus; not promoted today either.
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is
  host-level, same failure mode applies to every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_20/reddit-women-uk.md`. Carry-forward set has
  been empty since 2026-06-09 per the 3-day DROP rule; nothing to
  inherit on the final day either.
- **Manual-drop directory:** `daily_data/2026_06_21/raw/reddit/` does
  not exist on disk. The per-run manual fallback pathway was flagged
  every day since day 5 — never adopted in this cycle.
- **Push-notification tool:** still not present in this routine's
  tool set. Day-14 close-out is filed in this artefact only, same as
  days 1-13. The project owner has received zero out-of-band
  escalations across the entire 14-day blocker.
- **Net result, end-of-window:** 0 of 14 days verified (0%). 14 of 14
  days (100%) placeholder. The 14-day Reddit-women-UK benchmark in
  its originally-scoped form is closed at 0% delivered corpus.

### Remediation options (for the NEXT cycle)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed. Single highest-
   leverage action.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix; bypasses
   WebFetch allowlist entirely.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/` AND patch the routine to read them
   first. Acceptable stopgap; requires routine code change.

### Cycle close-out summary

| Metric | Value |
|---|---|
| Window | 2026-06-08 → 2026-06-21 (14 days) |
| Verified Reddit days | 0 / 14 (0%) |
| Placeholder days | 14 / 14 (100%) |
| Brand mentions captured | 0 |
| NEW signals captured | 0 |
| Adjacent subs sampled | 0 |
| Carry-forward set at close | empty (since 2026-06-09) |
| Blocker | host-level 403 on all reddit.com + mirrors |
| Owner unblock action taken | none across 14 days |
| Recommended next step | install allowlist + MCP, then restart |

**End of 14-day window. The blocker decision passes to the project
owner. No further daily artefacts in this cycle.**
