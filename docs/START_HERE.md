# START HERE — Setup & Rules

## Setup
```bash
uv venv && uv pip install -r requirements.txt
make run
make eval
```

## Cursor Rule
Use the rule: **“Certification Challenge — Evidence Map & Slide Generator (v4)”**

Generates:
- `/deliverables/CERT_CHECKLIST.md`
- `/deliverables/CERT_SLIDES.md` (9 slides: intro, 1/task, conclusion)

Do **not** edit README — all content lives in `/deliverables/`.

## Quick Reference
| Command | Purpose |
|----------|----------|
| `make run` | Run Flask app |
| `make eval` | Run evaluation harness |
| `make checklist` | Generate checklist (Cursor) |
| `make slides` | Generate slides (Cursor) |
