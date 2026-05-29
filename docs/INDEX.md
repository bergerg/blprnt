# Application Spec

This directory defines the application — its intent, logic, and design — in a set of markdown documents that are the authoritative source of truth. Every agent session should start here.

## Working with this directory

- **Read `INDEX.md` (this file) first** every session to understand current state.
- See [STACK.md](./STACK.md) for the current tech stack choices.
- See [dependencies/](./dependencies/) for external infrastructure requirements.
- Documents are ordered and cross-reference each other.
- Before writing code, ensure the relevant spec doc is up to date. Code implements the spec, not the other way around.
- When scope changes, update the spec first, then code.

## Features

Each feature lives under `docs/features/<feature-name>/FEATURE.md`. Every new feature must be registered here as a link with a one-line purpose.

- _List features here as they are created._

## How to add a new feature

1. Copy `docs/features/TEMPLATE.md` to `docs/features/<feature-name>/FEATURE.md`.
2. Fill in the template sections.
3. Add a link and one-line purpose to the Features section above.
4. If the new feature changes the overall plan, update this INDEX.md summary.

## How to add a new dependency

1. Copy `docs/dependencies/TEMPLATE.md` to `docs/dependencies/<dependency-name>/DEPENDENCY.md`.
2. Fill in the template sections.
