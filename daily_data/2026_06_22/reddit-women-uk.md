# Reddit K-Skincare Mentions — last 24h — 2026-06-22

> **POST-WINDOW DAY 1.** The 14-day Reddit-women-UK benchmark closed
> 2026-06-21 at 0/14 verified days (0%). Yesterday's close-out
> artefact (`daily_data/2026_06_21/reddit-women-uk.md`) handed the
> unblock decision to the project owner and recommended no further
> daily artefacts in this cycle. This file exists because the routine
> is still scheduled; it is a one-line status check, not a day-15
> extension of the closed benchmark.

## Re-test today (2026-06-22)

Identical failure to days 1-14. Block remains at environment outbound
network policy:

- `curl https://www.reddit.com/r/SkincareAddictionUK/new.json` →
  `HTTP/2 403`, `x-deny-reason: host_not_allowed`
- `curl https://old.reddit.com/r/AsianBeauty/new.json` → `HTTP/2 403`,
  `x-deny-reason: host_not_allowed`
- `curl https://api.pullpush.io/reddit/search/submission/` →
  `HTTP/2 403`, `x-deny-reason: host_not_allowed`
- `WebFetch https://www.reddit.com/...` → "Claude Code is unable to
  fetch from www.reddit.com"
- `daily_data/2026_06_22/raw/reddit/` does not exist on disk

No remediation action observed between 2026-06-21 close-out and
2026-06-22 retest (16 hours elapsed). Owner-side unblock
(allowlist `reddit.com` in environment outbound policy, OR install
PRAW MCP server) has not occurred.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (empty since 2026-06-09) / NEW: 0
verified

## Brand mentions (last 24h)

No corpus retrievable. Carry-forward set is empty (faded under 3-day
DROP rule on 2026-06-09). Nothing to inherit into post-window. No
new evidence today.

## Top posts (5-10)

None. Same as days 1-14.

## Recurring vocabulary (top 10)

Empty. Same as days 1-14.

## Pain points

Empty. Standing hypotheses (Ireland 18-34 shipping/availability gap,
slugging fatigue, actives over-stacking burnout, UVA-reformulation
confusion post-2025 EU update, dupe-culture backlash) remain notebook-
only and are forwarded to the restart's day-1 hypothesis sheet.

## Faded / contradicted carry-forwards

- Faded set unchanged (15th consecutive day empty): Beauty of Joseon,
  medicube, Biodance, Anua, SKIN1004, COSRX, mixsoon, Round Lab +
  10 vocabulary terms.
- Contradicted: none.

## Content strategy notes

Three actionable items. Urgency tier = **POST-WINDOW, RESTART
PENDING**.

1. **Stop running this routine until the blocker is fixed.** The
   schedule is producing zero-corpus files and now zero-corpus
   post-window files. Pause the schedule and re-clock a fresh 14-day
   window starting the day Reddit becomes reachable. Continuing to
   run the routine against a host-blocked endpoint costs container
   compute and produces no benchmark value.
2. **Owner action, ~2 min:** allowlist `reddit.com` and subdomains in
   the Claude Code on the Web environment outbound network policy.
   Docs: https://code.claude.com/docs/en/claude-code-on-the-web. This
   has been the single highest-leverage action since day 5. It is
   still the single highest-leverage action.
3. **Durable fix, ~30 min:** install a PRAW-based Reddit MCP server
   (`adhikasp/mcp-reddit` or `jordanburke/reddit-mcp-server`) with a
   free Reddit script-app credential set. MCP traffic bypasses the
   WebFetch host allowlist, so the routine is durable against future
   network-policy changes. Combine with item 2.

## Data quality

- Live Reddit access: BLOCKED. Identical signature across 15
  consecutive days.
- WebSearch substitutes: not promoted. `site:reddit.com` returns
  editorial/SEO substitutes, not raw threads — wrong corpus for
  unfiltered consumer voice.
- Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice): not attempted; same host-level failure.
- Manual-drop directory `daily_data/2026_06_22/raw/reddit/`: absent.
- Push-notification tool: still not present in this routine. Owner
  has received zero out-of-band escalations across 15 days.
- Yesterday's carry-forward source loaded:
  `daily_data/2026_06_21/reddit-women-uk.md`. Inherited set empty.

### Window status

| Metric | Value |
|---|---|
| Original window | 2026-06-08 → 2026-06-21 (closed at 0/14) |
| Post-window day | 1 (2026-06-22) |
| Verified Reddit days since blocker began | 0 of 15 |
| Blocker | host-level 403 on all reddit.com + mirrors |
| Owner unblock action taken | none across 15 days |
| Recommended next step | pause schedule; allowlist + MCP; restart |

**Recommendation: pause this scheduled routine pending unblock.**
