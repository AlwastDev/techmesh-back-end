---
name: Release
about: Release checklist (v0.x)
title: "Release v0.x.y"
labels: ["type:release"]
---

## Gate
- [ ] MVP gate not regressed
- [ ] Tests green (unit/integration)
- [ ] E2E green (frontend Playwright)
- [ ] No critical a11y issues on key screens

## Frontend
- [ ] Bump version
- [ ] Build passes
- [ ] Deploy (if applicable)
- [ ] Tag + Release notes

## Backend
- [ ] Migrations reviewed + applied
- [ ] Integration tests green
- [ ] Deploy (if applicable)

## Notes
- What changed:
- Risks:
- Rollback plan:
