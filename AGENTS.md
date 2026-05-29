# AGENTS.md

## Navigation

Start every session by reading `docs/INDEX.md`. That file is the authoritative entry point for understanding the application's intent, logic, and current state.

Before making any commits, validate that `pre-commit` hooks are installed. If `.pre-commit-config.yaml` exists but hooks aren't active (i.e., no `.git/hooks/pre-commit` or `pre-commit install` hasn't been run), run `pre-commit install`.

## Setup _(run these when first cloning / generating from template)_

- **`pre-commit install`** — installs Git hooks defined in `.pre-commit-config.yaml`. Must be run once before any commits. Run this if hooks aren't active.

## Commands _(will be populated as tooling is added)_

- **build:**
- **test:**
- **lint:**
- **typecheck:**
- **format:**

## Conventions

- Spec-first: update `docs/` before changing code. Code implements the spec.
- No generated code committed without a regeneration script checked in alongside it.
