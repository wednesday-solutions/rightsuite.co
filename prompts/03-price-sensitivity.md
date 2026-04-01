---
layout: default
title: "03 - Price Sensitivity Test"
parent: Prompts
nav_order: 3
---

# Prompt 03 - Price Sensitivity Test

**The decision:** What should I charge?

**When to use this:** You have a price but you're not confident it's right. Or you're pre-launch and trying to decide between $29, $49, and $99. Or you want to know if you're leaving money on the table.

[← Back to prompt library](./README.md)

---

## The Prompt

```
You are a SaaS pricing analyst. You think like a buyer, not a seller.

I'm selling:

Product: [NAME]
What it does: [1-2 sentence description]
The specific outcome it delivers: [what the buyer has after using it - be concrete]
My target buyer: [job title, company type, company size]
Current price: [PRICE/mo] - or "undecided" if you haven't set one
Business model: [SaaS subscription / one-time / usage-based / agency retainer]

Competitors and their prices:
- [Competitor 1]: $[PRICE]/mo - [what they offer]
- [Competitor 2]: $[PRICE]/mo - [what they offer]
- Status quo (no tool): [time/cost the buyer spends doing this manually]

Simulate how my target buyer reacts to three price points: $[LOW], $[MID], $[HIGH].
(If I said "undecided", suggest three sensible test points for my category.)

For each price point give me:

1. IMMEDIATE GUT REACTION
   The first thought a buyer has when they see this price, stated in their own words.

2. PERCEIVED VALUE ALIGNMENT
   Does this price feel consistent with the quality/outcome I described, or does it signal something wrong?

3. OBJECTIONS AT THIS PRICE
   Specific concerns this price triggers - not generic "too expensive" but the actual thought process.

4. WHO BUYS AT THIS PRICE
   The specific sub-segment of my target buyer who would pay this without much friction.

5. WHO WALKS AWAY AT THIS PRICE
   Who this price loses, and why.

6. CONVERSION FRICTION SCORE (1-10)
   10 = they pay immediately, no hesitation. 1 = this price kills the deal.

End with:
- The optimal price point for maximum conversion (not maximum revenue - explain the difference)
- The optimal price point for maximum revenue
- Your recommended trial or onboarding model (free trial / freemium / paid pilot / demo-first) with reasoning
- The one pricing change that would have the most impact on conversion right now
```

---

## How to interpret the output

**"Immediate gut reaction"** is what your pricing page has to overcome. If the gut reaction is "that seems steep for a tool I haven't tried," you have a trial model problem, not a price problem.

**"Maximum conversion vs. maximum revenue" is the key split.** Early-stage: optimise for conversion - you need proof, testimonials, and case studies more than you need margin. Post-traction: optimise for revenue. Most founders price for conversion but think they're pricing for revenue, and end up underpriced for too long.

**The trial model recommendation matters as much as the price.** A wrong trial model kills conversion at any price. "Free trial converts at 15-25% for B2B SaaS. Freemium converts at 2-5%. If your time-to-value is under 30 minutes, free trial dominates." - Price Intelligently, 2024.

---

## The Van Westendorp shortcut

If you want to go deeper without running a full survey, add this to the prompt:

```
Also give me Van Westendorp estimates for my product:
- At what price does this feel so cheap it raises quality concerns?
- At what price does this start to feel expensive but still worth it?
- At what price does this feel too expensive regardless of quality?
- At what price does this feel like a bargain?

State each as a specific dollar amount, not a range.
```

Van Westendorp is a survey methodology for mapping price sensitivity. These estimates from an AI are rough proxies - but they'll tell you if you're wildly outside the zone.

---

## What to do next

- Use the optimal price in your copy - run your pricing section through [Prompt 04 (Copy Scorecard)](./04-copy-scorecard.md)
- Use the "objections at this price" as the things your FAQ and landing page copy need to address
- If the trial model recommendation contradicts what you're currently doing, that's the highest-priority change

---

*For 100+ simulated buyer reactions across 12 personas with a confidence score and official price range, use [RightPrice](https://www.rightsuite.co/products/right-price?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=prompt-right-price).*
