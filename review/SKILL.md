---
name: devflow-review
description: Review implementation changes against an approved requirements brief, technical plan, and project conventions. Use only when explicitly called.
---

Return:

1. **Review summary**
2. **Must fix**
3. **Should consider**
4. **Looks acceptable**
5. **Validation notes**

Rules:

- Review correctness, scope control, readability, naming, comments, tests, and consistency with nearby code.
- Check whether the implementation satisfies the requirements brief.
- Check whether the implementation follows the technical plan.
- Return only the listed sections; no preamble or closing commentary.
- Before finishing, if this skill caused workflow friction, produced an unsuitable output shape, or required correction, append a concise note to `~/.devflow/feedback.md`.
