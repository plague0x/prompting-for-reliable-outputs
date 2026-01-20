# Common Prompting Mistakes That Lead to Failure Modes

Many unreliable or unsafe model outputs can be traced back to recurring prompt design mistakes.  
These issues are often subtle and unintentional, but they significantly increase the likelihood of hallucination, misalignment, or overconfidence.

This section highlights common patterns that tend to produce poor outcomes.

---

## Underspecified goals

Prompts that do not clearly state what the user wants often lead models to infer intent.

This can result in:
- responses that miss the actual goal
- overly broad or overly narrow answers
- assumptions that were never intended

Clear goals reduce the need for inference.

---

## Missing or implicit constraints

When constraints are not stated explicitly, models may:
- overreach beyond the intended scope
- include unnecessary or risky details
- provide answers that are technically correct but contextually inappropriate

Relying on the model to “know when to stop” increases failure risk.

---

## Forcing certainty where it does not belong

Prompts that demand definitive answers in ambiguous situations often encourage guessing.

This can lead to:
- speculative details presented as fact
- collapsed possibilities
- omitted caveats or dependencies

Allowing uncertainty is often safer than forcing confidence.

---

## Combining multiple goals in one prompt

Prompts that bundle several objectives together can confuse prioritization.

Common effects include:
- shallow coverage of each goal
- dropped requirements
- inconsistent tone or structure

Breaking complex requests into stages improves reliability.

---

## Treating the first response as final

Assuming the first output is the best or only answer limits correction.

Without iteration:
- misunderstandings persist
- errors go unchallenged
- alignment issues remain unresolved

Prompting works best as a dialogue rather than a single exchange.

---

## Guiding principle

Most prompting failures are communication failures.

Clear intent, explicit constraints, allowance for uncertainty, and thoughtful iteration reduce the likelihood of unreliable outputs.
