# Skill: champion-building

**Module:** sales-skills
**Version:** 1.0
**Reads From:** `.agents/product-marketing-context.md`, `../job-os/PEOPLE-AND-POLITICS-MAP.md`
**Triggered By:** `/champion`, `/internal-sell`, `/stakeholder`

---

## What This Skill Does

Most deals die not because the buyer said no — but because no one inside the account
fought for you when you weren't in the room.

This skill identifies, develops, and activates internal champions: the people inside
a prospect or customer account who will sell on your behalf to their own leadership.

Drawn from *The Challenger Customer* (Adamson & Dixon) and Winning by Design's
account mobilization frameworks.

---

## When To Trigger This Skill

- Deal has gone quiet after a good demo
- You're stuck talking to the wrong level (too low or too high)
- "I need to get buy-in from my team" response received
- Multi-stakeholder deal with no clear internal advocate
- Renewal at risk because your contact has lost internal influence
- You suspect a competitor is already talking to someone else in the account

---

## Core Concepts

### Concept 1: The Champion vs. The Coach

These are different people. Do not confuse them.

| | Champion | Coach |
|---|---|---|
| **Definition** | Has organizational power AND wants you to win | Gives you intel but can't or won't fight for you |
| **Value** | Sells internally when you're not there | Helps you navigate, but can't close |
| **Risk** | If they leave, deal is at risk | Low risk — they're informational only |
| **Action** | Invest heavily. Enable them. | Extract intel. Don't over-rely. |

**Rule:** A coach is not a champion. Confirm before you invest.

---

### Concept 2: Champion Identification Criteria (MEDDICC)

A true champion must pass all 3 tests:

1. **Power:** Do they have or directly influence budget authority?
2. **Motivation:** Do they have a personal stake in this working? (Career upside, pain relief, visibility)
3. **Willingness:** Have they actively done something to help you? (Set up a meeting, shared internal data, cc'd their boss)

**Litmus test question to ask yourself:**
"Has this person done anything for this deal that could get them in trouble if it fails?"
If yes → Champion. If no → Coach.

---

### Concept 3: Mobilizer Types (Challenger Customer)

Not all internal influencers are equal. Identify which type your champion is:

- **The Go-Getter:** Motivated by new ideas and organizational improvement. Sell them on vision.
- **The Teacher:** Wants to educate their colleagues. Give them insights and data to share.
- **The Skeptic:** Questions everything. Win them and they become your most powerful advocate.
- **The Guide:** Shares inside information freely. Valuable coach, rarely a champion.
- **The Friend:** Likes you personally. Dangerous over-reliance risk.
- **The Climber:** Motivated by personal advancement. Frame your solution as their win.

**Highest-value target:** The Skeptic. Hardest to win, most credible internally.

---

### Concept 4: Champion Enablement

Once identified, your job is to make it easy for them to sell for you.

**Give them:**

- A one-slide internal business case they can forward to their CFO/CEO
- The 3 objections their colleagues will raise and how to answer them
- ROI numbers specific to their company size and use case (pull from context hub)
- A clear "ask" — what exactly do you need them to do next?

**Script to activate them:**
"I know you're aligned on this. The part I can't control is the internal conversation
after I leave the room. Can I help you prepare for that? What are the 2-3 concerns
you think [their boss/CFO/committee] will raise?"

---

### Concept 5: Multi-Threading

Never rely on a single champion. Map and connect with at least 3 stakeholders.

**The Multi-Thread Map:**

```
Economic Buyer (signs the check)
        ↑
Champion (your advocate)     ← YOU MUST HAVE THIS
        ↑
End User (day-to-day user)
        +
Technical Buyer (IT/Security/Legal)
```

**Rule:** If your champion leaves the company, your deal should not die.
If it would, you are single-threaded. Fix it immediately.

---

## Output Format

When this skill is triggered, the agent will produce:

1. **Stakeholder Map:** Current contacts in the account and their classification (Champion/Coach/Blocker/Unknown)
2. **Champion Score:** Does your current contact pass the 3-part champion test?
3. **Mobilizer Type:** Which type are they and how should you engage them?
4. **Enablement Package:** Exactly what to give them to sell internally
5. **Multi-Thread Gap:** Who else in the account you need to connect with
6. **Next Action:** The one thing to do in the next 48 hours

---

## Guardrails

- Do not share sensitive competitive information with a champion — it can leak
- Do not coach a champion to mislead their own colleagues
- If champion leaves the account, immediately re-run this skill for the account
- Cross-reference with `PEOPLE-AND-POLITICS-MAP.md` for any known internal dynamics
