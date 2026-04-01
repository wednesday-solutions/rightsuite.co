---
layout: default
title: Zero-Customer GTM
parent: Playbook
nav_order: 1
---

# The Zero-Customer GTM Playbook

**For vibe coders, solo founders, and indie hackers who built a product and now need to sell it.**

Every GTM guide you've found starts with "analyse your best customers." This one doesn't, because you don't have any yet.

This is the procedure for the pre-customer stage. Seven decisions, in the right order, with the specific action to take at each step.

[← Back to Right Suite](../README.md) | [Automate the validation](https://www.rightsuite.co?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=playbook-homepage)

---

## Who this is for

You:
- Built something with AI, no-code, or code
- Have a landing page (or are about to)
- Have zero or fewer than 10 paying customers
- Are not sure if the price is right, the messaging is working, or you're talking to the right people
- Have heard "just talk to customers" a hundred times and want something more structured

This is not a strategy document. It is a procedure. Work through it in order.

---

## The 7 Decisions

```
Decision 1: WHO    → Who has the highest purchase intent for my offer?
Decision 2: WHY ME → Why would they pick me over the alternatives?
Decision 3: PRICE  → What will they actually pay?
Decision 4: COPY   → Does my landing page convert?
Decision 5: REACH  → How do I start conversations cold?
Decision 6: CHANNEL → Where do I find them at scale?
Decision 7: ADS    → Does my paid creative work before I spend?
```

You can't shortcut the order. Decision 5 (cold outreach) is less effective if you haven't done Decision 1 (ICP). Decision 4 (copy) is weaker if you haven't done Decision 2 (positioning). Each step builds context for the next.

---

## Decision 1: WHO - Find Your Highest-Intent Segment

### The question
Which type of buyer has the most urgent need for what I built, right now, at a price they'll pay without friction?

### The common mistake
Selling to whoever will talk to you.

Early-stage founders talk to friends, ex-colleagues, and warm intros. Those people are nice. They give feedback. They sometimes say "I'd pay for that." Then they don't. Because they were your customer because they knew you - not because they had the problem you solve.

Your actual ICP is defined by the urgency of the problem, not the warmth of the relationship.

### What to do

1. Write down 3 candidate segments - specific job titles at specific company types and sizes. Example: "Head of Sales at 10-30 person B2B SaaS" not "sales teams."

2. For each segment, answer:
   - How urgently do they feel the pain I solve? (1-10)
   - What would it cost them (time, money, missed opportunity) to NOT solve it this quarter?
   - How do they currently solve this without a tool like mine?
   - What's happening in their world right now that would make them actively search for a solution?

3. Score and rank. The segment with the highest urgency AND the clearest buying trigger is your beachhead. Not the biggest market - the most urgent problem.

**Use:** [ICP Scoring Matrix template](../templates/icp-scoring-matrix.md) | [ICP Validation prompt](../prompts/01-icp-validation.md) | [RightAudience](https://www.rightsuite.co/products/right-audience?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=playbook-right-audience)

### Output from this step
One specific segment definition: "[Job title] at [company type], [company size], who is currently [situation that makes them urgently need your product]."

Write it down. Every subsequent decision uses this as an input.

---

## Decision 2: WHY ME - Find Your Positioning Angle

### The question
When a buyer in my target segment evaluates my product alongside the alternatives, what makes me the obvious choice?

### The common mistake
Listing features as differentiation.

"We have X integration" is not a positioning angle. "We're the only tool that does Y for Z" is a positioning angle - if it's true, if Y matters to your segment, and if your competitors don't claim it.

The other mistake: treating "simpler than X" as a position. Everyone says they're simpler. You need a specific axis of simplicity tied to a specific pain.

### What to do

1. List your 3 main competitors - including the status quo (how buyers solve this without a tool). What does each one claim?

2. Map your product against each competitor on the dimensions your target buyer actually cares about. Not the dimensions you think matter - the dimensions they search for when evaluating tools in your category.

3. Find the gap. What angle does no current player own? That's your positioning.

4. Write your positioning statement: "[Product] is the [category] for [specific segment] who [specific situation], unlike [alternatives] which [limitation]."

**Use:** [Positioning Audit prompt](../prompts/02-positioning-audit.md) | [RightPositioning](https://www.rightsuite.co/products/right-positioning?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=playbook-right-positioning)

### Output from this step
One positioning statement and one differentiator angle - the thing you'll lead with in every conversation, every email, every piece of content.

---

## Decision 3: PRICE - Set a Price You Can Defend

### The question
Is my price in the range where my target segment will pay without friction, or am I leaving money on the table / pricing myself out?

### The common mistake
Copying a competitor's price.

A competitor's price reflects their customer segment, their cost structure, their brand equity, and their conversion funnel - none of which you have yet. Copying their price doesn't mean your buyers will respond the same way.

The second mistake: pricing for sustainability before you've validated conversion. If you're pre-10 customers, price for conversion first. You can raise prices once you have proof.

### What to do

1. Write down your current price and the reasoning behind it. If the reasoning is "it felt right" or "similar to X," that's the problem.

2. Find the floor: what's the lowest price that doesn't raise quality concerns for your segment? (Below this, buyers think something is wrong.)

3. Find the ceiling: what's the highest price your segment would pay without needing a procurement process or lengthy evaluation?

4. Check your trial model: for B2B SaaS at sub-$100/mo, free trial converts at 15-25%. Freemium converts at 2-5%. If your time-to-value is under 30 minutes, you should almost certainly be running a free trial, not requiring a credit card upfront.

**Use:** [Price Sensitivity Test prompt](../prompts/03-price-sensitivity.md) | [RightPrice](https://www.rightsuite.co/products/right-price?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=playbook-right-price)

### Output from this step
A defended price (not just a number - a rationale), a trial strategy, and the top price objection your copy needs to address.

---

## Decision 4: COPY - Write a Landing Page That Converts Cold Traffic

### The question
If someone who has never heard of me lands on my page, will they understand what I do, believe the claim, and take the action I want?

### The common mistake
Writing for people who already understand the context.

Founders write copy that makes sense to them - because they've been living with the product for months. A cold visitor has none of that context. They're scanning, not reading. They're looking for their problem, not your solution. If your hero doesn't reference their specific situation in the first sentence, they're gone.

### What to do

1. Run a 5-second test: cover your landing page and write down what a first-time visitor would think the product does based on the hero alone. If that doesn't match what you actually do, rewrite the hero.

2. Apply the "so what?" chain to every line. "AI-powered pricing validation" → so what? → "you'll know if your price is right before you launch" → so what? → "you won't lose sales to a price that's too high or leave money on the table." The last link in the chain is the thing to say.

3. Check that your copy handles the top 3 objections your segment has. These came out of Decision 1 (ICP). If you don't address them on the page, buyers leave with unresolved doubt.

**Use:** [Landing Page Copy Formula template](../templates/landing-page-copy-formula.md) | [Copy Scorecard prompt](../prompts/04-copy-scorecard.md) | [RightMessaging](https://www.rightsuite.co/products/right-messaging?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=playbook-right-messaging)

### Output from this step
A landing page that a cold visitor can understand in 5 seconds, with a hero that references their specific situation and a CTA that says what happens next.

---

## Decision 5: REACH - Start Conversations Before You Have a Channel

### The question
How do I get in front of my target buyers right now, before I've built a channel or an audience?

### The why-it-matters
Before you have a scalable channel, you need signal. Signal comes from conversations with real buyers. The fastest way to get conversations is direct outreach - cold email, LinkedIn DMs, community posts. This is your validation channel, not your growth channel.

The goal of Decision 5 is not to get 100 customers. It's to get 10 conversations that tell you whether your positioning, price, and copy are right.

### The common mistake
Sending templates.

Every founder has the same 5 cold email templates. Buyers have seen all of them. Generic personalisation ("I love what you're building at [Company]") makes it worse - it signals you're blasting a list.

The only thing that works: a real reason to reach out to this specific person at this specific company right now.

### What to do

1. Find 20 people who match your ICP exactly. Not vaguely - exactly. Use LinkedIn, Apollo, or manual research.

2. For each person, find one specific, real reason to reach out that relates to your product's value prop. A job posting, a recent tweet, a company announcement, a product update.

3. Write one email that opens with that observation, connects it to the problem you solve in one sentence, and ends with one binary ask (not "let me know if you're interested").

4. Send 20 manually. Judge the response rate after 20 - not 5.

**Use:** [Cold Email Swipe File template](../templates/cold-email-swipe-file.md) | [Cold Outreach Diagnostic prompt](../prompts/05-cold-outreach-diagnostic.md) | [RightEngagement](https://www.rightsuite.co/products/right-engagement?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=playbook-right-engagement)

### Output from this step
A proven outreach message (one that got a reply rate above 15%) and a documented understanding of what objections come up in conversations.

---

## Decision 6: CHANNEL - Pick the One Channel to Go Deep On

### The question
Once I've validated the offer through direct outreach, which channel should I invest in for repeatable, scalable acquisition?

### The common mistake
Picking a channel because it worked for someone else.

"Go on Twitter" is advice for someone with a Twitter audience. "Write SEO content" is advice for someone with a 12-month runway to wait for traffic. "Launch on Product Hunt" is advice for devtool products with a developer audience. None of these are universal.

The right channel depends on where your specific buyers are, what mode they're in when they're there, and what you can execute consistently.

### The channel decision matrix

| Channel | Works best when | Doesn't work when |
|---------|----------------|-------------------|
| Cold email | You have a specific list and a specific reason to reach out | Your ICP is too broad to personalise at volume |
| LinkedIn organic | You can post consistently and your buyers are on LinkedIn daily | Your buyers are developers or ops people who don't use LinkedIn |
| SEO / content | You have 6+ months of runway and can write | You need customers this month |
| Community | You're genuinely active in the communities where your buyers are | You're joining communities just to post links |
| Product Hunt | Your product is developer-facing or has a strong design angle | Your buyers are non-technical B2B buyers who don't browse PH |
| Paid ads | You have a proven conversion funnel first | You haven't validated copy and pricing (burning money on unproven pages) |
| Partnerships | You have a relationship with a complementary tool's founder | You're reaching out cold to ask for a partnership |

### What to do

1. List the 3 channels you're considering. For each: where do your buyers spend time in this channel? What mode are they in (discovery vs. browsing vs. searching)?

2. Pick one primary channel. Go deep for 60 days before evaluating. You can't judge a channel in 2 weeks.

3. Pick one compound channel to start building in parallel (usually content/SEO or community). Don't expect results for 6+ months. Start anyway.

**Use:** [Channel Fit Analysis prompt](../prompts/06-channel-fit.md) | [RightChannel](https://www.rightsuite.co/products/right-channel?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=playbook-right-channel)

### Output from this step
One primary channel with a 60-day experiment plan, and one compound channel you're starting to build.

---

## Decision 7: ADS - Test Before You Spend

### The question
If I decide to run paid ads, will my creative actually stop the scroll before I find out the expensive way?

### When to make this decision
After Decision 6. Paid ads are a distribution channel - you should only consider them once you've validated that your copy converts, your price is right, and you know which channel your buyers are on. Running ads before validating those upstream decisions is paying to send traffic to a funnel that doesn't work.

### The common mistake
Optimising the ad before optimising the landing page.

A great ad that sends traffic to a weak landing page loses to a mediocre ad that sends traffic to a strong landing page. Validate your landing page (Decision 4) before you test creative.

### What to do

1. Write 3 versions of your hook - the first line or frame that has to stop the scroll:
   - Pain-first: lead with the situation the buyer is in ("Still pricing your SaaS based on what your competitors charge?")
   - Outcome-first: lead with the specific result ("Know if your price is right before you launch - in 10 minutes")
   - Pattern-interrupt: lead with something unexpected ("The average SaaS company spends 8 hours on pricing. Total. Ever.")

2. Test all three with equal budget. Let the data pick the winner after 500+ impressions per variant.

3. Don't iterate on the winner until it stops working. Creative fatigue is real but it takes longer than you think - resist the urge to change what's working.

**Use:** [Ad Creative Review prompt](../prompts/07-ad-creative-review.md) | [RightAd](https://www.rightsuite.co/products/right-ad?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=playbook-right-ad)

### Output from this step
A proven hook and a tested creative that you can scale with confidence.

---

## The anti-checklist

Things this playbook will not tell you to do, because they are almost always wrong at the zero-customer stage:

**Build a waitlist before validating the offer.**
A waitlist of people who signed up for a vague promise is not validation. It's email addresses. Validate the offer with real conversations before you run waitlist ads.

**Write a blog to get SEO traffic.**
SEO compounds over 12+ months. If you need customers in the next 90 days, SEO is not the answer. Start with direct outreach, add SEO in parallel.

**Go broad on ICP to maximise the market.**
"SaaS founders" is not an ICP. "Head of Sales at 10-30 person B2B SaaS companies who recently missed their outreach targets" is an ICP. The more specific the segment, the better the conversion. You can expand later.

**Perfect the product before starting GTM.**
There is no version of your product that's ready. Start GTM now. The conversations will tell you what to build.

**Wait for social proof before launching.**
You get social proof by launching. Launch without it, get it from the first 3 customers, then add it.

---

## Progress tracker

| Decision | Status | Key output | Date completed |
|----------|--------|-----------|----------------|
| 1. WHO - ICP | Not started | Target segment definition | |
| 2. WHY ME - Positioning | Not started | Positioning statement + differentiator | |
| 3. PRICE - Pricing | Not started | Defended price + trial model | |
| 4. COPY - Messaging | Not started | Landing page that passes 5-second test | |
| 5. REACH - Outreach | Not started | Proven message with >15% reply rate | |
| 6. CHANNEL - Distribution | Not started | Primary channel + 60-day plan | |
| 7. ADS - Creative | Not started | 3 hook variants to test | |

---

## The honest version of what happens next

You work through these 7 decisions. You validate each one. You get to 10 customers.

Then the playbook changes. You now have data. You can analyse your best customers, find the pattern, and double down. Everything from this point is a different problem - a better problem.

But you can't get there without getting here first.

---

*Right Suite automates the validation at each step - simulated buyer reactions, scored reports, specific recommendations. [Start here](https://www.rightsuite.co?utm_source=docs&utm_medium=referral&utm_campaign=docs&utm_content=playbook-homepage).*
