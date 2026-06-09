# Creator-UK-Female — Surge Edition — 2026-06-09

## DATA NOTICE — TODAY'S CRAWL DEGRADED

Today's local FastMoss crawl finished at 2026-06-09T08:30 but returned **only Italy region** for the two viral inputs:
- `daily_data/2026-06-09/fastmoss_raw/viral_korean_skincare_7d.json` → 1 video, IT
- `daily_data/2026-06-09/fastmoss_raw/viral_kbeauty_7d.json` → 6 videos, IT

No UK rows in either file. Likely a region-toggle or auth issue in the crawler script — the other UK jobs (`growthrank_beauty_gb_daily`, `risingstar_beauty_gb`, `newlisted_skincare_gb`) all returned full 30-row payloads, so the FastMoss endpoint itself is healthy. The region for the two `viral_*` jobs flipped or defaulted to IT this run.

**Falling back to**: yesterday's UK crawl `daily_data/2026-06-08/fastmoss_raw/` as the "today" baseline, and `daily_data/2026-06-07/fastmoss_raw/` as "yesterday". The diff below is therefore one day behind — every reference to "today" means the **06-08 7d viral pool** unless otherwise noted. Sun-master-report should treat this run as a 1-day-stale surge snapshot, not a fresh one.

## Today's diff at a glance
- Yesterday viral pool (06-07 UK): **57** unique creators
- Today viral pool (06-08 UK): **52** unique creators
- NEW today: **12** (creators in 06-08 not in 06-07)
- DROPPED: **18** (creators in 06-07 not in 06-08)
- Date source used: **2026-06-08** (today's UK crawl returned IT-only — see DATA NOTICE)

NEW today (UK): AXISY UK [brand], Amelia ✨Reviews +UGC, Ashleigh McNab ❤️, DanMadeMeBuyIt, KIBODI STORE [shop], Omotoyosi 🦋💜, Shop Tik Collections [shop], TikTokShop Anna's Beauty Finds [shop], poppylivingstonex, rachelrookebeauty, wishuojha, 𝕜𝕒𝕥𝕚𝕖. After filtering brand/shop accounts → **8 real creators NEW**.

## Surge creators — deep dive

### 1. @omotoyosi (display: Omotoyosi 🦋💜)
- **Handle / display name**: Omotoyosi 🦋💜
- **Niche**: K-beauty creator-economy joiner — referral/affiliate posting style, not product reviewer
- **Follower count + avg views + ER**: 5.8k followers, 651 views on surge video, **25.49% ER** (141 likes / 651 views) — exceptional but on a thin base
- **Today's surge video** (vid `7647530195825609987`, published 2026-06-04 14:23 UK): caption "Get locked in and join picky app, Picky now invites Australian creators to have a chance to collab with kbeauty brands. You can always get in with invitation code [409471F5] when signing up ✅ @Picky KBeauty #picky #pickycreator #referral #kbeauty". 59-second talking-head referral pitch. What made it pop: **not a product video — a creator-economy onboarding video**. The 25% ER is driven by a small intent-locked audience clicking through her code. FastMoss surfaced it because the K-beauty hashtag cluster + an organic (non-ad) post is rare in the 7d UK pool.
- **Past content pattern**: insufficient FastMoss data (single-video surface). Bio-side: posts from UK but pushing "Australian creators" code → likely network of Picky referrers, not a stand-alone K-skincare reviewer. **Strong flag for paid-affiliate funnel, not organic K-beauty enthusiast.**
- **Voice/persona signature**: transactional, network-marketer-adjacent, code-driven, low-aesthetic. Ireland 18–34 women would **not** trust her for product judgement; she reads as MLM-style affiliate, not creator-curator. Low credibility transfer.
- **Demographic guess**: Black/African woman, late 20s, UK-based, possibly NW England or West Midlands.
- **Brand alignment**: **None of our brand stack.** Picky is a B2B creator-matching layer; she's pushing the platform, not a K-brand SKU. VT/Anua/Mixsoon would not partner — she's not a curator. Medicube/Dr.Melaxin would not partner — she has no product-trust signal.
- **Persona mapping**: **None of the 8 personas fit.** This is a 9th archetype — **The K-Beauty Creator-Economy Recruiter** — pushing other creators to join the matching layer, not pushing skincare to consumers. Flag for creator-demo-map's new-archetype watchlist.
- **Verdict**: **One-hit wonder.** The 25% ER is a referral-list artefact, not a product-video pattern. She is NOT a Tier-1 candidate and not useful for the IE brief. **Real value of the signal**: Picky (the K-beauty creator-matching platform) is recruiting UK micro-creators via referral codes — a data point for our Ireland white-space play. If we want to seed an IE K-skincare creator, **Picky is now a discoverable recruitment channel** (vs hand-finding via Favikon).

### 2. @poppylivingstonex
- **Handle / display name**: poppylivingstonex
- **Niche**: Mid-tier paid skincare AD creator — first week of brand partnership
- **Follower count + avg views + ER**: 36.4k followers, 1.2k views on surge video, **4.31% ER** (53 likes / 1.2k views). 4.3% ER on a paid post is notably above the Medicube paid cohort baseline (0.3–1.5%).
- **Today's surge video** (vid `7647492418152975638`, published 2026-06-04 11:56 UK): "Only been using medicube for a week and the results already are insane! Medicube = Glowy skin🤭 #fyp #foryoypage #medicube #pdrn @medicube UK" — 44-second short. Hook is the **timeline claim** ("one week → results insane"). This is the canonical Medicube "new convert" creator template: short-timeline before/after with PDRN hashtag.
- **Past content pattern**: not in FastMoss creator JSON; not in 06-07 viral pool. **First-time entry into K-skincare context.** Bio-side, "x" suffix + lifestyle handle suggests general beauty/lifestyle creator who took Medicube's first-week brief. **Flag: brand-seeded — Medicube is recruiting fresh mid-tier UK lifestyle creators into their paid stack.**
- **Voice/persona signature**: enthusiastic-convert, low-friction, lifestyle-adjacent rather than skincare-deep. Ireland 18–34 women: **moderate trust** — the "I just tried this" framing reads honest at first viewing but doesn't survive a feed of similar Medicube week-1 posts.
- **Demographic guess**: white British, early–mid 20s, lifestyle/beauty generalist.
- **Brand alignment**: **Medicube only** (paid-push tier). Fits the cohort exactly: Chloe Ferry → Nath Henry → Stephanie Vavron → poppylivingstonex is the same lane.
- **Persona mapping**: Closest to **Persona 4 (Frishta couple/conversational)** in tone but without the relationship-vulnerability layer; structurally fits the "paid mid-tier convert" cohort that sits **outside** the 8 personas. The 8 personas were modelled on organic-strong creators; poppylivingstonex is the paid-tier inverse. No clean fit.
- **Verdict**: **Paid-only.** Medicube's UK creator stable is growing — she is a stable-recruit indicator, not a Tier-1 candidate. **Worth tracking only as Medicube-spend proxy** (when their stable grows, paid CAC rises and the "Medicube ceiling" hypothesis hardens).

### 3. @ashleighmcnab (display: Ashleigh McNab ❤️)
- **Handle / display name**: Ashleigh McNab ❤️
- **Niche**: Long-form GRWM-for-bed, multi-brand layered routine, narrative-heavy paid creator
- **Follower count + avg views + ER**: 55.3k followers, 2.9k views on surge video, **2.4% ER** (54 likes / 2.9k views). 2.4% ER on a 1,400+ character caption is solid — long-form copy depresses ER mechanically and she still cleared baseline.
- **Today's surge video** (vid `7647133682003758358`, published 2026-06-03 12:44 UK): 49-second "Come get ready for bed with me this evening 💖" GRWM-bed. Stack: **Wonderskin Cleansing Balm → Dr. Melaxin Pink Serum → Medicube PDRN Pink Serum → Medicube Pink Jelly Cream**. Hook is a defensive frame: **"I've got a TikTok Shop restriction for the next 3 days, so I can't link any of the products"** — turns a platform punishment into a "I'm telling you because the results speak for themselves, not because I'm getting paid" credibility play. What made it pop: the **TikTok-shop-restriction framing is a novel trust-recovery hook** — same content, but stripped of the affiliate link surface. Anti-de-influencing maneuver.
- **Past content pattern**: not in 06-07 viral pool. First entry. Caption style + brand layering (Wonderskin + Dr.Melaxin + Medicube in one routine) reads as **seasoned paid-skincare creator who normally lives in the link-attached routine GRWM lane**. The TikTok Shop restriction is what surfaced her this week — she had to lean on narrative.
- **Voice/persona signature**: warm, methodical, sequenced-routine, story-anchored ("microneedling in a bottle", "I love using it as an overnight mask because I wake up with skin that looks plump"). Reads narrative-confident, not chemist-clinical. Ireland 18–34 women: **moderate-to-high trust** when the link is missing — the post survives the de-influencing filter.
- **Demographic guess**: white British, late 20s–early 30s, possibly Scottish or NE English (McNab surname).
- **Brand alignment**: **Medicube and Dr.Melaxin** (paid-push tier). She is multi-brand-friendly within that tier. Wonderskin (J-beauty-adjacent / cleansing-balm category) extends her into balm-tier too. VT/Anua/Mixsoon could partner if they wanted the long-form narrative GRWM slot — she is one of the cleanest crossover candidates if the organic-tier brands wanted to test paid (none of them currently do).
- **Persona mapping**: Strongest fit is **Persona 3 (ZhilaBeauty/Companion)** — the "I am doing my routine RIGHT NOW, you can too" framing, evening routine, sequenced narrative — but Ashleigh executes it inside a **paid stack**, where Zhila uses organic VT/Anua/Mixsoon. So she's **ZhilaBeauty-format × paid-tier brand stack**. This is a **persona-card amendment candidate**: Persona 3 may have a paid-tier variant (long-form companion GRWM with Medicube/Dr.Melaxin) that we did not document on 2026-06-06.
- **Verdict**: **Keep watching.** If she posts a follow-up paid GRWM in the next 48h with the same TikTok-shop-restriction framing — or **without** the restriction (now restriction has lifted) — she becomes a Tier-1-candidate for the IE paid-GRWM bench. If she goes silent post-restriction, the 06-03 video was an artifact of the platform punishment, not a sustained pattern. **Today's video is the second-cleanest narrative-GRWM-as-paid post we have logged across 4 days** (cleanest: Bina13's Dr.Melaxin Peel Shot, but that one is shorter).

## Tier-1 health (one line each)
- **James Welsh**: posted (vid `7646773773840010518`, 62.0k views, **1.3% ER** vs 5.58% baseline — well below; AD for **Medicube** "simple pore care for teenage skin"). 🚩 **First Medicube AD captured for James Welsh** — this BREAKS the brand-creator split documented in `persona-cards.md` (he was organic-tier VT/Anua/Mixsoon). Either the Medicube paid ceiling has cracked or he's testing one-off; major flag for sun-master-report.
- **Graces.faces_** (Grace Marsh): **no posts in 7d UK viral pool today**. Brand mentions stale at VT/Anua/Mixsoon baseline. Cadence-watch — second day absent. Not yet abnormal but trending toward inactive in the FastMoss surface.
- **ZhilaBeauty**: **no posts in 7d UK viral pool today**. Baseline avg 321.8k views with 4.95% ER — silence is unusual at her scale; either she's posted non-K content or FastMoss missed her. Watch tomorrow.
- **Frishta** (frishtaxx): **no posts in 7d UK viral pool today**. Avg ER 8.59% baseline — second day absent from K-viral surface; if she's still posting just not K, that's a quiet pivot signal. Watch.
- **Cindy Lee** (ab61e): **no posts in 7d UK viral pool today**. Avg views 43.5k baseline; smallest of Tier-1, so absence is the most expected here. No anomaly flag.

## Departures
- **@nathhenry** (Nath Henry, 464k, BOJ AD lane): was rank 1 of 06-07 viral_korean_skincare with 55.0k views on BOJ Apricot Peeling Gel; **dropped from 06-08 viral pool entirely**. Yesterday's collection-reminder asked whether he'd post a 3rd BOJ video this week to confirm BOJ-UK paid pivot; the answer is **no**. BOJ-via-paid hypothesis softens, organic-first posture for BOJ-UK holds.
- **@melissajade** (Melissa Jade 💚, 487k): was 16.9k views on 06-07 K-content; dropped from 06-08. Likely 7d-window roll-off (her video was published before 06-01); not a behavior change. Re-check 06-09 cycle if/when crawl recovers.

## Carry-forward for tomorrow
- watch **@ashleighmcnab** (does post-restriction follow-up confirm sustained narrative-GRWM-as-paid pattern, or was the 06-03 hit an artifact of the TikTok Shop punishment?), **@poppylivingstonex** (does Medicube run a second week-1 post to confirm she's in the paid stable or was 06-04 a one-shot?)
- also: **fix the UK-region crawl flag for `viral_kbeauty_7d` and `viral_korean_skincare_7d`** before tomorrow's 10:00 Dublin run, or this surge file rolls one more day stale.

## Notes for sun-master-report
- 🚩 **James Welsh × Medicube AD** (vid `7646773773840010518`, 62k views, 1.3% ER) is a **brand-creator-split breakage**. Persona-cards 2026-06-06 documents Welsh as organic-tier VT/Anua/Mixsoon; this Medicube AD puts him in the paid-push tier for at least one slot. Possible explanations: (a) Medicube cracked Welsh's pricing — paid-ceiling shifted; (b) one-off product test, not portfolio shift; (c) Welsh segmenting paid-vs-organic by SKU rather than by brand. **Recommend re-baselining the brand-creator split** in the Master Report — it was a foundational assumption underlying the IE brand-target recommendation (VT/Anua/Mixsoon for organic IE seeding).
- 🚩 **Picky app (K-beauty creator-matching platform) is recruiting UK micro-creators via referral codes** (Omotoyosi @ 5.8k followers, code `409471F5`). For our IE white-space play, Picky is a **discoverable recruitment surface** — if we want to seed an IE K-skincare creator, we no longer have to hand-find via Favikon; we can register on Picky as the brand side and let creator-matching surface IE micro-creators. Worth adding to the Day-1 brief as a tactical surface.
- **New archetype watchlist**: "The K-Beauty Creator-Economy Recruiter" (Omotoyosi pattern) — referral-code-driven content that surfaces because of K-beauty hashtag-cluster + organic flag, not because of product judgement. Not a fit for our 8 personas; not a brief target; **noise filter for the surge pool going forward**.
- **Persona 3 (ZhilaBeauty/Companion) paid-tier variant**: Ashleigh McNab 06-03 video suggests a paid-tier variant of the companion format exists (Medicube + Dr.Melaxin layered routine, narrative-heavy, evening). If sustained on next 1–2 days, persona-cards.md needs an addendum.
- **BOJ paid-test hypothesis update**: Nath Henry did not produce a 3rd BOJ video this week. The BOJ-via-Sissel-Lab IE play remains organic-first; the defensive paid-tweak the Sunday master report flagged is **not required this cycle**.
- **Crawl-region failure**: today's local crawl regression (UK → IT) is the second consecutive day of pipeline noise (Day 2 had handle-resolution gaps; Day 3 had Italy-only viral pulls). Flag for `_run_summary.json` quality monitoring.
