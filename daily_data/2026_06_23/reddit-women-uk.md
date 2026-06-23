# Reddit K-Skincare Mentions — last 24h — 2026-06-23

> **POST-WINDOW DAY 2.** The original 14-day Reddit-women-UK benchmark
> closed 2026-06-21 at 0/14 verified days (0%). Yesterday's post-window
> day-1 file (`daily_data/2026_06_22/reddit-women-uk.md`) re-confirmed
> the host-level outbound block and recommended pausing the schedule
> pending an owner-side allowlist or PRAW MCP install. No remediation
> observed in the ~24h since. This file is a status check, not a
> day-16 continuation of the closed benchmark.

## Re-test today (2026-06-23)

Identical failure to days 1-15 + post-window day 1. Block remains at
environment outbound network policy:

- `curl https://www.reddit.com/r/SkincareAddictionUK/new.json` →
  `HTTP/2 403`, `x-deny-reason: host_not_allowed` (header captured 08:04 UTC)
- `curl https://old.reddit.com/r/AsianBeauty/new.json` → `HTTP/2 403`,
  `x-deny-reason: host_not_allowed`
- `curl https://api.pullpush.io/reddit/search/submission/` →
  `HTTP/2 403`, `x-deny-reason: host_not_allowed`
- `curl https://www.redditle.com/...` (mirror) → `HTTP/2 403`
- `WebFetch https://www.reddit.com/...` → "Claude Code is unable to
  fetch from www.reddit.com"
- `daily_data/2026_06_23/raw/reddit/` does not exist on disk (no
  manual drop)

16 consecutive days, zero verified Reddit days. No owner action
between 2026-06-22 post-window day-1 close and 2026-06-23 retest
(~24 h elapsed).

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09) / NEW: 0
verified

## Brand mentions (last 24h)

No corpus retrievable. Carry-forward set empty (faded under 3-day DROP
rule on 2026-06-09). No new evidence today. Adjacent subs
(r/MakeupAddiction, r/SkincareAddictionPale, r/femalefashionadvice)
not sampled — same host-level 403 applies to all reddit.com paths.

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| — | — | 0 | 0 | 0 | n/a (no corpus) |

## Top posts (5-10)

None. Same as days 1-15 and post-window day 1.

## Recurring vocabulary (top 10)

Empty. Same as days 1-15 and post-window day 1.

## Pain points

Empty. Standing hypotheses (Ireland 18-34 shipping/availability gap,
slugging fatigue, actives over-stacking burnout, UVA-reformulation
confusion post-2025 EU update, dupe-culture backlash) remain
notebook-only; forwarded into the restart's day-1 hypothesis sheet
when the corpus comes back online.

## Faded / contradicted carry-forwards

- Faded set unchanged (16th consecutive day empty): Beauty of Joseon,
  medicube, Biodance, Anua, SKIN1004, COSRX, mixsoon, Round Lab +
  10 vocabulary terms (last seen pre-2026-06-09).
- Contradicted: none — contradiction requires evidence, and there is
  none.

## Content strategy notes

Three actionable items. Urgency tier = **POST-WINDOW DAY 2, RESTART
PENDING**. Items are unchanged from yesterday because the situation
is unchanged.

1. **Pause this scheduled routine until the blocker is fixed.** The
   schedule has now produced 16 consecutive zero-corpus files (14
   in-window + 2 post-window). Continuing to fire it against a
   host-blocked endpoint costs container compute, clutters
   `daily_data/`, and produces no benchmark value. Pause the
   schedule; re-clock a fresh 14-day window starting the day Reddit
   becomes reachable.
2. **Owner action, ~2 min — highest leverage:** allowlist
   `reddit.com` and subdomains in the Claude Code on the Web
   environment outbound network policy. Docs:
   https://code.claude.com/docs/en/claude-code-on-the-web. This has
   been the single highest-leverage action since day 5; it remains
   so 11 days later.
3. **Durable fix, ~30 min:** install a PRAW-based Reddit MCP server
   (`adhikasp/mcp-reddit` or `jordanburke/reddit-mcp-server`) with a
   free Reddit script-app credential set. MCP traffic does not
   traverse the WebFetch host allowlist, so the routine becomes
   durable against future network-policy changes. Combine with
   item 2.

## Data quality

- Live Reddit access: BLOCKED. Identical signature across 16
  consecutive days.
- WebSearch substitutes: not promoted. `site:reddit.com` returns
  editorial/SEO substitutes, not raw threads — wrong corpus for
  "unfiltered consumer voice."
- Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice): not attempted; same host-level failure.
- Manual-drop directory `daily_data/2026_06_23/raw/reddit/`: absent.
- Push-notification tool: still not present in this session. Owner
  has received zero out-of-band escalations across 16 days; this
  file remains the only escalation surface.
- Yesterday's carry-forward source loaded:
  `daily_data/2026_06_22/reddit-women-uk.md`. Inherited set empty
  (faded since 2026-06-09).

### Window status

| Metric | Value |
|---|---|
| Original window | 2026-06-08 → 2026-06-21 (closed at 0/14) |
| Post-window day | 2 (2026-06-23) |
| Verified Reddit days since blocker began | 0 of 16 |
| Blocker | host-level 403 on all reddit.com + mirrors + pullpush |
| Owner unblock action taken | none across 16 days |
| Recommended next step | pause schedule; allowlist + MCP; restart |

**Recommendation: pause this scheduled routine pending unblock.**
