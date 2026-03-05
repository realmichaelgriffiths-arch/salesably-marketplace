# Skill: negotiation-closing

**Module:** sales-skills
**Version:** 1.0
**Reads From:** `.agents/product-marketing-context.md`
**Triggered By:** `/close`, `/negotiate`, `/objection`

---

## What This Skill Does

This skill turns stalled, objecting, or hesitant prospects into closed deals.
It applies battle-tested negotiation frameworks — drawn from Chris Voss (Never Split the Difference),
Neil Rackham (SPIN Selling), and the Sandler methodology — adapted for B2B sales execution.

It does NOT use pressure tactics. It uses precision: the right question, the right silence,
the right frame at the right moment.

---

## When To Trigger This Skill

- Prospect says "I need to think about it"
- Prospect goes cold after a strong demo
- Budget objection is raised
- "Send me a proposal" (stall tactic)
- End of quarter deal acceleration needed
- Prospect is comparing you to a competitor

---

## Core Frameworks

### Framework 1: Tactical Empathy (Voss)

Make the prospect feel understood BEFORE you try to move them.
Never counter-argue until they feel heard.

**Steps:**

1. Mirror their last 2-3 words back as a question
2. Label the emotion underneath with "It seems like..." or "It sounds like..."
3. Pause. Let them correct or confirm.
4. Only proceed once tension drops.

**Example:**

- Prospect: "We already have a tool for that."
- Agent Output: "You already have a tool for that. It sounds like switching feels risky right now — is that fair?"

---

### Framework 2: Calibrated Questions (Voss)

Replace statements and pushback with open "How" and "What" questions.
These force the prospect to problem-solve with you instead of against you.

**Power Questions:**

- "What would need to be true for this to make sense for your team?"
- "How would you see this fitting into your current workflow?"
- "What's the biggest risk you see with moving forward?"
- "How are you currently solving for [pain point from context hub]?"

**Rule:** Never ask a "Why" question. It sounds accusatory.
Always ask "What" or "How."

---

### Framework 3: The Accusation Audit (Voss)

Before the prospect raises objections, name them yourself.
This disarms defensiveness and builds trust.

**Structure:**
"I'm sure you're thinking [their likely objection]. And honestly, that's a fair concern..."

**Example using context hub data:**
If your product is premium-priced:
"I'm sure you're wondering whether this is worth the investment compared to [Competitor from context hub].
That's exactly what [similar customer type] thought before they saw [specific result]."

---

### Framework 4: SPIN Closing (Rackham)

Don't pitch features. Lead them to articulate their own pain and the cost of inaction.

**Question Sequence:**

1. **Situation:** "Walk me through how you're currently handling [problem area]."
2. **Problem:** "Where does that break down for you?"
3. **Implication:** "What happens to [metric] when that breaks down?"
4. **Need-Payoff:** "If you could fix that, what would that mean for the team?"

**Rule:** The prospect should be talking 70% of the time during this sequence.
Your job is to ask, not tell.

---

### Framework 5: The Sandler Takeaway

When a prospect stalls, pull back instead of pushing forward.
Scarcity and detachment are more powerful than pressure.

**Script:**
"Honestly, based on what you've told me, I'm not sure this is the right fit right now.
I'd rather you not move forward than commit to something that doesn't work for you.
What would need to change for the timing to be right?"

**Why it works:** It removes the salesperson dynamic. They stop resisting
and start telling you the real objection.

---

### Framework 6: The Final Close

When all objections are addressed and you need a decision:

"Based on everything we've discussed, is there any reason we shouldn't move forward?"

If yes → return to Framework 1 (Tactical Empathy)
If no → "Great. Let's get the paperwork started. I'll send it over today."

---

## Output Format

When this skill is triggered, the agent will produce:

1. **Situation Read:** What objection/stage is this prospect at?
2. **Recommended Framework:** Which of the above applies?
3. **Exact Script:** Word-for-word language calibrated to this prospect using context hub data
4. **What Not To Say:** Common mistakes to avoid in this specific situation
5. **Next Step:** The one clear action to take after this interaction

---

## Guardrails

- Never fabricate product capabilities to close a deal
- Never manufacture urgency that doesn't exist
- If prospect is genuinely not a fit, flag it — a bad close creates a churn problem later
- All scripts must be checked against `product-marketing-context.md` before output
