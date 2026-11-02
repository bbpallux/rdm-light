# RDM Light – Implementation Agent Rules

This is the **public application repository**. It is reserved for implementation.

## Source of truth

All product analysis and design specifications live in the private repository:
https://github.com/bbpallux/rdm-light-ai

Before changing code, consult the relevant specifications there, especially:
- `project/PROJECT_CONTEXT.md`
- `project/ROADMAP.md`
- `project/BACKLOG.md`
- `project/OPEN_QUESTIONS.md`
- relevant architecture documents and ADRs
- `project/AGENTS.md` and `agents/AGENTS.md`

## Repository boundary

- Use this repository for application source code, tests, migrations, runtime/build configuration, container files and concise implementation-facing documentation.
- Do not perform or store product analysis, requirements definition, architecture proposals, ADRs, security specifications, roadmap or backlog management here.
- Do not copy private analysis/specification documents into this public repository.
- If implementation uncovers a missing or contradictory requirement, pause implementation and resolve the specification in the private `rdm-light-ai` repository first. Implement only after the decision is clear.
- Keep branches and commits in the two repositories independent; never assume matching branch names or commit histories.

## Implementation quality

- Inspect the existing code and relevant private specifications before editing.
- Keep changes focused and readable; avoid unrelated refactoring.
- Keep UI styling, themes and design tokens separate from application logic.
- Never commit secrets, credentials, private keys or real environment files.
- Run relevant tests, linting and formatting before reporting completion.
- Do not merge pull requests, delete branches or rewrite history without explicit approval.
- At completion, report changed files, tests/validation, and any remaining limitations.
