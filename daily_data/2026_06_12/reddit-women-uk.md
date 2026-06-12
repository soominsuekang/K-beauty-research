# Reddit K-Skincare Mentions — last 24h — 2026-06-12

> **DAY 5 OF UNRESOLVED BLOCKER — STATISTICAL FLOOR BREACHED TODAY.**
> 5 of 14 benchmark days (~36%) are now placeholder files. Above this
> threshold, any running average, trend line, sentiment shift, or
> brand-velocity ranking produced from the completed window cannot be
> presented to a stakeholder without a caveat that voids most of its
> operational value. The benchmark's confidence interval has formally
> failed the project's own published threshold.
>
> Re-tested today (all FAILED): `www.reddit.com/r/{sub}/new.json`,
> `old.reddit.com`, `api.reddit.com`, `www.redditmedia.com`, `.rss`
> variants, `api.pullpush.io`, `libreddit.privacydev.net`,
> `redlib.catsarch.com`, `safereddit.com`, `teddit.adminforge.de`,
> `eu.redlib.privacyredirect.com`. All returned 403, ECONNREFUSED, or
> "Host not in allowlist". WebSearch `site:reddit.com` queries returned
> no links, or returned editorial/wholesaler results that are NOT
> Reddit threads and would corrupt the benchmark if promoted.
>
> Fix remains ~2 minutes (allowlist `reddit.com` + subdomains in the
> environment outbound policy). Push notification sent today.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (set was emptied 2026-06-09) / NEW: 0 verified

The DIVERSITY rule (≥3 NEW Reddit signals/day, plus 1-2 adjacent subs)
cannot be satisfied without raw Reddit. Editorial substitutes — blog
posts, wholesaler guides, retailer SEO pages, YouTube shorts — exist
and are easy to fetch, but promoting them to the benchmark would mix
SEO/PR-driven language into a deliberately consumer-voice dataset.
That distortion is the exact failure mode the methodology was
designed to prevent.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| medicube | BASE | 0 | — | — | no signal — blocked (day 5) |
| COSRX | BASE | 0 | — | — | no signal — blocked (day 5) |
| Beauty of Joseon | BASE | 0 | — | — | no signal — blocked (day 5) |
| d'Alba | BASE | 0 | — | — | no signal — blocked (day 5) |
| AXISY | BASE | 0 | — | — | no signal — blocked (day 5) |
| mixsoon | BASE | 0 | — | — | no signal — blocked (day 5) |
| Dr.Melaxin | BASE | 0 | — | — | no signal — blocked (day 5) |
| Anua | BASE | 0 | — | — | no signal — blocked (day 5) |
| Isntree | BASE | 0 | — | — | no signal — blocked (day 5) |
| Numbuzin | BASE | 0 | — | — | no signal — blocked (day 5) |
| Round Lab | BASE | 0 | — | — | no signal — blocked (day 5) |
| VT | BASE | 0 | — | — | no signal — blocked (day 5) |
| Purito | BASE | 0 | — | — | no signal — blocked (day 5) |
| SKIN1004 | BASE | 0 | — | — | no signal — blocked (day 5) |
| Biodance | BASE | 0 | — | — | no signal — blocked (day 5) |
| Laneige | BASE | 0 | — | — | no signal — blocked (day 5) |

**No NEW brand rows.** The diversity floor cannot be met from non-Reddit
sources without inflating the benchmark's confidence falsely. Editorial
chatter today happened to surface Anua (Boots UK/IE expansion narrative)
and a BoJ-vs-COSRX wholesale comparison — both are PR/SEO artefacts,
not Reddit consumer voice, so they are explicitly NOT entered as
verified mentions.

## Top posts (5-10)

**None retrievable.** Day 5 in a row. Zero Reddit URLs, titles, scores,
or comment counts captured from any of the 7 base subs or the 3
adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
r/femalefashionadvice). The methodology's primary deliverable is empty
for the fifth consecutive day.

## Recurring vocabulary (top 10)

**Empty.** The 10 inherited vocabulary terms faded 2026-06-09 alongside
the brand carry-forwards. Re-collecting vocabulary requires raw post
bodies and comment threads; editorial substitutes systematically launder
out the colloquial phrasing the benchmark exists to capture.

## Pain points

**Empty.** Pain points only emerge from raw user posts. None could be
verified on days 1-5.

Standing hypotheses retained in the notebook (NOT promoted to benchmark
signal): shipping/availability gap for Ireland 18-34, slugging fatigue,
actives over-stacking burnout. Testable only once raw Reddit access
returns.

## Faded / contradicted carry-forwards

- **Faded set (emptied 2026-06-09, unchanged):** Beauty of Joseon,
  medicube, Biodance, Anua, SKIN1004, COSRX, mixsoon, Round Lab plus
  the 10 vocabulary terms (glass skin, slugging, barrier-first,
  fermented ceramides, lab-grown ginseng, PDRN/pink peptide,
  bio-collagen, prebiotic complex, minimalist routine, heartleaf). No
  new fades possible today — the set has been empty for 3 days.
- **Contradicted:** None. Contradiction requires raw threads.

**Net carry-forward state going into 2026-06-13: empty.** Day 6 (if
unblocked) starts from the BASE seed only. Any "rebuild" of the
carry-forward set will need to start from day 1 of new data.

## Content strategy notes

3 actionable items — the urgency tier has stepped up because the
statistical-floor breach has now occurred, not just been forecast:

1. **The 36% breach has happened.** Decision point for the project
   owner is no longer hypothetical: (a) re-baseline the 14-day window
   from the unblock date and accept a delayed deliverable, (b) lower
   the published confidence threshold and present the partial benchmark
   with a caveat, or (c) pause the routine until access is restored.
   "Continue as planned" is no longer one of the options that produces
   a defensible deliverable.
2. **The fix is still 2 minutes; the cost of inaction is now realised,
   not threatened.** Allowlist `reddit.com`, `www.reddit.com`,
   `old.reddit.com`, `api.reddit.com` in the environment's outbound
   policy (Claude Code on the web → environment settings → network
   policy). Reddit JSON read endpoints are unauthenticated; no API key
   required. Docs: https://code.claude.com/docs/en/claude-code-on-the-web.
3. **Install a PRAW-based Reddit MCP server as the durable fix.** MCP
   traffic isn't gated by the WebFetch allowlist, so it bypasses this
   failure mode entirely. Candidates: `adhikasp/mcp-reddit`,
   `jordanburke/reddit-mcp-server`. Free Reddit script-app credential
   set, ~30 min one-time setup. Pays back the first time this benchmark
   is re-run, and prevents the next access-policy change from breaking
   the routine again.

## Data quality

- **Live Reddit access: BLOCKED (day 5).** Identical failure pattern
  to days 1-4. Every reddit.com endpoint, every public mirror, and the
  Pushshift-replacement mirror returned 403, ECONNREFUSED, or "Host not
  in allowlist".
- **WebSearch: works, but `site:reddit.com` is unindexed for our
  queries.** Today's variant ("COSRX Anua Beauty of Joseon 2026 UK
  Ireland") returned only blog posts, wholesaler guides, and retailer
  SEO pages — not Reddit threads. These are the wrong corpus for this
  benchmark.
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually — blocker is at
  the reddit.com host level, identical failure mode for every subreddit.
- **Yesterday's carry-forward source:** loaded from
  `daily_data/2026_06_11/reddit-women-uk.md`. Carry-forward set
  emptied 2026-06-09 per the 3-day DROP rule; nothing to inherit.
- **Net result:** 0 verified mentions on day 5. 5 of 14 benchmark days
  (~36%) are placeholder files. Statistical-floor threshold is now
  formally crossed.

### Remediation options (unchanged; urgency = realised)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/`; the routine can read from disk.

**The benchmark has now crossed its own statistical floor. Day 6
onward will compound the breach until one of the three remediation
options is applied.**
