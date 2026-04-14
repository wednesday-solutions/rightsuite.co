---
layout: default
title: How to Run a Price Sensitivity Analysis for Your SaaS
parent: Guides
description: "Price sensitivity analysis tells you exactly where your price sits relative to your segment's willingness to pay - before you set a number and defend it without data."
faq:
  - q: "What is price sensitivity analysis for SaaS?"
    a: "Price sensitivity analysis measures how buyers in your target segment react to different price points - what reads as too cheap to trust, what reads as a fair deal, and what reads as too expensive to consider. The most common method for SaaS is the Van Westendorp Price Sensitivity Meter, which plots four thresholds from buyer responses to identify an acceptable price range. The output is a band, not a single number - your price should sit in the upper third of that band."
  - q: "What is the Van Westendorp method and how do you use it for SaaS pricing?"
    a: "The Van Westendorp Price Sensitivity Meter uses four questions to identify price thresholds: at what price is the product too cheap to trust its quality? At what price is it a good deal? At what price is it getting expensive but still worth it? At what price is it too expensive to consider? You need a minimum of 15 respondents for reliable results. Plot each threshold as a curve and find the intersections - the range between the lower acceptable bound and upper acceptable bound is your optimal price zone. Most early-stage SaaS products discover their current price sits below the lower bound."
  - q: "How many respondents do you need for a price sensitivity analysis?"
    a: "The Van Westendorp method requires a minimum of 15 respondents from your target segment for the output to be statistically reliable. Fewer than 15 produces a high-variance result that's hard to act on. The respondents must match your target buyer - not general users, not friends, and not buyers from a different segment than the one you're pricing for. B2B SaaS optimal price ranges typically span a 30-40% band between the lower and upper acceptable bounds."
---

# How to Run a Price Sensitivity Analysis for Your SaaS

The average SaaS company spends 8 hours total on pricing across its entire lifetime. That number produces prices set by gut feel, competitor anchoring, and the reluctance to lose any deal on price grounds - which is how most B2B SaaS founders end up 40-60% below their real price ceiling without knowing it. Price sensitivity analysis turns pricing into a testable question rather than a guess.

## Why this happens

Founders set prices under conditions that guarantee undercharging. They look at the cheapest competitor and price below it. They charge what their first customer said they'd pay - a buyer who wanted to support them, not a buyer who represents the segment. They pick a round number that feels low enough not to be a friction point. None of these methods surface actual willingness to pay.

The deeper problem is that price tolerance varies dramatically across segments. A feature that a solo founder values at $29 per month is worth $500 per month to a VP of Sales at a 200-person company. The same product, the same functionality, a 17x price gap - driven entirely by which segment you're selling to. Without segment-specific price testing, you're setting a single price for a range of buyers with fundamentally different willingness to pay.

Price sensitivity analysis solves this by asking buyers directly - using a structured method that accounts for anchoring bias and produces an acceptable range rather than a point estimate.

## What to check first

Four questions tell you whether your current price has been tested or just assumed:

1. **Did you set your price by looking at competitors first?** Competitor pricing is a useful reference point, not a data source. Competitors may be undercharging too. Their segment may be different from yours. Their pricing strategy may be intentionally below market to acquire volume. If competitor pricing was your primary input, you don't have a price - you have a mirrored guess.

2. **Have you ever asked a buyer the Van Westendorp four questions?** If you haven't explicitly asked at what price your product becomes too cheap to trust, at what price it's a fair deal, at what price it's getting expensive, and at what price it's too expensive - you haven't run price sensitivity analysis. You've had pricing conversations, which is different.

3. **Is your price the same across all segments you're selling to?** If you're selling to solo founders and enterprise teams at the same price, one of those segments is significantly mispriced. Price tolerance varies 3-5x across segments for the same product.

4. **Have you lost a deal because your price was too low?** This happens more than founders expect. In B2B, a price that's too cheap signals that the product may not be enterprise-ready or that the business may not survive. A champion inside a target account sometimes can't defend your price to their CFO because it seems suspiciously low for what it does.

## How to fix it

**Step 1: Identify your target segment for the analysis.**
Price sensitivity is segment-specific. Run the analysis separately for each segment you're considering targeting. A result from a mixed group of respondents tells you nothing actionable about any individual segment.

**Step 2: Recruit a minimum of 15 respondents who match the segment.**
Van Westendorp requires at least 15 respondents from your target buyer profile for the output to be statistically reliable. Below 15, the curve intersections are too noisy to act on. Recruit through LinkedIn outreach, customer communities, or your existing network - but confirm each respondent actually matches the segment you're testing.

**Step 3: Ask the four Van Westendorp questions in order.**
Present each respondent with a clear description of your product - what it does, who it's for, what it replaces. Then ask:

- At what price would this product be so cheap that you'd question its quality?
- At what price would this product seem like a good deal?
- At what price would this product be getting expensive, but you'd still consider it?
- At what price would this product be too expensive to consider?

Collect a specific price number for each answer. Don't let respondents give ranges.

**Step 4: Plot the four curves and find the intersections.**
Each question produces a cumulative frequency curve across the price range. The intersection of "getting expensive" and "good deal" defines your optimal price zone. B2B SaaS optimal ranges typically span a 30-40% band - if that band runs from $180 to $260 per month, your price should sit in the $220-260 range, not the bottom of the band.

**Step 5: Use the output to set price, not just confirm it.**
The output of a price sensitivity analysis is a price band and a confidence level, not a single number. Set your initial price in the upper third of the acceptable band. Monitor conversion rate for 30 days. If conversion holds, you've validated the upper range. If conversion drops more than 15%, move toward the middle of the band and retest.

**Step 6: Run the analysis again when you change segments.**
Price sensitivity results don't transfer between segments. If you've validated a price for solo founders and you're expanding into SMB teams, run the analysis again with the new segment before changing your pricing page.

## Remove the guesswork

Coordinating 15+ buyer interviews for a single price test takes 2-4 weeks minimum. [RightPrice]({{ '/docs/products/right-price/' | relative_url }}) runs the Van Westendorp analysis automatically against 100+ synthetic buyers calibrated to your segment. The output includes your optimal price range, your confidence score, and a recommendation on trial structure and packaging - in hours instead of weeks.

[Find your optimal price range with RightPrice](https://www.rightsuite.co/products/right-price?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=guide-price-sensitivity-analysis-saas){: .btn .btn-green }

---

Related: [How to Price a New SaaS Product]({{ '/guides/how-to-price-a-new-saas-product/' | relative_url }}) - [How to Know If You're Undercharging for Your SaaS]({{ '/guides/am-i-undercharging-for-my-saas/' | relative_url }}) - [RightPrice: how it works]({{ '/docs/products/right-price/' | relative_url }})
