---
name: devflow-retro
description: Review feedback to recommend small, evidence-based improvements to devflow skills. Use only when explicitly called.
---

Review the feedback in `~/.devflow/feedback.md`.

Return for each recommendation:

1. **Observed pattern**
2. **Evidence**
3. **Type**
4. **Recommended action**

Allowed recommendation types:

- No action
- Skill wording change
- Deterministic script candidate
- New skill candidate
- Remove or simplify instruction

Rules:

- Only suggest changes to `devflow-*` skills.
- Prefer no change unless there is repeated evidence.
- Keep skills small and single-purpose.
- If `~/.devflow/feedback.md` is missing, treat it as an empty feedback log and return `No action` based on available evidence.
- If `~/.devflow/feedback.md` is inaccessible, do not fail the workflow; append a concise workflow note when possible and return `No action` based on available evidence.
- Return only the listed sections; no preamble or closing commentary.
- If a workflow issue occurs while using this skill, append a concise note to `~/.devflow/feedback.md`.
