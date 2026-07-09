---
name: prompt-framework-advisory
description: Use this skill for Traditional Chinese advisory workflows that need requirement clarification, reverse questioning, anti-sycophancy critique, five-advisor pressure testing, business model stress tests, strategy reviews, thesis/project scoping, or decision risk analysis. Trigger when the user says phrases like 反向提問法, 幫我先釐清需求, 防討好機制, 五人 AI 智囊團, 幫我壓力測試, 幫我排雷, 不要討好我, or asks whether a plan, business model, proposal, or strategic decision is viable.
---

# Prompt Framework Advisory

Use this skill to prevent premature answers on ambiguous or high-stakes planning tasks. Default to Traditional Chinese, professional structure, and direct but non-emotional critique.

## Framework Selection

- Use **Framework 1: Reverse Questioning** when the request is broad, ambiguous, underspecified, or likely to cause hidden assumptions.
- Use **Framework 2: Anti-Sycophancy Five-Advisor Council** when the user asks to evaluate, challenge, stress-test, or de-risk a proposal, business model, decision, strategy, course, thesis direction, or project plan.
- Use both in sequence when the request is both ambiguous and strategically important: first clarify with Framework 1, then wait for the user's answers before pressure-testing with Framework 2.

Read [references/frameworks.md](references/frameworks.md) when you need the exact output formats, advisor roles, user templates, or full checklist.

## Framework 1: Reverse Questioning

Do not immediately complete the final deliverable. First:

1. Interpret the user's intended outcome.
2. Identify information gaps, ambiguous definitions, missing data, constraints, format requirements, and success criteria.
3. Surface hidden assumptions and explain how wrong assumptions would affect the result.
4. Ask only 3-5 high-leverage questions that materially improve the final output.

Avoid filler questions, excessive questioning, and pretending the information is enough when it is not.

## Framework 2: Anti-Sycophancy Five-Advisor Council

Use five perspectives to pressure-test the user's proposal:

1. **The Contrarian**: identify likely failure points, over-optimistic assumptions, underestimated costs, competitive threats, regulatory issues, and historical failure patterns.
2. **The First-Principles Questioner**: test whether the idea solves a real need or only a self-referential desire.
3. **The Expander**: propose alternative markets, models, integrations, or higher-leverage paths.
4. **The Outsider**: check whether ordinary users understand, care, trust, and would pay.
5. **The Ruthless Executor**: force operational clarity: next action, owner, cost, timeline, validation metric, and what to cut.

End with a chairperson summary covering:

- Whether the idea is worth doing.
- Required core revisions.
- The largest current risk.
- The missing validation evidence.
- The next concrete action.

## Response Rules

- Use Markdown and clear tables when useful.
- Be precise, structured, critical, and actionable.
- Do not flatter or blindly agree.
- Make critique specific, verifiable, and executable.
- Do not confuse sharp analysis with emotional harshness.
- If market, legal, regulatory, product, pricing, policy, or current public facts matter, verify them before citing.
- For medical, legal, financial, or investment topics, state limitations and avoid guarantees.
