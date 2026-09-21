# 00 — Brief, Assumptions & Scope

## The brief as given

> Build a 2-week (15 post) content calendar for our Instagram launch — mix of product posts,
> behind-the-scenes, festive/occasion content, and UGC-style posts. Include 3 sample captions
> with hashtags, a quick competitor analysis (3 jewelry brands), and a posting strategy note.

Brand tone specified: **elegant, trustworthy, gifting-focused.**

## What the brief did not specify

The brief gives a tone but no price tier, material, audience, or brand name. Those four
variables change almost every downstream decision — a ₹1,899 silver pendant and a ₹1.4L
diamond solitaire need opposite content strategies. Rather than write something vague enough
to fit both (and therefore fit neither), I picked a position, committed to it, and documented
it here so it can be swapped.

## Working assumptions

| Variable | Assumption | Why |
|---|---|---|
| **Brand name** | `{{BRAND}}` placeholder | Not my brand to name. Every caption uses the token — find-and-replace once and the whole repo is live. |
| **Category** | Demi-fine: 925 sterling silver + 18k gold-plated | The only tier where an Instagram-first launch can actually close sales in-feed. |
| **Price band** | ₹1,000 – ₹5,000, hero SKU at ₹1,899 | Below the ~₹3k "no-spouse-approval-needed" threshold. Impulse- and gift-viable. |
| **Audience** | Women 22–35, Indian metros + tier-1, salaried/early-career | Self-purchase and gifting in roughly equal measure. |
| **Secondary audience** | Men 25–35 buying gifts | Small in follower count, disproportionate in Oct–Nov revenue. |
| **Launch window** | Mon 5 Oct – Sun 18 Oct 2026 | See below. |
| **Channel** | Instagram only (feed + Reels + Stories) | Per brief. Strategy note flags where WhatsApp/email should pick up. |
| **Team** | 1 person, phone camera, no studio budget | Every post in the calendar is shootable under that constraint. |

### Swapping the assumptions

If the real brand is gold or bridal, three things change and the rest holds:
1. **Competitor set** → Tanishq, CaratLane, Bluestone (see `04` for the substitution note).
2. **Post goal** → discovery/credibility, not in-feed conversion. CTAs move from "link in bio"
   to "book a video call / visit store".
3. **Post 04** (the price-breakdown post) is cut — margin transparency reads as confident at
   ₹1,899 and as defensive at ₹80,000.

The calendar structure, pillar ratio, posting cadence and UGC engine are tier-independent.

## Why the launch window is 5–18 October 2026

This is the single most load-bearing decision in the whole submission, so it gets its own note.

The Indian jewellery year peaks in a ~5-week corridor:

| Date (2026) | Occasion | Relevance |
|---|---|---|
| Sun 11 Oct | Ghatasthapana — Sharad Navratri Day 1 | 9 nights of garba, dressing up, daily outfit posts |
| Tue 20 Oct | Vijayadashami / Dussehra | Auspicious-purchase day |
| Thu 29 Oct | Karwa Chauth | Gifting spike, husband-buys-for-wife |
| Fri 6 Nov | **Dhanteras** | The single biggest jewellery-buying day in India |
| Sun 8 Nov | Diwali | Gifting peak |

A launch is worth the least on day one and the most about six weeks in, once the audience is
warm, the retargeting pool is seeded, and there is real UGC to reshare. So the calendar
**deliberately ends on 18 October — nineteen days before Dhanteras.**

The two weeks in this document are not the payoff. They are the run-up that makes the payoff
possible. By 18 Oct the brand should have a warm audience, a seeded pixel, a stack of customer
photos, and a known-winning creative format — and then it spends into Dhanteras.

Launching *on* Dhanteras with a cold account would mean paying full price for traffic that has
never heard of you, in the most expensive ad auction of the year.

> **Note on festival dates:** These follow the lunisolar calendar and can shift by a day by
> region and panchang. Confirm against the final panchang before locking paid spend.

## Deliverables map

| Brief asks for | Where it is |
|---|---|
| 2-week, 15-post content calendar | [`02-content-calendar.md`](02-content-calendar.md) · [`../data/content-calendar.csv`](../data/content-calendar.csv) |
| 3 sample captions with hashtags | [`03-sample-captions.md`](03-sample-captions.md) |
| Competitor analysis (3 brands) | [`04-competitor-analysis.md`](04-competitor-analysis.md) |
| Posting strategy note | [`05-posting-strategy.md`](05-posting-strategy.md) |
| *(added)* Buyer-psychology rationale | [`01-buyer-psychology.md`](01-buyer-psychology.md) |
| *(added)* Production shot list | [`../assets/shot-list.md`](../assets/shot-list.md) |

The last two are not in the brief. I added them because "understanding of jewelry-buyer
psychology" is an assessment criterion with no named deliverable attached to it, and because a
calendar a solo founder cannot physically shoot is not a plan.
