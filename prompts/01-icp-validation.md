---
layout: default
title: "01 — ICP Validation"
parent: Prompts
nav_order: 1
---

# Prompt 01 — ICP Validation

**The decision:** Who should I sell to?

**When to use this:** You have an offer but you're not sure which segment has the highest purchase intent. You're considering 2-4 different buyer types and need to rank them.

[← Back to prompt library](./README.md)

---

## The Prompt

```
You are a go-to-market strategist who specialises in early-stage SaaS and has helped 200+ founders find their ideal customer profile.

I've built the following product:

Product name: [NAME]
What it does: [1-2 sentence description]
The core problem it solves: [specific pain point]
Current price: [PRICE/mo or one-time]
Stage: [pre-launch / just launched / early traction]

I'm considering targeting these buyer segments:
Segment A: [job title, company type, company size]
Segment B: [job title, company type, company size]
Segment C: [job title, company type, company size — optional]

For each segment, give me a structured analysis with exactly these sections:

1. PURCHASE INTENT SCORE (1-10)
   Rate how urgently this segment would buy a solution to this problem right now.

2. WILLINGNESS TO PAY
   Estimated monthly budget range this persona has for tools in this category.

3. TOP OBJECTION
   The single most likely reason they wouldn't buy, stated in their own words.

4. WHAT THEY NEED TO HEAR
   The one sentence that would make this segment immediately interested.

5. DEAL BREAKERS
   2-3 things that would make them walk away regardless of price.

6. BUYING TRIGGER
   The specific event or situation that would make them actively search for a solution like this right now.

End with:
- A ranked order of the segments by conversion probability
- The segment I should focus on first and why
- One segment I haven't mentioned that might be worth testing
```

---

## How to interpret the output

**Purchase intent score 8+:** This segment actively feels the pain. They're searching for solutions. Go here first.

**Purchase intent score 5-7:** They have the problem but it's not urgent enough to act. You'll need demand-gen content before direct outreach.

**Purchase intent score below 5:** Wrong segment or wrong timing. Don't try to create urgency — find the segment that already has it.

**The "buying trigger" is the most important output.** This is what your cold outreach, ads, and landing page should reference. If you can speak to the trigger, you'll outperform generic value-prop messaging every time.

---

## What to do next

- Use the top-ranked segment as your input for [Prompt 02 (Positioning Audit)](./02-positioning-audit.md) and [Prompt 03 (Price Sensitivity)](./03-price-sensitivity.md)
- Use the "what they need to hear" line as the starting point for your hero headline in [Prompt 04 (Copy Scorecard)](./04-copy-scorecard.md)
- Use the "buying trigger" in your cold outreach — run it through [Prompt 05 (Cold Outreach Diagnostic)](./05-cold-outreach-diagnostic.md)

---

## Example filled-in prompt

```
Product name: Waitroom
What it does: Adds a live demo booking widget to SaaS landing pages — no code, 5-minute setup
Core problem: Founders lose inbound leads because there's no easy way to book a live demo from a landing page
Current price: $49/mo
Stage: Just launched

Segment A: Solo SaaS founders, B2B product, pre-Series A
Segment B: Head of Sales at 10-50 person SaaS company
Segment C: Marketing managers at PLG SaaS companies
```

---

*For 100+ buyer simulations with scored outputs, use [RightAudience](https://www.rightsuite.co/products/right-audience).*
