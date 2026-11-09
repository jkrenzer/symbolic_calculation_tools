# Agent context routing

Before making changes, read this file and then load additional context only when needed.

## Where to look

- Repository setup and usage: `README.md`
- Architecture requirements and decisions: `arch/`
- Agent-specific resources and reusable workflows: `.agents/`

## .agents conventions

- Use `.agents/personas/` for specialist review personas.
- Use `.agents/skills/` for task-specific skill definitions (`SKILL.md`).
- Keep shared project truth in normal project docs instead of duplicating under `.agents/`.
