# Framing Clear Goals and Constraints

Many model failures trace back to unclear or underspecified prompts.  
When goals and constraints are vague, models tend to fill in gaps with assumptions, which increases the risk of hallucination or misalignment.

This section focuses on how clear framing improves reliability.

---

## Defining the goal

A useful prompt makes the intended outcome explicit.

Instead of assuming the model will infer what is wanted, I look for prompts that clearly answer:
- What is the user trying to achieve?
- What kind of response is expected (explanation, summary, comparison, etc.)?
- Who is the intended audience?

Clear goals reduce guesswork and narrow the space of possible responses.

---

## Setting constraints

Constraints help prevent scope drift and overreach.

Common constraints include:
- Level of detail (high-level vs. detailed)
- Allowed assumptions
- Timeframe or context limits
- Output format or structure
- Whether uncertainty should be surfaced

Explicit constraints are especially important for ambiguous or open-ended requests.

---

## What happens when constraints are missing

When constraints are not stated, models may:
- Overgeneralize or overspecify details
- Present guesses as facts
- Drift into adjacent but unintended topics
- Provide information that is technically correct but contextually wrong

These issues are often prompt-related rather than model capability issues.

---

## Encouraging appropriate uncertainty

In some cases, the goal is not a definitive answer but a careful one.

Prompts that allow or encourage uncertainty help models:
- Signal limits in knowledge
- Offer multiple possibilities rather than a single claim
- Suggest verification or next steps

This reduces the risk of confident but unsupported outputs.

---

## Guiding principle

Clear goals define *what* the model should do.  
Clear constraints define *where it should stop*.

Reliable outputs depend on both.
