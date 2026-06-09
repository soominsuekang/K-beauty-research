# Reddit K-Skincare Mentions — last 24h — 2026-06-09

> **DAY 3 OF UNRESOLVED BLOCKER — CARRY-FORWARD FADE CLIFF TRIGGERED.**
> Same blocker as 2026-06-07 and 2026-06-08. All reddit.com endpoints
> (www, old, api, .rss), every Reddit mirror tested today
> (libreddit.privacydev.net, redlib.catsarch.com, safereddit.com,
> teddit.net, eu.redlib.privacyredirect.com), and every Pushshift mirror
> (api.pullpush.io) returned 403 / "Host not in allowlist" / ECONNREFUSED.
> WebSearch returns no `site:reddit.com` hits for any K-beauty query
> tried (4 variants today).
>
> **Per the DROP rule (no mention for 3 days → faded), every brand carried
> forward from 2026-06-07 with no Reddit verification on 06-07, 06-08,
> 06-09 is now FADED.** This is not a contradicted-by-evidence fade
> (which would require raw threads showing decline); it is a
> no-evidence-available fade — the carry-forward set has aged out.
>
> **3 of 14 benchmark days now lost (~21%).** Push notification sent.

## Tracking distribution
BASE: 0 verified / CARRY-FORWARD: 0 (all 8 aged out today) / NEW: 0 verified

The DIVERSITY rule cannot be satisfied (≥3 NEW Reddit signals/day);
satisfying it from editorial sources would corrupt the benchmark.

## Brand mentions (last 24h)

| Brand | Bucket | # posts | Upvotes | Comments | Sentiment |
|---|---|---|---|---|---|
| Beauty of Joseon | FADED (was CARRY-FORWARD) | 0 | — | — | faded — 3 days no Reddit verification |
| medicube | FADED (was CARRY-FORWARD) | 0 | — | — | faded — 3 days no Reddit verification |
| Biodance | FADED (was CARRY-FORWARD) | 0 | — | — | faded — 3 days no Reddit verification |
| Anua | FADED (was CARRY-FORWARD) | 0 | — | — | faded — 3 days no Reddit verification |
| SKIN1004 | FADED (was CARRY-FORWARD) | 0 | — | — | faded — 3 days no Reddit verification |
| COSRX | FADED (was CARRY-FORWARD) | 0 | — | — | faded — 3 days no Reddit verification |
| mixsoon | FADED (was CARRY-FORWARD) | 0 | — | — | faded — 3 days no Reddit verification |
| Round Lab | FADED (was CARRY-FORWARD) | 0 | — | — | faded — 3 days no Reddit verification |
| d'Alba | BASE | 0 | — | — | no signal surfaced (blocked) |
| AXISY | BASE | 0 | — | — | no signal surfaced (blocked) |
| Dr.Melaxin | BASE | 0 | — | — | no signal surfaced (blocked) |
| Isntree | BASE | 0 | — | — | no signal surfaced (blocked) |
| Numbuzin | BASE | 0 | — | — | no signal surfaced (blocked) |
| VT | BASE | 0 | — | — | no signal surfaced (blocked) |
| Purito | BASE | 0 | — | — | no signal surfaced (blocked) |
| Laneige | BASE | 0 | — | — | no signal surfaced (blocked) |

**No NEW brand rows.** The diversity floor cannot be met from editorial
sources without inflating the benchmark's confidence falsely.

## Top posts (5-10)

**None retrievable.** Day 3 in a row. Zero Reddit URLs, titles, scores,
or comment counts captured from any of the 7 base subs or any of the 3
adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
r/femalefashionadvice). The methodology's primary deliverable is empty
for the third consecutive day.

## Recurring vocabulary (top 10)

**Empty.** All 10 inherited-from-editorial terms (glass skin, slugging,
barrier-first, fermented ceramides, lab-grown ginseng, PDRN/pink peptide,
bio-collagen, prebiotic complex, minimalist routine, heartleaf) fade
today by the same 3-day rule applied to brands. Vocabulary cannot be
inherited indefinitely from non-Reddit sources without becoming a
self-reinforcing artifact.

## Pain points

**Empty.** Pain points only emerge from raw user posts; editorial
content systematically launders them out. None could be verified on
days 1-3.

Standing hypotheses retained in notebook (not in benchmark):
shipping/availability gap for Ireland 18-34, slugging fatigue, actives
over-stacking burnout. These remain testable only once raw Reddit
access is restored — they are NOT being treated as carry-forward signal.

## Faded / contradicted carry-forwards

- **Faded (today, 8 brands):** Beauty of Joseon, medicube, Biodance,
  Anua, SKIN1004, COSRX, mixsoon, Round Lab — all aged out after 3
  consecutive days with no Reddit verification (06-07, 06-08, 06-09).
- **Faded (today, 10 vocabulary terms):** glass skin, slugging,
  barrier-first / skin barrier care, fermented ceramides, lab-grown
  ginseng, PDRN / pink peptide, bio-collagen, prebiotic complex,
  minimalist routine, heartleaf — same reason.
- **Contradicted:** None — contradiction requires raw threads.

**Net carry-forward state going into 2026-06-10: empty.** If access is
restored tomorrow, day 4 starts from the BASE seed only.

## Content strategy notes

3 actionable items:

1. **The blocker is now a hard project risk, not a tooling annoyance.**
   3 of 14 days lost = 21%; 5 days = the benchmark statistical floor
   is breached. The 2-minute fix is: add `reddit.com`, `www.reddit.com`,
   `old.reddit.com`, `api.reddit.com` to the environment's outbound
   allowlist (Claude Code on the web → environment settings). Reddit
   JSON read endpoints are unauthenticated; no API key required. Docs:
   https://code.claude.com/docs/en/claude-code-on-the-web.
2. **Reset expectations for the deliverable.** With the carry-forward
   set now empty, even an unblock on day 4 cannot recover the 14-day
   trend lines for the 8 faded brands — they will start from 0 on the
   unblock date. Recommend explicitly re-baselining the benchmark
   window from the unblock date forward (e.g. 14 days from unblock,
   not 14 calendar days from 2026-06-07). A mixed window of 3 empty
   days + 11 real days will skew every running average produced.
3. **Install a PRAW-based Reddit MCP server as the durable fix.** MCP
   traffic is not routed through the WebFetch allowlist, so it bypasses
   this class of failure entirely. Candidates: `adhikasp/mcp-reddit`,
   `jordanburke/reddit-mcp-server`. Setup: register a Reddit "script"
   app (free), add `client_id` + `client_secret` + UA to MCP server
   config, restart the environment. ~30 min one-time; pays back the
   first time this benchmark is re-run.

## Data quality

- **Live Reddit access: BLOCKED (day 3).** Re-tested today:
  `www.reddit.com/r/{sub}/new.json`, `old.reddit.com`, `reddit.com`
  (without www), `www.reddit.com/r/{sub}/.rss`, `api.pullpush.io`,
  `libreddit.privacydev.net`, `redlib.catsarch.com`, `safereddit.com`,
  `teddit.net`, `eu.redlib.privacyredirect.com`. All returned 403,
  "Host not in allowlist", or ECONNREFUSED.
- **WebSearch: works, but does NOT index `site:reddit.com`.** 4 query
  variants today (subreddit + brand + year, brand + year + reddit,
  multi-brand OR + reddit + UK, exact subreddit name + brand + year)
  all returned "no links found" or only editorial / TikTok domains
  (mamabella.uk, coreebeauty.com, tiktok.com).
- **Adjacent subs (r/MakeupAddiction, r/SkincareAddictionPale,
  r/femalefashionadvice):** not attempted individually because the
  blocker is at the reddit.com host level, not per-subreddit. Same
  failure mode applies to all subs.
- **Yesterday's carry-forward source:** loaded successfully from
  `daily_data/2026_06_08/reddit-women-uk.md`. Inherited 8 unverified
  brands and 10 vocabulary terms — all faded today per the 3-day rule.
- **Net result:** 0 verified mentions on day 3. 3 of 14 benchmark days
  (21%) are now placeholder files.

### Remediation options (unchanged across 3 days; urgency now critical)

1. **~2 min:** allowlist `reddit.com` + subdomains in environment
   outbound network policy. No API keys needed.
2. **~30 min:** install PRAW-based Reddit MCP server with a free
   Reddit script-app credential set. Long-term durable fix.
3. **Per-run manual:** drop raw Reddit JSON exports into
   `daily_data/{date}/raw/reddit/`; the routine can read from disk.

**Without any of the above, the remaining 11 benchmark days will be
the same placeholder file with the BASE-only table and an empty
carry-forward state.**
