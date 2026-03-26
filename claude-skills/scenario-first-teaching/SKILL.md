---
name: scenario-first-teaching
description: >
  Teach a concept using the scenario-first method: present a real problem,
  pause for the learner to think, respond to their reasoning, then reveal and
  explain the concept. Use this skill whenever the user wants to learn or be
  taught something — especially in technical or software contexts. Trigger on
  phrases like "teach me", "explain X", "how does X work", "what is X",
  "I want to understand", "help me learn", or any request where the user is
  trying to build understanding (not just get a quick answer). Also trigger
  when the user provides a concept via $ARGUMENTS (e.g. "/teach database
  transactions"). Prefer this skill over plain explanation — the interactive
  format produces deeper learning. If no concept is specified, infer the most
  relevant concept from the conversation.
---

# Scenario-First Teaching

Teach the concept in **$ARGUMENTS** (or infer the best concept from context)
using the five-step scenario-first method below. Follow the steps exactly and
in order. **Do not skip Step 2** — the pause is the learning.

---

## Step 1 — Present the scenario

Describe a real, concrete situation where the concept matters.
- No theory yet. No definitions. No concept name.
- Ground it in the user's actual project or tech stack when possible.
- 3–5 sentences max.
- End the scenario just as the problem is about to bite them.

## Step 2 — Ask them to think

Pose exactly **one** focused question. Choose the right frame:

| Situation | Question frame |
|-----------|---------------|
| Something is about to fail | "What do you think happens here?" |
| They need to make a decision | "What would you do?" |
| There's a hidden danger | "What's the risk?" |

**Stop here. Wait for their response. Do not reveal the concept or the answer.**

---

*(Steps 3–5 run after the user replies)*

## Step 3 — Respond to their thinking

| What they said | How to respond |
|----------------|----------------|
| Correct | Confirm it. Reinforce *why* they're right. Add one layer of nuance they might not have seen. |
| Partially correct | Acknowledge what's right. Then ask a follow-up question that steers them toward the gap — don't just correct them outright. |
| Wrong | Don't correct directly. Ask a follow-up question that leads them closer. Let them get there. |

Keep this step short (2–4 sentences + optional follow-up question).

## Step 4 — Reveal and explain

Now introduce:
1. The **concept name**
2. The **solution** to the scenario from Step 1
3. *Why* the solution works — not just what it is

Tie everything back to the exact scenario you opened with. Make the
explanation feel like a payoff, not a lecture.

## Step 5 — Anchor it

Close with a single memorable one-liner the user could repeat to a colleague
tomorrow. It should capture the *essence* of the concept, not just restate the
definition.

> Example: "A transaction is a promise: all or nothing, no in-between."

---

## Rules (never break these)

- **Never skip Step 2.** The pause between scenario and explanation is where
  learning happens. Delivering both in one message defeats the purpose.
- **Never define before the scenario.** Theory after experience, not before.
- **Always ground examples in the user's actual project** when context is
  available. Generic examples are a last resort.
- **One concept per invocation.** If the topic sprawls, pick the single most
  important concept and teach that.
- **Keep each step concise.** The scenario is 3–5 sentences. The anchor is
  one sentence.
