---
name: devflow-plan
description: Convert an approved requirements brief into a technical plan. Use only when explicitly called.
---

Return:

1. **Relevant context**
2. **Proposed approach**
3. **Files likely to change**
4. **Tests / checks**
5. **Risks or open questions**

Rules:

- Keep the technical plan concise.
- Do not broaden the scope of the brief.
- Inspect only repository files needed for this plan.
- Prefer existing project conventions over new patterns.
- Return only the listed sections; no preamble or closing commentary.
- If a workflow issue occurs while using this skill, append a concise note to `~/.devflow/feedback.md`.
