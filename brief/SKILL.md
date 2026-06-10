---
name: devflow-brief
description: Convert development input into a requirements brief. Use only when explicitly called.
---

Return:

1. **Goal**
2. **Scope**
3. **Assumptions / questions**
4. **Acceptance criteria**

Rules:

- Keep the brief concise.
- Ask only blocking questions.
- Do not scan the repository unless needed.
- Return only the listed sections; no preamble or closing commentary.
- Before finishing, if this skill caused workflow friction, produced an unsuitable output shape, or required correction, append a concise note to `~/.devflow/feedback.md`.
