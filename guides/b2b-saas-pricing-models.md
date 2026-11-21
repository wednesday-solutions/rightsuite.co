---
layout: default
title: "B2B SaaS Pricing Models Compared: Flat, Per-Seat, Usage, Tiered and Hybrid (2026)"
parent: Guides
description: "The 5 B2B SaaS pricing models in one table, plus how to pick one: charge on the unit your buyer's value grows with. Then test it with RightPrice."
faq:
  - q: "What are the main B2B SaaS pricing models?"
    a: "Five: flat-rate (one price for everything), per-seat (price per user), usage-based (price per unit consumed, like API calls or records), tiered (packages at different price points, usually split by features or limits), and hybrid (a base fee plus a usage or seat component). Freemium and free trials are ways to acquire customers, and sit on top of any of these."
  - q: "How do I choose a pricing model for my SaaS?"
    a: "Find the unit your buyer's value grows with. If value grows with the number of people using it, charge per seat. If it grows with volume processed, charge per usage. If every customer gets roughly the same value, charge a flat rate. If customers differ a lot in size or needs, use tiers. Then test buyer reaction before you build billing."
  - q: "Should I charge per seat or per usage?"
    a: "Per seat when each extra person using the product gets their own value, as in collaboration or role-based tools. Per usage when value comes from volume, as in automation, data or API products. Per-seat pricing on a usage-driven product caps what your heaviest customers pay, and buyers ration logins to save money."
  - q: "What is hybrid pricing in SaaS?"
    a: "A base subscription plus a variable part. For example, a monthly platform fee that includes a set amount of usage, then a per-unit charge above it. It gives buyers a predictable floor and lets you earn more from customers who use more."
  - q: "Can I change my pricing model later?"
    a: "Yes, but it's harder than changing a price. Existing customers have contracts and budgets built around the old model, and billing has to be rebuilt. Test the model before launch so you change prices, not structures, later."
---

# B2B SaaS Pricing Models Compared (And How to Pick One)

There are five B2B SaaS pricing models: flat-rate, per-seat, usage-based, tiered and hybrid. Pick the one that charges on the same unit your buyer's value grows with, so customers who get more value pay more without feeling punished. Then run the pick past simulated buyers in [RightPrice](https://rightsuite.co/products/right-price?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=guide-b2b-saas-pricing-models) before you build billing around it.

This guide is for founders choosing a model for a new product, or rethinking one that isn't working. If you already know the model and need the number, go to [how to price a new SaaS product from scratch]({{ '/guides/how-to-price-a-new-saas-product/' | relative_url }}).

[Test your pricing model with RightPrice](https://rightsuite.co/products/right-price?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=guide-b2b-saas-pricing-models){: .btn .btn-green }

## The 5 B2B SaaS pricing models in one table

| Model | How you charge | Fits when | Watch out for | Illustrative example |
|---|---|---|---|---|
| **Flat-rate** | One price, everything included | Customers are similar in size and get similar value | Big customers pay the same as small ones, so you leave money behind | $99/month, unlimited users |
| **Per-seat** | Price per user, per month | Each extra person gets their own value (collaboration, role tools) | Buyers share logins or cap seats to save money | $15 per user per month |
| **Usage-based** | Price per unit consumed | Value grows with volume (API calls, records, messages, minutes) | Bills vary month to month, which finance teams dislike | $0.002 per API call |
| **Tiered** | Packages at set prices, split by features or limits | Customers differ a lot in size or needs | Too many tiers confuse; wrong limits push everyone to the cheapest | $29 / $99 / $299 per month |
| **Hybrid** | Base fee plus a seat or usage component | You need a predictable floor and upside from heavy users | Harder to explain on a pricing page | $200/month incl. 10,000 records, then $10 per 1,000 |

Freemium and free trials aren't on this list because they're acquisition tactics. You can put a free tier or a trial in front of any of the five. For the trial question, see [why your free trial isn't converting]({{ '/guides/free-trial-not-converting/' | relative_url }}).

## How do I pick the right pricing model for my product?

Work through these steps in order. Each one narrows the field.

1. **Name your value metric.** Finish this sentence: "A customer gets more value from us when they have more ___." Users? Records? Contacts? Projects? Locations? That blank is the unit you want to price on.
2. **Check if value scales with people or with volume.** If adding a teammate gives that teammate their own benefit, it's people, so look at per-seat. If one person can push ten times more through the product and get ten times the result, it's volume, so look at usage-based.
3. **Check how different your customers are.** If a 5-person team and a 200-person team would use the product the same way, flat-rate keeps things simple. If they'd use it very differently, you need tiers or a variable component.
4. **Check your cost to serve.** If heavy users cost you real money (AI inference, compute, storage, messages sent), a flat price transfers that cost to you. Add a usage component or usage limits per tier.
5. **Check how your buyer pays.** Buyers with a fixed annual budget prefer predictable bills. If your value metric is usage but your buyer needs predictability, use hybrid: a committed base with included usage.
6. **Pick one, and write the pricing page sentence.** If you can't explain the model in one line ("$X per seat per month, billed annually"), the buyer won't understand it either.

## Worked example: picking a model for a meeting-notes tool

For example, say you sell an AI tool that turns sales calls into CRM notes.

- **Value metric:** the number of calls processed. A rep with 40 calls a week gets more value than one with 5.
- **People or volume?** Both, but volume drives your cost, because every call costs you transcription and model time.
- **Customer spread:** 3-person startups and 50-rep sales teams.
- **Buyer:** a sales leader with a fixed tool budget.

Per-seat alone would let a heavy team cost you more than they pay. Pure usage would give the sales leader an unpredictable bill. Hybrid fits: per seat, with a set number of calls included, and a per-call charge above it. That's the hypothesis to test.

## Symptom, check, fix

| Symptom | Check | Fix |
|---|---|---|
| Your biggest customers pay barely more than your smallest | Are you on flat-rate while value grows with size? | Add tiers or a seat or usage component. |
| Customers share one login | Are you per-seat on a product where one person does the work? | Price on the output (usage) or the account, not the seat. |
| Prospects stall at "we can't predict the bill" | Are you on pure usage with budget-bound buyers? | Move to hybrid with included usage. |
| Almost everyone picks the cheapest tier | Do the tier limits match how customers actually grow? | Move the limit to the value metric so growing customers hit it. |
| Heavy users are unprofitable | Is cost to serve rising with usage you don't charge for? | Add usage limits or a usage component. |

## How to test your pricing model with RightPrice

A pricing model is a guess until buyers react to it. [RightPrice](https://rightsuite.co/products/right-price?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=guide-b2b-saas-pricing-models) gives you a first read before you build billing or tell anyone.

1. Describe your offer, the price written exactly as it would appear on your pricing page, and your target audience.
2. RightPrice builds buyer personas for that audience: buyer archetypes, plus a competitor-minded persona and a skeptic. They discuss your offer in a simulated session you can watch live.
3. You get a confidence score, a sentiment breakdown, willingness-to-pay analysis, a price assessment, and objections and feedback from each buyer.
4. Run it again with the second-best model. For the example above, compare "$30 per seat per month" against "$30 per seat including 100 calls, then $0.20 per call." Read which objections appear in one run and not the other.

A Quick run takes about 10 minutes and 1 credit; Standard about 20 minutes and 2 credits; Deep about 30 minutes and 3 credits. Simulated buyers give you a fast first read. Confirm the winner in real sales conversations before you lock it into contracts.

## FAQ

**What are the main B2B SaaS pricing models?**
Flat-rate, per-seat, usage-based, tiered and hybrid. Freemium and free trials are acquisition tactics that sit on top of any of them.

**How do I choose a pricing model for my SaaS?**
Find the unit your buyer's value grows with. People means per seat. Volume means usage. Same value for everyone means flat. Big differences between customers mean tiers. Then test buyer reaction before you build billing.

**Should I charge per seat or per usage?**
Per seat when each extra person gets their own value. Per usage when value comes from volume. Per-seat pricing on a usage-driven product caps what heavy customers pay.

**What is hybrid pricing in SaaS?**
A base subscription plus a variable part, such as a monthly fee with included usage and a per-unit charge above it.

**Can I change my pricing model later?**
Yes, but it costs more than changing a price, because contracts, budgets and billing are built around the model. Test it before launch.

## Next step

Write your value metric sentence, pick the model from the table, and [run that pricing through RightPrice](https://rightsuite.co/products/right-price?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=guide-b2b-saas-pricing-models) against your second choice. For a deeper walk through the decision, see [how to choose the right pricing model for your SaaS]({{ '/guides/how-to-choose-saas-pricing-model/' | relative_url }}).
