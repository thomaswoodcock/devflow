# devflow

Small AI agent skills for a development workflow.

## Principles

- Keep skills small and single-purpose.
- Use skills explicitly.
- Move through the workflow in gated steps: brief, plan, implement, review.
- Do not broaden approved scope without approval.
- Record workflow issues so real usage can drive improvements.
- Improve skills only through retrospective review, not during normal workflow.
- Prefer deterministic scripts only when feedback shows a repeated, mechanical issue.

## Skills

- `devflow-brief` — convert development input into a requirements brief.
- `devflow-plan` — convert an approved requirements brief into a technical plan.
- `devflow-implement` — implement an approved technical plan.
- `devflow-review` — review implementation changes against an approved requirements brief and technical plan.
- `devflow-retro` — review workflow feedback and suggest improvements.

All skills record workflow issues in:

```text
~/.devflow/feedback.md
```
