# Copilot instructions for SPUR Project Placeholder

## About this project

This is the starting repository for the SPUR project. Its purpose, audience, and
technology choices have not been defined yet; do not guess them.

## Project decisions and documents

If project documents are added, follow their agreed order of precedence:

1. `CONCEPT-IDEA.md` — why the project exists and who it is for
2. `SPECIFICATION.md` — what it should do
3. `PLAN.md` — architecture and technical decisions
4. `BACKLOG.md` — the ordered work list

If a request conflicts with an approved project decision, explain the conflict and
ask before proceeding. Mark assumptions clearly; never present them as facts.

## How to work with me

- Explain things in plain language and define technical terms the first time you use them.
- Ask a clarifying question instead of guessing when a request is ambiguous.
- Before running a command, show the exact command and explain in one plain sentence what
  it does. After running it, say what happened and how you checked the result.
- Do not invent facts, statistics, APIs, package names, or citations. Verify them or say
  when you do not know.
- Prefer the simplest solution that satisfies the request. Avoid unrelated changes.
- After a change, explain what changed and how to verify it.
- Point out anything that needs human review before merging.

## Code and safety

- No programming language, framework, or build system has been selected yet. Inspect the
  project and ask before choosing one when it matters.
- Never add secrets, API keys, or tokens to tracked files. Use secure prompts or
  environment variables, and keep local secret files untracked.
- Follow established project conventions once they exist.
