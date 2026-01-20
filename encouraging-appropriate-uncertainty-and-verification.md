# Encouraging Appropriate Uncertainty and Verification

Not all questions have a single, definitive answer.  
When prompts implicitly demand certainty, models may respond with confidence even when information is incomplete, ambiguous, or context-dependent.

This section focuses on prompt framing that allows uncertainty where it is appropriate and encourages verification rather than overconfidence.

---

## When uncertainty is the safer outcome

Uncertainty is often appropriate in cases involving:
- incomplete or missing information
- rapidly changing facts
- ambiguous scenarios or edge cases
- subjective interpretation

In these situations, a careful response is often more reliable than a definitive one.

---

## Allowing uncertainty in prompt framing

Prompts can explicitly allow uncertainty by:
- inviting multiple possibilities instead of a single conclusion
- asking the model to state assumptions
- allowing the model to say when information is unavailable
- requesting confidence ranges or dependencies

This reduces pressure on the model to guess.

---

## Encouraging verification and follow-up

Good prompt design can also guide models toward safer next steps.

This includes prompting for:
- ways information could be verified
- signals or sources a user might check
- clarifying questions that would improve accuracy
- conditions under which the answer might change

Verification framing helps prevent users from treating outputs as final or authoritative when they should not be.

---

## Common failure patterns when uncertainty is discouraged

When prompts discourage uncertainty, models may:
- present speculation as fact
- collapse multiple possibilities into one answer
- omit important caveats
- overstate confidence in edge cases

These failures are often driven by prompt framing rather than model capability.

---

## Guiding principle

Reliable prompts make it safe for a model to say:
- “It depends”
- “There isn’t enough information”
- “Here are a few possibilities”

Allowing appropriate uncertainty reduces the risk of confident but incorrect outputs.
