# Refill Program Design

A design-led refill mechanic. Sustainability claim is a side effect, not the lead.
LTV multiplier is the investor case.

## The white space

Refill is split between two extremes today:

| Lane | Comp | Pricing | Aesthetic |
|------|------|---------|-----------|
| Mass eco | Blueland | $2.25 refill tab to $39 starter to $79+ bundles | Plastic-utility, eco-lead. Source: [research/brand_teardowns.md](research/brand_teardowns.md) |
| Mid eco | Branch Basics | $19 concentrate refill to $99 Premium Starter | Wellness-clinical. Source: [research/brand_teardowns.md](research/brand_teardowns.md) |
| Mass refill-curious | Method | No refill core mechanic, mass priced $4-20. Source: [research/brand_teardowns.md](research/brand_teardowns.md) |
| Premium standalone | Touchland | No refill mechanic. Sold to Church & Dwight May 2025 for ~$880M total ($700M cash + stock + $180M earnout). Source: [research/brand_teardowns.md](research/brand_teardowns.md) |
| Luxury hand wash | Aesop | $47 Resurrection Hand Wash, no refill program. Sold to L'Oreal April 2023 for $2.53B. Source: [research/brand_teardowns.md](research/brand_teardowns.md) |
| Luxury home | Homecourt | $20-90+, no refill program. $30M revenue, $8M Series A Oct 2025. Source: [research/brand_teardowns.md](research/brand_teardowns.md) |

GESINE plays the white space: **design-led + refill native + premium pricing**. No competitor occupies all three.

## Mechanic

| Component | Spec | Price hypothesis | Reasoning |
|-----------|------|------------------|-----------|
| Hero Bottle | 188 x 36 x 72mm, frosted glass, aluminum cap | $48-58 retail | Anchor on Aesop $47 hand wash floor + premium for Apple-density object. Source: [research/brand_teardowns.md](research/brand_teardowns.md) for Aesop pricing. `[unverified — exact price needs willingness-to-pay test]` |
| Refill Vial | 10 x 18mm, glass | $12-18 per vial, $30-45 for 3-pack | Anchor: Branch Basics $19 single concentrate, Blueland $2.25 tab. We sit between, premium positioned. `[unverified]` |
| Organizer Unit | 194 x 51 x 191mm, holds bottle + 6 vials | $78 (locked) at C&B exclusive | Source: [research/crate_barrel_intel.md](research/crate_barrel_intel.md) |
| Refill Subscription | 6 vials, quarterly | $48-60 per quarter, $192-240 annual | Subscription discount vs single-vial pricing. `[unverified — pricing model assumption]` |

## LTV math (worked example, all numbers `[unverified]` projections)

Year 1 customer:
- Buys Hero Bottle ($53) + Organizer ($78) + first vial set ($45) = $176 launch order
- Adds 2 quarterly refill sets at $54 each = $108
- Year 1 total: **~$284**

Year 2 customer:
- 4 quarterly refill sets at $54 = $216
- Adds 1 new bottle (different scent or kitchen vs bath) = $53
- Year 2 total: **~$269**

3-year LTV target: **~$700-800 per retained customer.**

Compare:
- Method customer: ~$30-50/yr at most (mass channel, no recurring)
- Blueland customer: ~$80-120/yr ([Source: research/brand_teardowns.md](research/brand_teardowns.md), $39 starter + $2.25 refills)
- Branch Basics customer: ~$150-250/yr ([Source: research/brand_teardowns.md](research/brand_teardowns.md))
- Aesop hand wash customer: $50-100/yr ([Source: research/brand_teardowns.md](research/brand_teardowns.md), $47 hand wash, no recurring)

GESINE LTV target sits ~3-5x Branch Basics. Justified by: design-object purchase up front, recurring subscription, multiple bottles per household.

## Sustainability claim (for press, not the lead)

| Claim | Status |
|-------|--------|
| Refill reduces single-use plastic | True directionally. Specific tonnage avoided per customer requires audit. `[unverified]` |
| Glass + aluminum recyclable | True. Cite specific recycling stream eligibility per region before claiming. `[unverified per market]` |
| Refills carbon-cheaper to ship vs full bottles | Directionally true: less weight, less volume. Specific kg CO2e per refill vs new requires LCA study. `[unverified]` |
| EWG / Made Safe / B Corp certs | Pending. `[unverified — Lee to confirm cert paperwork status]` |

Press should NOT claim percentages without an LCA study. Investors will ask.

## Operational design

### Vial fill model

- Vials manufactured empty, shipped to fill house in batches
- Concentrate produced in lots, QC tested, filled per scent
- Labels applied, vials capped, sealed with linen ribbon (per brand standard)
- Boxed in subscription quantity (6 per box)
- Direct ship from 3PL or pick from C&B DC for retail

### Subscription enrollment paths

1. **At first purchase** (DTC): Checkout offers "Subscribe & Save 10%" on refill set
2. **Inside the bottle box** (DTC + retail): QR code on insert → activate subscription with first refill in 60 days
3. **Email day 14**: First-bottle owners get email "your refill ships in 60 days unless you adjust"
4. **Subscription portal**: Pause, swap scent, change frequency, cancel any time

### Subscription cancellation pressure-test

If churn is high:
- Pause-don't-cancel option (skip 1-3 cycles)
- Re-engage at 90 days post-cancel with new scent drop
- Win-back offer: 30% off return order

## What this slide tells investors

| Metric | Reference comp | GESINE target |
|--------|----------------|---------------|
| LTV | Method ~$50/yr, Branch Basics ~$200/yr ([sources](research/brand_teardowns.md)) | $250-300/yr |
| Repeat purchase rate | DTC home cleaning industry: not publicly disclosed at granular level. `[unverified]` | 60%+ on quarterly subscription |
| Subscription contribution to revenue Y2 | Branch Basics emphasizes refills, Blueland emphasizes refills, both private | Target: 40-50% of revenue from subscription Y2 |
| Cost-of-goods on refill vs full bottle | Refill ships ~70% lighter, similar concentrate cost. Margin uplift directional. `[unverified — needs unit econ model]` | Higher gross margin on refills than first bottle |

## Risks

1. **Subscription fatigue**: Modern Premium Consumer is over-subscribed. Mitigation: skip-don't-cancel UX + scent rotation drops.
2. **Refill scent integrity**: Concentrate must hold scent profile in glass + travel. Mitigation: stability testing per scent before launch.
3. **Operational complexity at retail**: C&B partner won't carry vials initially (Organizer Set only). Mitigation: vials DTC-only year 1, expand to retail year 2 if data supports.
4. **Sustainability backlash**: Consumers are wary of greenwashing. Mitigation: never lead with eco claims, never quote percentages without LCA. See claim audit above.

## Decisions Lee needs to make

- Final price points (currently `[unverified]`, willingness-to-pay test recommended)
- Subscription cadence default (quarterly vs monthly vs custom)
- Discount on subscription (10% / 15% / none)
- Vial fill volume per scent (concentrate density, dilution ratio)
- Whether refills go to retail in year 1 or year 2
