---
layout: default
title: "05 — Cold Outreach Diagnostic"
parent: Prompts
nav_order: 5
---

# Prompt 05 — Cold Outreach Diagnostic

**The decision:** Will they respond?

**When to use this:** Before you send a cold email, LinkedIn DM, or outreach sequence. Before you burn through your list on a message that was never going to get a reply.

[← Back to prompt library](./README.md)

---

## The Prompt

```
You are a cold outreach coach who has reviewed 10,000+ cold emails. You think like the recipient — someone who gets 30+ cold emails a day and has developed a finely tuned filter for what gets deleted vs. what gets a reply.

My target recipient:
- Job title: [TITLE]
- Company type: [TYPE]
- Company size: [SIZE]
- Their likely pain right now: [1 sentence — what problem are they dealing with that my product solves]

Here is my outreach message:

---
Subject: [SUBJECT LINE]

[PASTE YOUR EMAIL/DM HERE]
---

Diagnose this message from the recipient's perspective. Give me exactly these sections:

1. FIRST IMPRESSION (the read in under 3 seconds)
   What does the recipient think this is before they've read past the first line? Spam? Vendor pitch? Genuine outreach? Something else?

2. DELETE TRIGGERS
   Specific words, phrases, or structural patterns in this message that trigger the "delete" reflex. Be brutal.

3. TONE DIAGNOSIS
   Is this coming across as: Genuine / Salesy / Pushy / Unclear / Robotic / Other?
   What specific elements create that impression?

4. RELEVANCE SCORE (1-10)
   Does this message speak to a real problem this recipient has right now, or does it sound like it was sent to a list?

5. REPLY INTENT SCORE (1-10)
   How motivated is the recipient to reply after reading? 10 = they'll reply today. 1 = instant delete.

6. THE KILLER LINE
   The one sentence in this message that is most likely to make them keep reading. If there isn't one, say so.

7. THE DEATH SENTENCE
   The one sentence most likely to make them close the email. If there are multiple, list the worst one.

Then give me:

REWRITTEN VERSION
A full rewrite of the email that fixes the main issues. Keep the same core offer but make it sound like a person, not a pitch.

SUBJECT LINE VARIANTS
3 alternative subject lines ranked by predicted open rate, with a one-sentence explanation for each.
```

---

## The rules of cold outreach that don't change

**Rule 1: It's not about you until they ask.**
The recipient does not care about your product, your company, or your launch. They care about their problem. Every sentence that's about you is a sentence they're not reading.

**Rule 2: Specificity is the only personalization that works.**
"I saw you work in [industry]" is not specific. "I noticed you're hiring 3 SDRs this quarter — that usually means the current outreach process is breaking down" is specific. AI has commoditized fake personalization. Real specificity is the only thing that still cuts through.

**Rule 3: One ask, clearly stated.**
The biggest single improvement most founders can make to their cold outreach: end with a binary question, not an open-ended "would love to connect." "Do you have 15 minutes Thursday?" converts better than "let me know if you'd like to chat."

**Rule 4: The subject line is a promise.**
It shouldn't describe your email — it should promise something the recipient wants. "Quick question" is tired. "[Their company name] + [your product category]" works because it signals relevance before they open.

---

## Multi-step sequence diagnostic

If you're testing a full sequence (3-5 emails), paste each message separately and add this to the prompt:

```
This is email [NUMBER] in a [TOTAL]-step sequence.
Previous emails in the sequence covered: [brief summary]
The recipient has not replied to any previous emails.

In addition to the standard diagnostic, tell me:
- Is the gap in tone/approach between this email and the previous one jarring or natural?
- Is there a clear reason to send this email that's distinct from the previous one?
- At what point in this sequence would you personally unsubscribe?
```

---

## What to do next

- If the relevance score is below 6, the problem is likely your ICP — run [Prompt 01](./01-icp-validation.md) again and confirm you're targeting the right segment
- If the tone diagnosis is "salesy" or "robotic," read the rewrite aloud. If you wouldn't say it in person, don't send it
- Use the rewritten version as a starting point, not a final draft. Edit it until it sounds like you.

---

*For predicted reply rates across 100+ simulated buyer reactions with sequence drop-off analysis, use [RightEngagement](https://www.rightsuite.co/products/right-engagement).*
