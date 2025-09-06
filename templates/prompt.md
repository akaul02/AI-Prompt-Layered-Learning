# Explain [TOPIC] by progressively increasing the complexity
Choose an effective real-world scenario yourself and use it consistently across all levels.  
Do not ask me for extra inputs; make reasonable assumptions and state them briefly.

# Output structure
1) Chosen scenario (one line)  
2) Levels 0–6  
3) Wrap-up

# Chosen scenario (one line)
- Internally brainstorm 3 candidate scenarios from familiar real-world contexts using these criteria:
  mapping fidelity to [TOPIC], ability to scale from simple to expert, broad familiarity, and measurability (numbers, steps, or rules).
- Output only a single line:
  Chosen scenario: X — because Y

# Level 0 — one-sentence intuition
- A single plain-language sentence that captures the core idea using the chosen scenario.

# Level 1 — explain like I’m 5 (2–3 sentences)
- Very simple words tied to the scenario.
- One core idea only; no jargon.
- Mini-check: one yes/no question.

# Level 2 — middle school (3–5 sentences)
- Describe what it is and why it matters using the scenario.
- Add a tiny concrete example with numbers or counts.
- Introduce at most one simple term and define it in one short sentence.
- Mini-check: one fill-in-the-blank.

# Level 3 — high school (5–7 sentences)
- Explain cause → effect using the scenario.
- Introduce up to two key terms; define each in one short sentence.
- Include one small numeric or step-by-step example.
- Mini-check: one single-choice question.

# Level 4 — university (two short paragraphs)
- Use accurate technical terms; define any new term in ≤1 sentence.
- Show how it works internally via a compact model: a short formula, pseudocode, or stepwise procedure if relevant.
- Provide a worked example with intermediate steps tied to the scenario.
- Add one quick practice variant for the learner.
- Mini-check: ask for a brief calculation or short justification.

# Level 5 — practitioner/implementation (two short paragraphs)
- Translate the concept into practical decisions, parameters, and constraints.
- If relevant, include brief pseudocode, configuration snippets, or parameter choices with defaults and trade-offs.
- Discuss performance, complexity, reliability, observability, or safety metrics as applicable.
- Mini-check: ask the learner to choose a parameter or approach and justify it in one sentence.

# Level 6 — expert/research (2–4 short paragraphs)
- Use precise technical language without re-explaining basics.
- Compare at least two alternative approaches or formulations and specify when to choose each.
- Discuss edge cases, limits of the model, and real-world failure modes.
- If appropriate, include formulas, complexity notes, brief pseudocode, or mention current research directions or open problems.

# Wrap-up
- Recap ladder: one sentence per level that progressively summarizes the concept.
- Pitfalls: three common mistakes or misconceptions.
- Self-quiz: three questions —
  1) conceptual why/what-if,
  2) applied tiny calculation or concrete example,
  3) diagnostic spot the failure mode.

# Assumptions
- If any information is missing, state at most three short assumptions as a single list labeled Assumptions: … and proceed.

# Style rules
- Keep the chosen scenario present at every level.
- Make each level build on the previous one without repeating excessively.
- Use concrete numbers when helpful; keep equations or code minimal and focused, use kotlin syntax.
- Avoid meta-commentary or explaining the prompt or process; output only the explanation.
- Plain headings only; minimal use of tables, no emojis, no excessive formatting.