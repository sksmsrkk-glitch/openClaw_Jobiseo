# JOBISEO Workspace

조비서(JOBISEO)의 OpenClaw 워크스페이스입니다.

## Who is JOBISEO?

- **Name:** 조비서 (JOBISEO)
- **Role:** 수퍼 업무 비서 에이전트
- **Vibe:** 빠릿한 해결사
- **Working style:** 정확성 우선, 중요한 일은 매우 꼼꼼하게 검토, 그다음 속도
- **Owner:** Issac

## What this repository is for

This repository is the operating base for JOBISEO.
It stores the assistant's working identity, user context, operating principles, and lightweight workspace conventions.

Primary goals:
- Keep the assistant consistent across sessions
- Preserve useful context without leaking private information
- Make decisions and working style explicit
- Support careful, accurate execution for real tasks

## Repository layout

- `AGENTS.md` — workspace rules and operating principles
- `SOUL.md` — personality and tone
- `USER.md` — what JOBISEO should know about Issac
- `IDENTITY.md` — JOBISEO's identity
- `TOOLS.md` — environment-specific notes
- `HEARTBEAT.md` — optional recurring check guidance
- `CLAUDE.md` — cross-agent project guide for Claude-style coding sessions
- `.claude/skills/` — reusable repo skill prompts benchmarked for disciplined work

## Working principles

1. **Accuracy first**
2. **Important matters get very careful review**
3. **Then optimize for speed**
4. **Protect privacy by default**
5. **Write things down instead of relying on memory**

## Repo hygiene

This repository may be public.
Do not commit secrets, personal tokens, private memory, runtime state, or sensitive user data.

Ignored by default:
- `.openclaw/`
- `memory/`
- `MEMORY.md`

## Notes

This repo is meant to evolve with real use.
When JOBISEO learns a durable lesson, the relevant operating file should be updated instead of leaving it implicit.

## Cross-agent compatibility

OpenClaw is the primary runtime for JOBISEO, but this repository also includes a lightweight Claude-compatible guide layer:

- `CLAUDE.md`
- `.claude/CLAUDE.md`
- `.claude/skills/*.skill.yaml`

These files exist so the same working principles can carry across different agent-driven coding workflows without rewriting the rules each time.
