# Reddit K-Skincare Mentions — last 24h — 2026-06-26

> **POST-WINDOW DAY 5.** The original 14-day Reddit-women-UK benchmark
> closed 2026-06-21 at 0/14 verified days (0%). Post-window days 1-4
> (2026-06-22 → 2026-06-25) re-confirmed an unchanged host-level
> outbound block on all reddit.com paths and the pullpush.io mirror,
> and recommended pausing the schedule pending an owner-side allowlist
> or PRAW MCP install. No remediation observed in the ~24h since.
> This file is a status check, not a day-19 continuation of the closed
> benchmark.

## Re-test today (2026-06-26)

Identical failure to days 1-15 + post-window days 1-4. Block remains
at the environment outbound network policy. Captured 08:05 UTC:

- `curl https://www.reddit.com/r/SkincareAddictionUK/new.json` →
  gateway `403 CONNECT tunnel failed`, agent-proxy
  `recentRelayFailures` records
  `kind: connect_rejected, detail: "gateway answered 403 to CONNECT
  (policy denial or upstream failure)", host: www.reddit.com:443`,
  `ts: 2026-06-26T08:05:04.351Z`
- `curl https://old.reddit.com/r/AsianBeauty/new.json` → exit 56,
  HTTP 000 (tunnel rejected — `old.reddit.com:443`,
  `ts: 2026-06-26T08:05:14.394Z`)
- `curl https://api.pullpush.io/reddit/search/submission/` → exit 56,
  HTTP 000 (tunnel rejected — `api.pullpush.io:443`,
  `ts: 2026-06-26T08:05:14.685Z`)
- `WebFetch https://www.reddit.com/...` — not attempted today; failed
  on days 1-15 + post-window days 1-4 with the same host gate.
- `daily_data/2026_06_26/raw/reddit/` does not exist on disk (no
  manual drop).

19 consecutive days, zero verified Reddit days. No owner action
between 2026-06-22 post-window day-1 close and the 2026-06-26 retest
(~96 h elapsed since first post-window escalation).

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

None. Same as days 1-15 + post-window days 1-4.

## Recurring vocabulary (top 10)

Empty. Same as days 1-15 + post-window days 1-4.

## Pain points

Empty. Standing hypotheses (Ireland 18-34 shipping/availability gap,
slugging fatigue, actives over-stacking burnout, UVA-reformulation
confusion post-2025 EU update, dupe-culture backlash) remain
notebook-only; forwarded into the restart's day-1 hypothesis sheet
when the corpus comes back online.

## Faded / contradicted carry-forwards

- Faded set unchanged (19th consecutive day empty): Beauty of Joseon,
  medicube, Biodance, Anua, SKIN1004, COSRX, mixsoon, Round Lab +
  10 vocabulary terms (last seen pre-2026-06-09).
- Contradicted: none — contradiction requires evidence, and there is
  none.

## Content strategy notes

Three actionable items. Urgency tier = **POST-WINDOW DAY 5, RESTART
PENDING**. Items are unchanged from yesterday because the situation
is unchanged.

1. **Pause this scheduled routine until the blocker is fixed.** The
   schedule has now produced 19 consecutive zero-corpus files (14
   in-window + 5 post-window). Continuing to fire it against a
   host-blocked endpoint costs container compute, clutters
   `daily_data/`, and produces no benchmark value. Pause the
   schedule; re-clock a fresh 14-day window starting the day Reddit
   becomes reachable.
2. **Owner action, ~2 min — highest leverage:** allowlist
   `reddit.com` and subdomains in the Claude Code on the Web
   environment outbound network policy. Docs:
   https://code.claude.com/docs/en/claude-code-on-the-web. This has
   been the single highest-leverage action since day 5; it remains
   so 14 days later.
3. **Durable fix, ~30 min:** install a PRAW-based Reddit MCP server
   (`adhikasp/mcp-reddit` or `jordanburke/reddit-mcp-server`) with a
   free Reddit script-app credential set. MCP traffic does not
   traverse the WebFetch host allowlist, so the routine becomes
   durable against future network-policy changes. Combine with
   item 2.

## Data quality

- Live Reddit access: BLOCKED. Identical signature across 19
  consecutive days. Today's gateway response logged in
  `recentRelayFailures` of the agent proxy
  (`www.reddit.com:443`, 08:05:04 UTC, `connect_rejected / 403`).
  `old.reddit.com` (08:05:14 UTC) and `api.pullpush.io` (08:05:14
  UTC) both returned exit 56 / HTTP 000 — same CONNECT-tunnel reject
  signature.
- WebSearch substitutes: not promoted. `site:reddit.com` returns
  editorial/SEO substitutes, not raw threads — wrong corpus for
  "unfiltered consumer voice."
- Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice): not attempted; same host-level failure.
- Manual-drop directory `daily_data/2026_06_26/raw/reddit/`: absent.
- Owner has received zero out-of-band remediation across 19 days;
  this file remains the only escalation surface. Sending a
  PushNotification today on the post-window day-5 mark to surface
  the standing blocker.
- Yesterday's carry-forward source loaded:
  `daily_data/2026_06_25/reddit-women-uk.md`. Inherited set empty
  (faded since 2026-06-09).

### Window status

| Metric | Value |
|---|---|
| Original window | 2026-06-08 → 2026-06-21 (closed at 0/14) |
| Post-window day | 5 (2026-06-26) |
| Verified Reddit days since blocker began | 0 of 19 |
| Blocker | host-level 403 on all reddit.com + mirrors + pullpush |
| Owner unblock action taken | none across 19 days |
| Recommended next step | pause schedule; allowlist + MCP; restart |

**Recommendation: pause this scheduled routine pending unblock.**
