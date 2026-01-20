# Reducing Hallucinations Through Better Prompt Design

Hallucinations often emerge when prompts leave too much room for inference.  
When goals, constraints, or context are underspecified, models may fill gaps with plausible but incorrect information.

This section focuses on how clearer prompt design can reduce those failure modes.

---

## Common prompt patterns that increase hallucination risk

Certain prompt patterns tend to produce unreliable outputs, including:
- Requests for precise facts without context or sources
- Questions that assume information exists when it may not
- Broad prompts that combine multiple goals into one
- Prompts that discourage admitting uncertainty

These patterns increase pressure on the model to guess.

---

## Reducing ambiguity in prompts

Clear prompts reduce hallucinations by:
- Stating what is known versus what is unknown
- Limiting the scope of the response
- Clarifying whether examples, estimates, or explanations are acceptable
- Asking for reasoning or framing instead of final answers when appropriate

Reducing ambiguity narrows the space in which incorrect details can appear.

---

## Allowing the model to signal limits

Prompts that allow a model to acknowledge uncertainty help prevent fabricated details.

This includes:
- Allowing the model to say when information is unavailable
- Encouraging it to flag assumptions
- Inviting it to explain confidence levels or dependencies

This reduces the likelihood of confident but unsupported claims.

---

## Prompting for structure rather than content

In some cases, asking for structure rather than answers is safer.

Examples include:
- Asking for factors to consider instead of conclusions
- Requesting outlines or frameworks rather than specifics
- Focusing on how to approach a problem rather than solve it fully

This approach limits hallucination risk while still providing useful guidance.

---

## Guiding principle

Hallucinations are often a prompt design problem, not just a model problem.

Prompts that reduce pressure to guess and clearly define boundaries lead to more reliable outputs.
