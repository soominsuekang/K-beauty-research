# Creator-UK-Female — Surge Edition — 2026-06-11

## Today's diff at a glance

- Yesterday viral pool: 50 creators (last clean UK crawl 2026-06-08; 2026-06-09 returned IT-only, 2026-06-10 used as TODAY proxy)
- Today viral pool: 49 creators (2026-06-10 UK crawl — first clean UK pool since 06-08)
- Overlap (still in both): 15
- NEW today: 34
- DROPPED: 35
- **Date source used (not today)**: TODAY = 2026-06-10 fastmoss_raw; YESTERDAY = 2026-06-08 fastmoss_raw (06-09 IT-only, 06-11 morning crawl had no `fastmoss_raw/` directory at 10:00 Dublin scheduled run time).
- ✅ **Crawl-pipeline recovery confirmed for 2026-06-10**: `viral_korean_skincare_7d.json` and `viral_kbeauty_7d.json` both returned 50 + 30 UK records, restoring the diff function flagged broken in `daily_data/2026-06-10/creator-uk-female.md` (which actually wrote against the missing 06-09 crawl, not 06-10). The 06-11 morning crawl has not landed yet — pipeline owner should still verify the cron.

**Diff window caveat — important for reader**: this is a T+2 diff (06-10 vs 06-08), so 7d-roll-off is overstated vs a true 1-day diff. Roughly half of "DROPPED" is window roll-off (older-than-7d videos sliding out), not behavioural change. Surge picks below are filtered for fresh-post drivers only.

---

## Surge creators — deep dive

### 1. Stephanie Vavron — paid-tier mega-pop, NOT first-time K-skincare

| Field | Value |
|---|---|
| Handle / display | Stephanie Vavron (creator name as captured; FastMoss profile link: `https://www.fastmoss.com/media-source/video/7647647018399157526`) |
| Niche | Paid-tier lifestyle/beauty creator; medicube + Dr.Melaxin specialist (`paid-push` brand-creator-split tier) |
| Followers | 714.5k |
| Today's surge video | 06-04 21:56 — "Say goodbye 👋 to pores and blemishes with @medicube UK new bundle 💙 #skincare #blemishes #blackheads #skincaregoals #dealdrops" — 100s — **201.2k views @ 0.68% ER, AD=true** |
| 28d/90d baseline | 06-07 28d pool: 271.9k views (vid pub 2026-05-19 Medicube AD) → 06-08 28d pool same vid 313.3k views (still climbing). 90d pool: 187.9k Apr-27 Medicube AD; 105.0k Mar-22 Medicube organic. **Pattern: she is a stable Medicube top-of-funnel asset with 1 mega-hit per 4-6 weeks at 200-300k views, ER 0.5-0.8%.** |
| Past content pattern | Mentioned by name in `daily_data/2026-06-06/persona-cards.md` §brand-creator split as one of three creators (alongside Chloe Ferry, Nath Henry) used by Medicube/Dr.Melaxin for paid pushes. Not new to K-skincare — she rotated **out** of 7d viral pool on 06-08 (her May-19 hit aged off) and rotated back **in** today on the strength of the Jun-4 fresh AD. This is rotation, not a first-appearance. |
| Voice/persona signature | Sales-led, exclamation-heavy, hashtag-stacked, "deal-drop" register; reads as paid-creator-professional. Identical lane to Chloe Ferry but at slightly smaller scale (714k vs 1.2M) and noticeably better view-conversion-per-AD (her Medicube hits land 200-300k where Ferry's BOJ AD on 06-08 only hit ~21k). |
| Demographic guess | White British female, late 20s/early 30s, polished aspirational presentation. Audience: 18-34 female, broad-mainstream not skin-specialist. |
| Brand alignment | medicube (primary), Dr.Melaxin (paid-push tier) — **NOT for our IE organic-first plan**. Per persona-cards §brand-creator split: VT / Anua / Mixsoon = organic; medicube / Dr.Melaxin = paid. Stephanie sits firmly in the paid-only column. |
| Persona mapping | No match against the 8 organic-focused persona cards. Sits in the same de-facto "Paid-Tier Established" group as Chloe Ferry / Nath Henry, which the 8-card model deliberately excluded. **Not a new archetype candidate** — already named in cards §brand-creator split. |
| Verdict | **paid-only — do not pursue for IE organic seeding.** Watch her as a Medicube-paid-volume indicator only. The 201k landing tells us the Medicube UK ad budget is still firing at full force going into mid-June; this is supportive evidence for the brand-creator split holding (organic VT/Anua/Mixsoon side is uncontested by Medicube). |

### 2. MASUK LIMITED — organic BOJ editorial reappearance, consistent with Persona 8

| Field | Value |
|---|---|
| Handle / display | MASUK LIMITED (UK business-style channel) |
| Niche | Long-form K-skincare review / editorial — already canonised as **Persona Card 8 "The Regulator-Storyteller"** in `daily_data/2026-06-06/persona-cards.md` |
| Followers | 48.9k |
| Today's surge video | 06-03 19:08 — "Worlds Best Korean Skincare - Best Beauty of Joseon Review #skincare #koreanskincare #beautyofjoseon @Beauty of Joseon" — **136s, 7.6k views @ 4.02% ER, AD=false (organic)** |
| 90d/historic baseline | 90d pool: **265.4k views Mar-08 organic** K-review; **101.6k Mar-13 organic**; 8.0k May-30 Numbuzin AD (also seen in 06-07 and 06-09 search_brand_numbuzin pools). Pattern: organic ~5-10× more reach per video than AD, supporting Persona 8 thesis (this creator's audience rewards long-form editorial, punishes ad register). |
| Past content pattern | Mix of UK-business-channel naming and editorial-length K-review content. Long-form (>2 min) outperforms shorter cuts. Stable 4-15% ER on organic. Today's BOJ editorial (4.02% ER, 136s) is **consistent with the Mar-08 high-watermark format**. |
| Voice/persona signature | Editorial-narrator, regulator-tone, "Worlds Best" superlative leads, evidence-led structure. Not personality-led; structurally about *the product category*, not *the creator*. Ireland 18-34: high trust on category-curation framing, especially for skin-conscious 25-34 segment. |
| Demographic guess | Unclear; channel is business-channel-style not personal. Audience skews skin-engaged 22-34 mixed gender (high ER + long-form retention implies actively interested viewer, not algorithm-fed). |
| Brand alignment | Beauty of Joseon (today's video, organic), Numbuzin (recent AD). Both sit on the organic-friendly tier per brand-creator split. **Compatible with our IE organic-first BOJ play.** |
| Persona mapping | **Direct Persona 8 reinforcement.** No archetype update needed. |
| Verdict | **Tier-1 candidate for cross-list watch** — but the channel name (MASUK LIMITED, business-style) and unclear presenter identity weaken the direct IE-personality-graft. For IE we want a person-led variant of Persona 8 (named human, similar editorial-long-form structure). Today's hit reinforces the organic-BOJ trajectory; the **structural takeaway is that BOJ organic editorial is still landing at 4% ER**, which contrasts sharply with the BOJ AD on Chloe Ferry that pulled 0.92% ER on 06-04 (data point: this run's NEW-today list). The org-vs-paid ER gap on BOJ is **>4×** — sharp signal for IE brand-seed strategy. |

### 3. Najma🎋 — Somali-British diaspora ambassador, high-ER organic, fresh-post surge

| Field | Value |
|---|---|
| Handle / display | Najma🎋 |
| Niche | Hobbyist organic reviewer; self-styled K-beauty/glass-skin ambassador for vidivici and skinseoul (brands outside our core split). Diaspora-explicit (`#somaliticktok` hashtag). |
| Followers | 16.9k |
| Today's surge video | 06-04 01:54 — "TikTok be picking the right sound 🤏🏽😍 #kbeauty #vidivicibeauty #skinseoulambassador #somaliticktok #glassskincare" — 7s — **734 views @ 12.26% ER, AD=false (organic)** |
| Past appearances | 06-06 and 06-07 viral_kbeauty_7d both captured the same 06-01 video at 462 views. Today's 06-04 video is a **fresh post that landed** — pushing her back into the pool with ~60% higher views and double-digit ER. This is a sustained, not flash, presence. |
| Voice/persona signature | Casual, sound-driven, identity-anchored (Somali British, glass-skin community). Short cuts (7s). Tone is community-celebratory not product-pushing. Ireland 18-34: high relevance for the **diaspora-explicit segment** (Somali/African heritage in Dublin, Cork). The persona-cards 8-deck does not currently carry a diaspora-identity-anchored archetype. |
| Demographic guess | Black British female, late teens-mid 20s, urban UK (likely London given community-tag density). |
| Brand alignment | vidivici, skinseoul — **neither in our core paid/organic brand split.** vidivici is a UK indie K-styled brand, skinseoul is a UK-K-retailer. Indicates a **3rd lane** of brand-creator alignment we haven't mapped: **retailer/indie-tagged micro-influencer ambassadorship**. This 3rd lane competes with VT/Anua/Mixsoon for organic-tier reach at much smaller follower base. |
| Persona mapping | **No clean fit to 8 personas.** Closest is Persona 5 (Cindy Lee identity-statement) but Najma's ER and content cadence pattern is community-celebratory not micro-moment-statement. Distinct enough to flag for the new-archetype watchlist as a **diaspora-ambassador / community-tagged organic micro-influencer** candidate. Note: she would be the **6th watchlist entry** since 06-08 (joining @olafflee, @mynameisrifah, @hanstluce, @jahanararahman_, @omotoyosi, @poppylivingstonex). |
| Verdict | **Keep watching** — Tier-1 candidate IF a sustained 7-14d organic cadence is confirmed (her 06-04 post landing with double-digit ER on a fresh post, plus the prior 06-01 video, is **2 K-skincare posts in 3 days at 12-15% ER on a 17k base** — that's the strongest organic-engagement micro-influencer profile this brief has surfaced UK-side). Strategic value: if IE has a Somali/African-heritage Dublin K-skincare creator at 5-20k followers, this is the persona shape to seed. |

---

## Tier-1 health (one line each)

- **James Welsh**: 🚩 **4th consecutive day absent from UK K-viral pool.** Last captured post is the 2026-06-02 Medicube AD (62k views, 1.3% ER — **vs 5.58% baseline = 4× ER collapse**) flagged 2 days ago. Brand-split breakage anomaly still unresolved.
- **Graces.faces_** (Grace Marsh): not in 06-10 viral pool, growthrank, risingstar, or deep_video_top10 UK surfaces. **4th day absent.** Cadence read pending — could be off-K, could be off-platform.
- **ZhilaBeauty**: not in 06-10 K-viral pool (06-09 growthrank had her +688 followers/24h gain, so she is posting — just not K). **2nd consecutive day of K-silence on a K-active week** — minor K-fatigue flag worth surfacing to sun-master-report.
- **Frishta** (frishtaxx): not in 06-10 viral pool or growthrank UK top-30. **4th day absent.** No movement signal either direction.
- **Cindy Lee** (ab61e): not in 06-10 viral pool or growthrank UK top-30. **4th day absent.** Smallest of Tier-1 by base; lowest-information signal of the five.

**Tier-1 summary**: 0 of 5 Tier-1 in today's UK K-viral pool — **lowest Tier-1 presence ratio in the rolling diff**. This is the strongest signal yet that the **UK K-viral pool composition has shifted to paid-push-dominant** (33 of 49 today's entries have AD=true, ~67%). Surfacing to sun-master-report.

---

## Departures (T+2 window, fresh-post drivers only)

- **@nattyhirut** (Natty Hirut, 361.6k): 06-08 surge was Mixsoon AD (an organic-tier brand on a paid-tier creator, flagged unusual at the time). Drop today consistent with one-off cross-brand AD activation, not a sustained Mixsoon stable. Mixsoon UK has not seeded a follow-up creator since.
- **@ellis_atlantis** (Ellis_Atlantis, 647k): 06-08 surge was a Yepoda AD (a German K-styled brand, outside our core split). Drop is almost certainly 7d roll-off (her 06-01 post is now ≥9 days old in the 06-10 window). No anomaly; window mechanics only.

---

## Carry-forward for tomorrow

- watch **@najmagh** (Najma🎋) — confirm sustained cadence: if a 3rd organic K-post lands within 7d at ≥8% ER, she becomes the **Persona 8.5 / 9** lead candidate (diaspora-ambassador community-tagged micro-influencer). Add to `new-archetype-watchlist.md` with `cluster tag = diaspora-community-ambassador`.
- watch **MASUK LIMITED** for cadence — if a 2nd organic ≥3% ER editorial lands in the next 7d, reinforces the BOJ-organic structural read.
- watch **Stephanie Vavron**'s Medicube post-views — if 06-04 video crosses 300k by next pool, she's tracking on Medicube's strongest hit pattern; if it stalls under 250k, that's a softening signal for Medicube paid-push effectiveness.
- watch **ZhilaBeauty** for K-content return — 2 days of non-K activity during peak K-discourse warrants a K-fatigue flag if it extends to 3rd day.
- 🚨 **Crawl-pipeline**: the 2026-06-11 morning crawl had not landed by 10:00 Dublin schedule (no `daily_data/2026-06-11/fastmoss_raw/` directory). Yesterday's report flagged 2-day regression; this is now potentially 3rd day partial. Confirm cron status with data-pipeline owner before tomorrow's run.

---

## Notes for sun-master-report

- ✅ **Crawl recovered for 2026-06-10**: full UK pool (50+30) returned, ending the 2-consecutive-day regression flagged in `daily_data/2026-06-10/creator-uk-female.md` (which mis-attributed: it was actually the 06-09 crawl that was IT-only; 06-10's crawl was clean but the routine ran before it landed). However the **2026-06-11 crawl had not landed at routine-run time** — partial-day-3 risk remains. Recommend pipeline owner verify cron timing vs Dublin 10:00 trigger.
- 🔄 **Frame correction on Stephanie Vavron**: she is **NOT a first-time-K-skincare** surge — she's rotational paid-tier (Medicube). Yesterday's broader interpretation in `daily_data/2026-06-09/creator-uk-female.md` (and similar) of "new entrants" should be filtered against the 28d/90d pool before being framed as discovery.
- 🔻 **BOJ organic-vs-paid ER gap = >4×** on today's data (MASUK LIMITED organic BOJ 4.02% ER vs Chloe Ferry BOJ AD 0.92% ER, same 7d window). This is **direct numerical reinforcement of the organic-first BOJ posture** for IE — supports the read already locked in `daily_data/2026-06-10/creator-uk-female.md` §sun-master-report notes.
- 🚩 **Tier-1 UK presence ratio = 0/5** in today's K-viral pool — **lowest of the rolling diff window**. Combined with the AD-share of today's pool at ~67%, the UK K-viral surface composition is shifting paid-push-dominant during this window. **For IE this means**: the organic VT/Anua/Mixsoon white-space is **widening** in UK as well, not just IE — the organic-first strategic posture gets stronger.
- 🆕 **Najma🎋 candidate** for `new-archetype-watchlist.md`: would be 6th entry, cluster `diaspora-community-ambassador` (new cluster — no prior entry). High organic ER (12.26%) + diaspora-identity-anchor + indie/retailer-tagged brand alignment. Distinct from `paid-tier-mid-convert` and from existing 8 cards. **First entry to its cluster**; watch for 2nd within rolling 14d.
- 🚩 **James Welsh × Medicube AD anomaly is now 4 days stale** without a clean follow-up post from him to disambiguate. Standing flag held.
