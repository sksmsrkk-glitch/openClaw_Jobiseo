# Claude Session Rules for JOBISEO Workspace

This directory provides Claude-compatible session guidance benchmarked from Issac's other repositories and adapted for the JOBISEO workspace.

## Session Intent

Keep the repo's behavior, documentation, and workflow rules consistent across agent tools.

## Mandatory Session Priorities

1. Accuracy first.
2. Important matters require very careful review.
3. Then optimize for speed.

## Mandatory Read Order

Before making meaningful repo changes, inspect:

1. `../AGENTS.md`
2. `../SOUL.md`
3. `../USER.md`
4. `../README.md`
5. relevant skill file in `./skills/`

## Core Rules

- Read before editing.
- Preserve existing useful content unless intentionally replacing it.
- Do not invent facts about repo state.
- Prefer the smallest stable change.
- Verify before claiming success.
- Keep public-repo safety in mind at all times.

## Skills

Use the skill files in `./skills/` as task-focused operating prompts.

- `jobiseo_init.skill.yaml`
- `workspace_docs.skill.yaml`
- `repo_hygiene.skill.yaml`
- `verification_agent.skill.yaml`
