# Skill: competitive-displacement

**Module:** sales-skills
**Version:** 1.0
**Reads From:** `.agents/product-marketing-context.md`, `marketing-skills/skills/competitor-alternatives/SKILL.md`
**Triggered By:** `/displace`, `/competitive`, `/steal`, `/vs`

---

## What This Skill Does

This skill is for taking a customer away from a competitor.
Not defensively — offensively.

It covers how to identify displacement opportunities, how to reframe
the competitor's weaknesses as the prospect's pain, and how to close
against an incumbent without triggering a defensive loyalty response.

Drawn from MEDDICC (Andy Whyte), Gong/Chris Orlob sales intelligence
research, and competitive intelligence frameworks from Klue and Crayon.

---

## When To Trigger This Skill

- Prospect says "We already use [competitor]"
- You discover an account is up for renewal with a competitor
- Competitor has a public outage, price increase, or negative press
- Prospect expresses frustration with their current tool but isn't actively looking
- You are building a target account list and want to identify displacement candidates

---

## Core Frameworks

### Framework 1: The Displacement Trigger Identification

Not every competitor customer is worth pursuing.
Target accounts where one or more of these triggers exist:

**Product Triggers:**

- Competitor recently deprecated a feature your prospect relies on
- Competitor raised prices (check their pricing page / G2 reviews)
- Competitor had a notable outage or data incident
- Competitor was acquired (instability / roadmap uncertainty)

**Relationship Triggers:**

- Champion at the account who bought the competitor has left
- New executive joined who has no loyalty to the incumbent
- IT/procurement is running a formal re-evaluation

**Growth Triggers:**

- Company has scaled beyond what the competitor's tier supports
- Company entering new markets the competitor doesn't serve well
- New use case emerged that competitor wasn't built for

**How to find these signals:**

- G2/Capterra reviews (look for 3-star reviews — they're the most honest)
- LinkedIn (who just joined the account, who just left)
- Competitor's changelog / release notes (what aren't they building?)
- Job postings at target account (what tools are they hiring for?)

---

### Framework 2: The Reframe — Don't Attack, Illuminate

Never directly attack a competitor. It triggers defensiveness and makes you look insecure.
Instead, ask questions that make the prospect feel the pain themselves.

**The Illumination Sequence:**

1. **Acknowledge the incumbent:** "Makes sense — [competitor] is a solid tool for [use case]."
2. **Plant the seed:** "One thing we hear from teams that have come from [competitor] is [specific limitation]. Is that something you've bumped into?"
3. **Let them talk:** If they haven't felt the pain, they'll say so. If they have, they'll tell you more than you asked for.
4. **Connect to cost:** "What does that cost you when [limitation] shows up?"

**Rule:** You want them to discover the problem, not hear it from you.
A problem they discovered themselves is 10x more compelling than one you told them about.

---

### Framework 3: The Competitive Trap Questions

These questions are designed to surface gaps the competitor can't fill,
without you ever naming the gap directly.

Pull the specific answers from `product-marketing-context.md` before using these.

**Template Questions:**

- "How important is [your differentiating capability] to your workflow?"
- "How are you currently handling [problem your product uniquely solves]?"
- "When [specific scenario where competitor fails] happens, what do you do?"
- "What would need to be true about a solution for you to consider switching?"

**The last question is the most powerful.** It gets the prospect to build
your pitch for you. Whatever they say, you respond with: "That's exactly
what we built [feature] for. Can I show you?"

---

### Framework 4: The Switching Cost Neutralizer

The #1 reason prospects don't switch is fear of switching costs — migration pain,
retraining, contract lock-in. You must neutralize this proactively.

**Switching Cost Objections and Responses:**

| Objection | Response |
|---|---|
| "We just renewed with them" | "When does that come up? We can start a parallel evaluation now so you're ready to make the call with full information." |
| "Our team is trained on their system" | "What if onboarding your team took less than [X days]? We have customers who were live in [timeframe]." |
| "Migration will be a nightmare" | "We have a dedicated migration team. Here's what that process looks like for a team your size." |
| "Our data is locked in there" | "You own your data. Here's exactly how you export it and what we do with it on import." |

**Rule:** Have a concrete, specific answer for every switching cost.
Vague reassurance makes it worse. Specificity builds confidence.

---

### Framework 5: The Competitive POC (Proof of Concept)

When a prospect is evaluating you against their incumbent, structure the POC to win.

**POC Design Principles:**

1. **Define success criteria upfront** — in writing, with the prospect. "If we can demonstrate [X], you'll move forward." Get them to agree before the POC starts.
2. **Focus the POC on your strengths** — specifically the areas where the competitor is weakest. Do not let the evaluation be on neutral ground.
3. **Involve the champion** — have them define at least one success criterion. Now they're invested in the outcome.
4. **Set a hard end date** — open-ended POCs die. "We'll run this for 2 weeks and reconvene on [date]."
5. **Document every win during the POC** — keep a running log of moments where your product outperformed. Present it at the end.

---

### Framework 6: The Competitive Battle Card

Before any competitive conversation, pull the relevant battle card from
`../marketing-skills/competitor-alternatives/` and cross-reference with
`product-marketing-context.md`.

For each competitor, you should know:

- Their 3 biggest product weaknesses (from real customer reviews, not your marketing)
- Their typical customer profile (are their customers actually similar to your prospect?)
- Their pricing model and where it breaks down at scale
- Their recent product/company news (acquisitions, layoffs, pivots)
- The customers they've lost to you and why

---

## Output Format

When this skill is triggered, the agent will produce:

1. **Displacement Viability Score:** Is this account worth pursuing right now? Why?
2. **Identified Triggers:** Which displacement signals are present?
3. **Illumination Questions:** Specific questions to surface pain (calibrated to this competitor)
4. **Competitive Trap Questions:** Tailored to your product's differentiators vs. this competitor
5. **Switching Cost Neutralizers:** Pre-loaded responses for expected objections
6. **POC Design:** If applicable, a structured evaluation framework designed to win
7. **Battle Card Summary:** Key competitive facts pulled from context hub

---

## Guardrails

- Never make false claims about a competitor's product
- Never use information shared by a mutual customer about their other vendor
- All competitive claims must be sourced (G2, public documentation, press)
- Cross-reference all displacement plays with `competitor-alternatives` skill before execution
- If competitive intel is older than 90 days, flag it as potentially stale
