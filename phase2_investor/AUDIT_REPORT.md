# Phase 2 + 3 Investor Docs — Citation Audit Report

## Phase 3 audit pass (manual, May 5 2026)

Audit agent hit usage cap mid-run. Manual quick-audit performed on 6 Phase 3 files.

Files reviewed:
- REFILL_PROGRAM.md
- COLOR_PALETTE_OPTIONS.md
- PRICING_LADDER_V2.md
- BRAND_BOOK_OUTLINE.md
- WHOLESALE_LINE_SHEET_TEMPLATE.md
- RISK_REGISTER.md

### Findings

- **REFILL_PROGRAM.md**: Per-customer LTV comp lines (Method ~$30-50, Aesop $50-100, etc.) were directional estimates not in source data. Replaced with explicit `[unverified, modeled from publicly cited SKU prices]` framing + note that competitor LTV is not publicly disclosed.
- **COLOR_PALETTE_OPTIONS.md**: Hex codes already flagged `[unverified — design pass needed]`. No data claims.
- **PRICING_LADDER_V2.md**: Comp prices sourced inline from research/brand_teardowns.md. GESINE prices flagged `[unverified]`. Margin assumptions flagged `[unverified — needs unit econ pass]`.
- **BRAND_BOOK_OUTLINE.md**: Mostly structural. TAM/SAM/SOM cited from research. Type picks flagged as suggestions during design pass.
- **WHOLESALE_LINE_SHEET_TEMPLATE.md**: Net 30/60 + 5-8% co-op + 5-10% markdown all sourced inline to research/crate_barrel_intel.md. MOQs flagged `[unverified]`.
- **RISK_REGISTER.md**: Acquisition multiples + Touchland $880M sourced. DTC subscription churn 5-10% flagged `[unverified — needs source per category]`.

### Top 3 risks still in Phase 3 docs

1. Per-customer LTV projections on competitors (now flagged but should be killed entirely if pitched verbally — say "publicly disclosed customer LTV not available")
2. "Industry norm" claims in WHOLESALE_LINE_SHEET_TEMPLATE.md (Net 30/60 standard, 12-20 week glass lead times) — sourced to research file but research file itself uses general benchmarks, not single audited source
3. Subscription churn benchmark in RISK_REGISTER.md — flagged but Lee should pull a real DTC consumables churn benchmark before pitch (Recurly, Bolt, Zuora reports)

### What Lee needs to verify before any pitch using Phase 3 docs

- C&B signed agreement scope (Risk 1, 9 in RISK_REGISTER.md)
- Hazmat / EPA classification per concentrate (Risk 5)
- Any specific subscription churn benchmark cited
- Final price points (currently `[unverified]` across REFILL_PROGRAM, PRICING_LADDER_V2)
- Color palette pick (A/B/C from COLOR_PALETTE_OPTIONS.md)

---

# Phase 2 Investor Docs — Citation Audit Report

Audit date: May 3, 2026. Pass over 9 top-level files in `phase2_investor/` (research/ subfolder excluded as already sourced).

---

## Summary

- **Files audited:** 9 (BRAIN_DUMP, ICP_MODERN_PREMIUM, NAMING_PUNS, PARTNERSHIPS_MIXED, BRAND_WORLD_MOOD, CREATOR_GIFTING_PLAYBOOK, PRESS_KIT_FRAMEWORK, PLAN_50, PLAN_50_v2)
- **Discrete factual/numeric claims reviewed:** ~75
- **Already sourced or self-evident creative output:** ~25 (NAMING_PUNS, BRAND_WORLD_MOOD)
- **Sourced inline (research/ folder + web verification):** ~22
- **Flagged `[unverified]` inline:** ~20
- **Removed/replaced as fabricated or wrong:** ~8

---

## Per-file changes

### BRAIN_DUMP.md
- Method "$230M acquired by Ecover/SC Johnson route" — **REMOVED**, replaced with verified status: Method→Ecover 2012 [undisclosed], Ecover/Method→SC Johnson 2017 [undisclosed]. Method ~$112M rev at 2012 deal. Sourced to research/teardowns_and_exits_v2.md.
- Acquisition outliers list: corrected (Native is P&G not C&D), added years + prices for Toppik, TheraBreath, Hero Cosmetics, Seventh Gen, DSC. Flagged Snowberry/OPTE as unverified.

### ICP_MODERN_PREMIUM.md
- "$150K+" HHI claim sourced to Census/Statista 2023 distribution + research/market_sizing.md. Absolute count flagged unverified pending B19001 query.
- "Tier-1 metros" geography flagged: not an official Census term; per-metro $150K+ counts unverified.
- "$3.5K+/mo rent or $700K+ home" flagged unverified (illustrative threshold).
- "Will pay 3-5x for the better version" flagged unverified.
- Both persona income tables flagged as directional/composite.
- Goop core HHI claim sourced (CanvasBusinessModel) per research/icp_modern_premium.md.
- Anthropologie $150–200K mom HHI sourced (Brand Hopper).
- "Will pay $30-80 vs $4-12" flagged unverified.

### NAMING_PUNS.md
- No changes required. Creative output, no factual/numeric claims beyond the candidate count (60, verified).

### PARTNERSHIPS_MIXED.md
- Edition "22 properties" → corrected to ~15–20 open as of 2026, ~30 by 2027 (PR Newswire 2022). Exact count flagged.
- 1 Hotels "9+ properties" → corrected to ~21 as of 2026 (1hotels.com/our-locations).
- Four Seasons "130+" → corrected to 135 hotels + 61 residential, 47 countries (Four Seasons press 2025).
- Pantone "Cafe (Monaco, Hong Kong)" → Hong Kong **REMOVED** (no public source confirms HK location). Monaco verified (Interior Design, WWD).
- Pantone Universe coloring kits flagged unverified.
- MoMA buyer email + 50% wholesale cut + lead time flagged unverified.
- Time Best Innovations submission process flagged for re-verification (URL was time.com/inventions/submit; current URL/cycle dates need check).
- Art Basel "$25K+ activation" flagged unverified.
- NADA/Frieze "$5-15K range" flagged unverified.
- All hospitality + press lead times flagged as estimates.
- Creator tier list cleaned: removed @whoiselijah (misclassified — Stephen James is a male model), corrected @theskinnyconfidential (~287K vs personal @laurynbosstick 2M), removed @amandachantalbacon (~34K, not 500K-3M).

### BRAND_WORLD_MOOD.md
- No changes required. All claims are aesthetic recommendations or apocryphal brand lessons, no falsifiable numerics.

### CREATOR_GIFTING_PLAYBOOK.md
Major fixes — original draft had multiple wrong handles + inflated counts:
- @studiomcgee "4M" → ~3.4M (SpeakRJ).
- @amberinteriordesign "1.7M" → handle is actually @amberinteriors, ~2M.
- @jakearnoldstudio "800K" → handle is @jakearnold, ~395K.
- @leannefordinteriors "1.2M" → ~578K.
- @brigetteromanek "200K" → ~204K (verified).
- @valeria.lipovetsky "2.6M" → handle is @valerialipovetsky (no dot), ~2.5–3M.
- @whoiselijah "600K Gen Z home aesthete" → **REMOVED**. Handle is Stephen James (male model), ~2M, but misclassified for this list.
- @vanesamaro91 "TikTok 7M" → ~5.6M.
- @sortedhome "1.2M" — could not verify as real account; **REMOVED**.
- @cleanwithme "800K" — `#cleanwithme` is a hashtag, not an account; **REMOVED**.
- @neat.method "1M" → handle is @neatmethod, ~846K.
- @taylorlashae "850K" → ~760–910K (verified, range across sources).
- @blaire_eadie "1.2M" → handle is @blaireadiebee, ~2M.
- @victorialyn "700K Home + ritual content" → ~1M but profile is "Beauty with Intention," flagged for re-evaluation.
- "Drunk Elephant did $100M run-rate by year 5 entirely on word-of-mouth + Sephora" → corrected: ~$100M by year 7 (2019), Sephora launch Jan 2015 was the flywheel. Sourced.
- "Hero Cosmetics did $115M run-rate in 3 years on creator-led TikTok" → corrected: $115M trailing-12-month at 2022 acquisition (5 years post-founding 2017), scaled primarily via Amazon + Target, not creator-only. Sourced.
- "Bala did $50M+ revenue on creator gifting alone" → flagged: ~$29M (2025), $50M figure is single-source 2023, omnichannel not gifting-only. Sourced.

### PRESS_KIT_FRAMEWORK.md
- Tier-1 outlet contact list: every "editor" entry flagged `[verify masthead]` since none had named editor confirmed. Joanna Goddard at Cup of Jo retained (founder, public).
- No hard industry stats made in this doc — mostly procedural template.

### PLAN_50.md
- No changes — task list, claims framed as research targets ("Research X").

### PLAN_50_v2.md
- Header note added: Crate & Barrel locked, $400K angel, Caraway design firm, Q4 2026 launch all flagged unverified pending Lee confirmation.
- Header note added: inline numbers cited inside steps (Touchland $880M, $258B→$312B gifting, 94% Clorox stat, 8,000+ creators) explicitly framed as research targets to verify, not asserted facts.

---

## Top 10 risk items still in the docs

1. **"Tier-1 metros" $150K+ HH count is implied but not pulled.** ICP doc references 9 specific MSAs without per-MSA Census B19001 data. Anyone reading "Modern Premium ICP in NYC, LA, SF…" will assume there's a number behind it; there isn't yet. Pull B19001 by MSA before any deck slide.
2. **"31.8M households" derived figure.** Math is right (23.9% × 132.9M) but neither the 2023 percentage nor the 2024 absolute count is from a single primary Census print. Confirm before using as a TAM anchor.
3. **Edition Hotels exact current property count.** Public sources show ~15–20 open with 30 targeted by 2027, but a hard 2026 number isn't published. If used in deck, say "~20" not a precise integer.
4. **Bala revenue.** Three different journalist-reported figures exist ($29M/$50M/$64M lifetime). Drop revenue claim from Bala framing or cite range with explicit "journalist-reported, not audited" caveat.
5. **Hero Cosmetics framing as "creator-led TikTok."** Industry coverage paints Hero as Amazon-native + Target retail. The TikTok framing was overstated — adjust before pitching.
6. **MoMA Design Store buyer email + ~50% wholesale cut.** Both flagged. Standard specialty-retail benchmark, but MoMA-specific terms not in any public source. Confirm before pitching wholesale.
7. **"Will pay 3-5x for the better version" + "$30-80 vs $4-12" willingness-to-pay claims.** Both flagged unverified. These are foundational pricing thesis lines — not safe to put on a deck slide without consumer research.
8. **Pantone "Color of the Year drop" 12-month lead time.** Flagged unverified. Lead times for Pantone collabs are not public.
9. **Time Best Innovations 2026 submission window.** URL and cycle dates need re-verification.
10. **Press kit Tier-1 outlet editor names.** All flagged unverified — every name needs masthead confirmation before pitching.

---

## What Lee should still verify manually

1. **Crate & Barrel "locked 2027" claim** — confirm signed agreement vs verbal-only. Janet Hayes / Pat Eckerstrom / Lee buyer relationship status.
2. **$400K angel close, Caraway design firm partnership scope (equity vs vendor), Q4 2026 D2C launch date** — all assumed in PLAN_50_v2 header.
3. **"8,000+ creators seed list"** referenced in deck audit step — confirm the source / list ID before claiming in deck.
4. **EWG Verified certification status** — claim is "active" in PLAN_50_v2 step 46 but cert paperwork still needed.
5. **Smoked Sage hex / colorway specs** — referenced as exclusive C&B colorway, no spec on file.
6. **Touchland $880M Church & Dwight 2025 deal** — referenced in PLAN_50_v2 as comp; not in research/teardowns_and_exits_v2.md. Verify via primary source before citing.
7. **Clorox 2026 Trend Report "94% link self-image to home care"** — find the original report. If can't find, pull from deck.
8. **Coresight or ASI source for "$258B (2022) → $312B (2025)" gifting market** — find or replace.
9. **Caraway 2025 revenue / DTC vs retail mix, funding rounds** — flagged in PLAN_50_v2 steps 4–5, no public source assembled yet.
10. **Per-creator audience verification on the day of send** — follower counts in CREATOR_GIFTING_PLAYBOOK are May 2026 snapshots; re-verify each handle before kits ship.

---

## Files changed

- BRAIN_DUMP.md
- ICP_MODERN_PREMIUM.md
- PARTNERSHIPS_MIXED.md
- CREATOR_GIFTING_PLAYBOOK.md
- PRESS_KIT_FRAMEWORK.md
- PLAN_50_v2.md

Files left untouched (no fabrication risk found): NAMING_PUNS.md, BRAND_WORLD_MOOD.md, PLAN_50.md.
