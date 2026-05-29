# blprnt

Template repository for [project description — fill in].

## Usage

Use this as a GitHub template. Click **"Use this template"** above to create a new repo from this skeleton.

### Getting started

```bash
# After generating your repo:
pre-commit install       # install Git hooks (if pre-commit is configured)
```

The repo includes an `AGENTS.md` that instructs opencode agents to read `docs/INDEX.md` first and auto-install `pre-commit` hooks before any commits.

## Structure

- `AGENTS.md` — instructions for opencode agent sessions
- `CLAUDE.md` — general context for opencode
- `docs/` — application spec (authoritative source of truth)
- `src/` — application source code
- `.pre-commit-config.yaml` — pre-commit hook configuration (commented out by default)

## Conventions

- Spec-first: update `docs/` before changing code.
- No generated code committed without a regeneration script.
