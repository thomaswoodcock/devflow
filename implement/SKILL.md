---
name: devflow-implement
description: Implement an approved technical plan. Use only when explicitly called.
---

Return:

1. **Summary of changes**
2. **Files changed**
3. **Tests / checks run**
4. **Deviations from the plan**
5. **Remaining risks or follow-up**

Rules:

- Do not broaden the scope of the technical plan without approval.
- Keep the diff as small as practical.
- Write readable, maintainable code: prefer clear names and simple structure; add comments only where intent or non-obvious reasoning is not clear from the code.
- Be test-aware: add or update tests before or alongside implementation where practical.
- Return only the listed sections; no preamble or closing commentary.
- Before finishing, if this skill caused workflow friction, produced an unsuitable output shape, or required correction, append a concise note to `~/.devflow/feedback.md`.
