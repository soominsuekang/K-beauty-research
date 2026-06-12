# Creator-UK-Female — Surge Edition — 2026-06-12

## DATA NOTICE — CRAWL PIPELINE STALE FOR 3RD CONSECUTIVE DAY

There is **no `fastmoss_raw/` for 2026-06-12** (today) or **2026-06-11** (yesterday) in the repo at 10:00 Dublin run time. The most recent UK-clean crawl is **2026-06-10**. The 2026-06-09 crawl returned IT-only on the K-viral inputs (see `daily_data/2026-06-10/creator-uk-female.md`). This is **Day 3** of the regression flagged in the 2026-06-10 and 2026-06-11 reports — no longer a transient.

The 2026-06-11 report (`daily_data/2026-06-11/creator-uk-female.md`) already ran the canonical 06-10 vs 06-08 viral-pool diff and deep-dived **Stephanie Vavron**, **MASUK LIMITED**, and **Najma🎋**. Re-running the same diff today would duplicate yesterday's output line-for-line. Instead this run:

1. Runs a **strict-fresh diff** (06-10 vs **06-06 ∪ 06-07 ∪ 06-08**) — surfaces only creators with zero prior K-viral-pool footprint in the last 4 clean windows.
2. Mines the **2026-06-10 UK growthrank + risingstar** surfaces, which were **not systematically diffed** by the 2026-06-11 report (it focused on viral-pool only). These are the only 06-10 surfaces still untapped.
3. Deep-dives **2 creators not covered yesterday** (Aimée Isabella, Sara Afroug) + 1 unverified watchlist add (jude.anderson).
4. Holds the Day-3 crawl regression as the dominant escalation to `sun-master-report`.

## Today's diff at a glance

- Yesterday viral pool (last clean = **06-08**): 50 unique creators
- Today viral pool (last clean = **06-10**): 49 unique creators
- NEW today vs 06-08 only: **34** (already mined in `daily_data/2026-06-11/creator-uk-female.md`)
- **NEW under strict-fresh filter (06-10 minus 06-06 ∪ 06-07 ∪ 06-08): 30** — 4 of yesterday's 34 turn out to have prior-window footprint (Najma🎋, nada | beauty, YSF Trends in 06-07; one more dedup)
- DROPPED (06-10 vs 06-08): 36
- **Date source used (not today)**: TODAY = 2026-06-10 fastmoss_raw; YESTERDAY = 2026-06-08 fastmoss_raw. **3rd day running on stale T+2 input.**

### Untapped 06-10 surface (new this run): UK growthrank + risingstar diff vs (06-08 ∪ 06-09)

**Growthrank UK NEW (9 entries):**

| Handle | Display | Followers | +24h | Growth% | Videos |
|---|---|---|---|---|---|
| @yazhadfield | yazhadfield | 944.6k | +1.6k | 0.17% | 7.8k |
| @astarbarbers | A Star Barbers | 4.3m | +1.5k | 0.04% | 399 |
| @prosper.fitness | Prosper Fitness | 901.6k | +1.3k | 0.15% | 420 |
| @lucyfice | Baddie Luce | 583.0k | +1.2k | 0.22% | 770 |
| **@jude.anderson** | jude.anderson | **230.3k** | **+938** | **0.41%** ← highest rate | 1.4k |
| @ellemoonz | ElleMoonz🤍☁️🧸 | 753.8k | +785 | 0.10% | 1.0k |
| @chloeferryofficial | Chloe Ferry | 1.2m | +754 | 0.06% | 1.4k |
| @vladimirflitar | Vladimir Flitar | 577.0k | +662 | 0.11% | 5.3k |
| **@saread7** | Sara Afroug 🇲🇦🇬🇧✅ | **156.1k** | +580 | **0.37%** ← 2nd-highest rate, diaspora-flag | 609 |

**Risingstar UK NEW (2 entries):**

| Handle | Display | Female% | Age | Viral idx | Avg views | Categories |
|---|---|---|---|---|---|---|
| @thesavvyscent | thesavvyscent | n/a | n/a | 74 | 17.5k (vs ch-avg 2.9k = **6× channel surge**) | Makeup Sets / Blush / Primers |
| @everdaywithj | Everyday With J 🚶‍♂️ | n/a | n/a | 73 | 28.0k (vs ch-avg 12.3k = 2.3× surge) | Home Games / Men's Perfume / Outdoor Chairs |

**Cross-check vs all prior captured K-pools (06-06 through 06-10, 7d+28d+90d)**: of the 9 growthrank UK entries, **only @lucyfice has K-skincare history** — May-13 Mediheal AD, 143.7k views. The other 8 are unconfirmed for K-skincare crossover. Same caveat as the 06-10 report applies: growthrank is UK-beauty-broad, not K-skincare-specific. FastMoss creator-detail pages 403 to WebFetch — cannot self-verify in-run.

---

## Surge creators — deep dive

### 1. Aimée Isabella — first surface for **Narae UK** brand, organic-tier paid micro-seed

| Field | Value |
|---|---|
| Handle / display | Aimée Isabella |
| Niche | Glass-skin / overnight-mask micro-creator. Persona reads aesthetician-adjacent enthusiast, not derm. |
| Followers / avg views / ER | 34.9k followers; **two captured K-posts both >4% ER** (4.1% on 998 views, 4.48% on 870 views). Tight engagement, small reach base. |
| Today's surge video | 06-05 22:08 — "Weekly ritual for glass skin, one of my favourite overnight masks @Narae UK #overnightmask #glassskincare" — **9s, 998 views @ 4.1% ER, AD=true.** Companion post 06-06 13:15 — collagen face mask @Narae UK, 7s, 870 views @ 4.48% ER. **Two AD posts in 24h for the same brand** = a discrete brand-seeded campaign, not a one-off. |
| Past content pattern | Zero K-skincare appearances in any prior captured viral pool (06-06/07/08 7d+28d+90d). She is a **first-time entrant** to the K-viral surface. |
| Voice/persona signature | Aspirational, "ritual" framing, brand-tagged in caption, glass-skin lexicon. Short cuts (7-9s). Polished. Not regulator-style; closer to lifestyle-aesthetic-led. Ireland 18-34: moderate-to-high trust for the aesthetic-led 18-24 segment (glass-skin/ritual language reads younger). |
| Demographic guess | White European/British female, mid-20s, polished urban presentation. |
| Brand alignment | **Narae UK** — Narae has zero prior appearances in our 90d dataset (verified: 2 mentions across all captured pools, both from Aimée). This makes Aimée the entire visible surface for Narae's UK TikTok push so far. Narae sits **outside** our existing brand-creator split (VT/Anua/Mixsoon=organic; medicube/Dr.Melaxin=paid) — it's an **unmapped brand**. ER pattern (4%+ on paid posts) suggests Narae is seeding micro-influencers and getting organic-tier engagement back, which would place them on the organic-friendly tier if the pattern holds across a 2nd creator. |
| Persona mapping | No clean fit to the 8 personas (per the 2026-06-06 cards referenced repeatedly in prior runs — note: `findings/2026-06-06/persona-cards.md` is not present in this repo; the canonical reference appears to live in another artifact). Closest is the aesthetic-led micro segment (similar shape to Aimée's lane). Flag for new-archetype watchlist as a **brand-seeded micro-aesthete**. |
| Verdict | **Keep watching — brand-watch primary, creator-watch secondary.** Aimée herself is at micro scale (35k) so creator-tier impact is bounded; but she is the only signal we have on **Narae UK's TikTok entry pattern**, and Narae is a brand that may shift the brand-creator split if it lands organic-paid (i.e., paid micro-seeds producing organic-tier ER). Watch for: 2nd Narae UK creator landing in next clean crawl. If a 2nd creator surfaces with 3%+ ER on a Narae AD, the brand-creator split needs a **new "organic-friendly paid" tier**, and Narae becomes a credible IE comp for VT/Anua/Mixsoon-tier creator strategy. |

### 2. Sara Afroug @saread7 — diaspora-ambassador candidate #2 (Moroccan-British), K-context unverified

| Field | Value |
|---|---|
| Handle / display | @saread7 (Sara Afroug 🇲🇦🇬🇧✅) |
| Niche | Unknown from data alone — fastmoss surfaces her in **06-10 growthrank UK beauty** (#27 by 24h gain, top-3 by growth-rate at 0.37%). The 🇲🇦🇬🇧 flag-set in her display name is a **Moroccan-British diaspora self-identification**, structurally identical to the Najma🎋 #somaliticktok pattern flagged in the 2026-06-11 surge file as the **diaspora-ambassador / community-tagged organic micro-influencer** archetype. |
| Followers / avg views / ER | 156.1k followers. Adding **+580 followers in 24h on a 156k base = 0.37% daily growth rate** — that's a high organic-velocity signal at her base level (4× the typical 0.10% growthrank entrant rate). 609 videos total = active poster, ~1.5/day if linear. |
| Today's surge "video" | **No captured viral video in 06-10 K-pool.** This is a growth-rate signal only — she is gaining followers fast but has not landed a K-video in the captured viral surface. **K-skincare relevance is unverified.** |
| Past content pattern | **Zero K-pool appearances** across 06-06/07/08/10 (7d/28d/90d). First-time on any FastMoss UK creator surface we capture. |
| Voice/persona signature | Unknown — no caption data in growthrank payload, FastMoss profile detail blocked. Diaspora-flag in display name is the only persona-signal in-data. |
| Demographic guess | Moroccan-British female (flag pair self-declared), follower base + beauty category suggests 18-34. |
| Brand alignment | Unknown — needs verification on next clean crawl or via TikTok profile read. |
| Persona mapping | **Would be 2nd entry in the diaspora-community-ambassador cluster** the 06-11 file proposed for Najma🎋. If she lands a K-post in the next 7d, that cluster becomes a confirmed pattern (2 entries within 14d) rather than a one-off. For Ireland: the diaspora-ambassador shape would map to Polish-Irish, Brazilian-Irish, Nigerian-Irish 18-34 segments in Dublin/Cork — direct architectural transferability. |
| Verdict | **High-priority watch.** This is the strongest leading-indicator signal of the day: if the same archetype shape (Najma's Somali-British + Sara's Moroccan-British) shows up twice on the UK surface within a 4-day window, the diaspora-ambassador cluster is **the most replicable persona for IE white-space seeding** the brief has surfaced. Critical action: verify K-skincare alignment in next clean crawl. Tier-1-candidate-conditional-on-K-content. |

### 3. @jude.anderson — fastest-growth growthrank entry, K-context unverified

| Field | Value |
|---|---|
| Handle / display | @jude.anderson (jude.anderson) |
| Niche | Unknown — fastmoss surfaces her at **06-10 growthrank UK beauty #5** with the **highest 24h growth-rate of any new entrant (0.41%)**. 1.4k videos = very active. |
| Followers / avg views / ER | 230.3k followers, +938 in 24h. 0.41% daily growth-rate is the strongest of any UK beauty grower in today's untapped 06-10 surface. |
| Today's video | No captured K-viral entry. Growth-rate signal only. |
| Past content pattern | Zero K-pool appearances in any captured window. |
| Brand alignment | Unverified. |
| Persona mapping | Insufficient data. |
| Verdict | **Keep watching** — flag purely as the fastest-rising NEW UK beauty creator on the latest clean crawl that we have not seen before in K-context. Not promoted to deep-dive priority because K-relevance is unconfirmed; one tier below Sara on watchlist priority. If she lands K-content in next 7d, she's a Tier-1 candidate by audience-scale (230k organic-growing); if she remains non-K, she's a noise hit on the growthrank surface. |

---

## Tier-1 health (one line each)

- **James Welsh**: 🚩 **5th consecutive day absent from UK K-viral pool.** Last captured post still the 2026-06-02 Medicube AD (62k views, **1.3% ER vs 5.58% baseline = 4× ER collapse**). Anomaly unresolved; no fresh data to disambiguate.
- **Graces.faces_** (Grace Marsh): not in 06-10 viral pool, 06-10 growthrank UK top-30, or 06-10 risingstar UK top-30. **5th day absent.** Cadence read still pending crawl recovery.
- **ZhilaBeauty**: not in 06-10 K-viral pool. **Also NOT in 06-10 growthrank UK top-30 today** — first day she's missing from both K-viral AND growthrank since the 2026-06-09 +688/24h read. 3 consecutive days of K-silence on a K-active week now plausibly the start of a behavioural shift, not just window-coverage artifact. Flag holds.
- **Frishta** (frishtaxx): not in 06-10 viral pool, growthrank, or risingstar UK. **5th day absent.**
- **Cindy Lee** (ab61e): not in 06-10 viral pool, growthrank, or risingstar UK. **5th day absent.** Lowest base, lowest signal weight; no anomaly flag.

**Tier-1 summary**: 0 of 5 Tier-1 on any 06-10 UK FastMoss surface (viral + growthrank + risingstar). Yesterday's "0 of 5 in viral pool" extends to "0 of 5 in viral + growthrank + risingstar" today — **strongest absence signal of the rolling diff**. Combined with 06-10 viral pool composition at 67% AD, the read is consistent: the captured UK K-surface in this window is **paid-push-dominant**, organic Tier-1s are off the surface.

---

## Departures (06-10 vs 06-08, fresh-post drivers only — yesterday's drop list re-checked for sustained-vs-window read)

- **@nattyhirut** (Natty Hirut, 361.6k, Mixsoon AD 06-08): still absent on 06-10. **No 2nd Mixsoon post from her or any other captured creator in the 06-10 pool.** Mixsoon UK has not seeded a follow-up creator on the surface for 4 days. Reads as one-off cross-brand activation, not a building stable. Mixsoon-organic-tier hypothesis still intact (small-base creators carry it; she was the only paid-tier hit and it didn't extend).
- **@trenzy** (8.6k followers, Korean-serum-darkspots series, 20.7k views 06-08): drop is series-cadence — his K-clip was published 06-01, naturally aged out of 7d window by 06-10. Not a behavioural signal. (Standard 7d roll-off.)

---

## Carry-forward for tomorrow

- watch **@saread7** (Sara Afroug 🇲🇦🇬🇧) — **highest-priority new lead.** Confirm K-skincare alignment on next clean crawl. If she lands a K-post within 14d, the diaspora-community-ambassador cluster (Najma + Sara) becomes a confirmed 2-entry pattern, opening the most replicable IE-transfer persona surfaced to date.
- watch **Aimée Isabella + Narae UK** — both for cadence (3rd Narae post within 7d?) AND brand-spread (2nd Narae UK creator landing?). If the brand seeds a 2nd creator at ≥3% ER, brand-creator split needs a new "organic-friendly paid" tier and Narae enters the IE brand watch.
- watch **@jude.anderson** — flag K-content emergence; demote from watch if no K-context surfaces in 7d.
- watch **@najmagh** (carry-forward from 06-11) — original brief: 3rd organic K-post within 7d at ≥8% ER. Cannot test today; rolls forward.
- watch **MASUK LIMITED** (carry-forward from 06-11) — 2nd organic ≥3% ER BOJ editorial. Cannot test today; rolls forward.
- watch **ZhilaBeauty** — 3rd day of K-silence + now off growthrank too. If 4th day extends, escalate from "K-fatigue" flag to "Tier-1 K-pivot under review" in sun-master-report.
- 🚨 **PIPELINE: 06-11 morning crawl did not land. 06-12 morning crawl did not land at 10:00 Dublin.** This is **3 consecutive days** without a fresh crawl input to this report. Escalating today as a structural blocker, not a transient.

---

## Notes for sun-master-report

- 🚨 **Crawl pipeline — Day 3 escalation.** Two consecutive scheduled crawls (06-11 morning, 06-12 morning) have not landed. The 06-09 crawl regressed to IT-only. The 06-10 crawl was clean but is now T+2 stale. **This is the most direct blocker on the brief's deliverable**: without fresh data, the surge-detection function rolls increasingly stale, Tier-1 reads become "absence-by-data-gap" rather than "absence-by-behaviour", and brand-watch signals (Narae UK, Mixsoon follow-ups, BOJ paid-spread) cannot be validated. Pipeline owner to confirm cron status before tomorrow's run; otherwise the brief should escalate to engineering ownership.
- 🆕 **Diaspora-community-ambassador cluster — 2nd candidate surfaces (Sara Afroug 🇲🇦🇬🇧)** within 4 days of the 1st (Najma🎋 🇸🇴). Two entries in 4 days on the same archetype shape (community/heritage-tagged display name, 16-156k follower band, organic-fast growth) is the strongest 2-entry pattern of the rolling diff. If verified K-aligned, this becomes the most replicable persona for IE white-space seeding — direct transfer maps to Polish-Irish / Brazilian-Irish / Nigerian-Irish 18-34 Dublin segments. **Action**: promote cluster from "watchlist" to "active hypothesis" in next master sweep; commission targeted creator search.
- 🆕 **Narae UK — unmapped brand entering the K-viral surface via micro-seeded paid posts at organic-tier ER (4%+).** Brand has zero prior appearances in 90d capture; surfaces today via 2 paid posts from Aimée Isabella (34.9k) in 24h. Pattern: if a 2nd creator lands at similar ER, Narae UK belongs in an "organic-friendly paid" tier that doesn't currently exist in the brand-creator split. Watch — could be a 3rd lane in the organic/paid binary.
- 🚩 **Tier-1 UK presence ratio = 0/5 on ALL 06-10 surfaces** (viral + growthrank + risingstar). Yesterday's "0/5 in viral pool" worsens today to "0/5 anywhere captured". This extends the paid-push-dominant read from yesterday and adds **ZhilaBeauty newly off growthrank** as a fresh data point — her 06-09 +688/24h gain has not recurred. If the 06-12 crawl recovers and Zhila is still off all surfaces, the "Zhila active just not on K" interpretation from 06-10 needs revision toward "Zhila slowing across surfaces". Holds for now as flag, not conclusion.
- 🔻 **Mixsoon non-spread**: Natty Hirut's 06-08 Mixsoon AD has produced zero follow-up Mixsoon creator entries in 4 days. Reinforces the read that Mixsoon-UK is carried by small-base organic creators, not paid stables — consistent with organic-tier brand-creator split and supports the IE organic-first strategic posture.
- 🚩 **James Welsh × Medicube AD anomaly is now 5 days stale** without a clean follow-up to disambiguate. Standing flag held; cannot be cleared until next clean UK crawl.

