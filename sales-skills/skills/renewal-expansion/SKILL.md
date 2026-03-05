# Skill: renewal-expansion

**Module:** sales-skills
**Version:** 1.0
**Reads From:** `.agents/product-marketing-context.md`, `../job-os/KPI-DASHBOARD.md`
**Triggered By:** `/renew`, `/expand`, `/upsell`, `/churn-risk`

---

## What This Skill Does

Acquiring a new customer costs 5-7x more than retaining one.
Expansion revenue from existing accounts is the highest-margin, lowest-friction
growth lever available.

This skill manages the full renewal and expansion motion — from early health signals
to expansion conversations to at-risk intervention — before it becomes a crisis.

Drawn from *Customer Success* (Mehta), Gainsight's CS frameworks, and
SaaS revenue expansion playbooks.

---

## When To Trigger This Skill

- 90 days before a contract renewal date
- Customer hasn't logged in / engaged in 30+ days
- Champion leaves the account
- Customer complains (even once)
- Customer hits a usage limit or milestone that signals expansion readiness
- QBR (Quarterly Business Review) preparation
- You want to introduce a new product/tier to an existing customer

---

## Core Frameworks

### Framework 1: The Health Score

Before any renewal or expansion conversation, assess account health.
Rate each dimension 1-3 (1=red, 2=yellow, 3=green):

| Dimension | Signal to Measure |
|---|---|
| **Product Usage** | Are they using core features? Frequency trending up or down? |
| **Outcome Achievement** | Are they hitting the KPIs they bought for? |
| **Relationship Depth** | Do you have contacts at multiple levels? |
| **Support Volume** | High ticket volume = friction. Low = either happy or disengaged. |
| **Champion Stability** | Is your main contact still there and still influential? |
| **Expansion Signals** | Are they growing? Hiring? Launching new products? |

**Score Interpretation:**

- 15-18: Healthy. Start expansion conversation.
- 10-14: Neutral. Reinforce value before renewal conversation.
- Below 10: At-risk. Trigger intervention protocol immediately.

---

### Framework 2: The Value Proof Conversation

Never go into a renewal talking about price or contract.
Go in talking about outcomes. Make them re-sell themselves.

**The QBR Structure:**

1. **Look Back:** "Here's what you've accomplished since we started." (Use real data from context hub/KPI dashboard)
2. **Connect to Goals:** "You told us your goal was [X]. Here's where you are against that."
3. **Identify Gaps:** "Here's where there's still room to improve."
4. **Bridge to Next:** "Here's what we'd recommend for the next 6-12 months."

**Rule:** The customer should leave feeling like *they* are the success story,
not that they bought a product. You are a chapter in their growth narrative.

---

### Framework 3: Expansion Timing and Triggers

Expansion conversations work when they solve a problem the customer
is already feeling. Look for these expansion triggers:

**Usage-Based Triggers:**

- Approaching seat/usage limits
- Power users who would benefit from advanced features
- Teams not yet on the platform who could benefit

**Business Triggers:**

- Company announces hiring spree (growth = need)
- Launching a new product line
- Entering a new market
- New executive joins (new priorities = new budget)
- Competitor experiences outage or PR problem

**Relationship Triggers:**

- Champion gets promoted (now has more budget authority)
- New stakeholder joins who has pain your product solves

**Expansion Script:**
"Based on how your team has been using [product], we're seeing
[specific pattern]. Companies at your stage typically find that
[expansion solution] gets them [specific outcome]. Is that something
worth a 20-minute conversation?"

---

### Framework 4: The At-Risk Intervention

If health score drops below 10, do not wait for renewal.
Intervene immediately using this sequence:

**Week 1:** Executive Outreach

- Bypass day-to-day contact. Go directly to the economic buyer.
- Frame: "I want to make sure we're delivering on what we promised."
- Goal: Understand the real problem at the leadership level.

**Week 2:** Root Cause Session

- Get on a call specifically to diagnose. Not to pitch. Not to defend.
- Ask: "If you could change one thing about how you're using [product], what would it be?"
- Listen. Document everything.

**Week 3:** Recovery Plan Delivery

- Present a specific, time-bound plan to fix the identified issue
- Assign owners on both sides
- Set a 30-day check-in to measure progress

**Rule:** An at-risk account that you save becomes your most loyal account.
They know you showed up when it was hard.

---

### Framework 5: Renewal Negotiation

When a customer asks for a discount at renewal:

1. **Never discount without a reason.** Ask: "Help me understand what's driving that."
2. **Trade, don't give.** If you discount, get something: longer term, more seats, a case study, a reference call.
3. **Anchor on value, not price.** "You generated [X outcome] this year. What's the ROI on [contract value]?"
4. **Use the Sandler Takeaway if needed.** "I want to make this work, but I also want to make sure we're the right fit for where you're going. What would make this a clear yes?"

---

## Output Format

When this skill is triggered, the agent will produce:

1. **Account Health Score:** Rated across all 6 dimensions with a total score
2. **Recommended Play:** Renewal, Expansion, or At-Risk Intervention
3. **Value Proof Points:** Specific outcomes to reference in the conversation (pulled from context hub)
4. **Expansion Opportunities:** Identified triggers and which products/tiers apply
5. **Talk Track:** Exact language calibrated to this customer's situation
6. **Risk Flags:** Any signals that could derail the renewal

---

## Guardrails

- Never lock a clearly unhappy customer into a longer contract — it creates a detractor
- Do not promise product features in a renewal that aren't on the roadmap
- Always document renewal conversations in the career asset vault as account wins
- Health score must be updated at least every 30 days — flag if stale
