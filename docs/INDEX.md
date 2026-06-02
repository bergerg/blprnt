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

Each feature lives under `docs/features/<feature-name>/FEATURE.md`. Every new feature must be registered here as a link with a one-line purpose. You may optionally add a `BDD.md` alongside with Given-When-Then scenarios (see [TEMPLATE.md](./features/TEMPLATE.md)).

- _List features here as they are created._

## Use Cases

Each use case lives under `docs/use-cases/<use-case-name>/USE_CASE.md`. Use cases describe an actor achieving a goal by composing multiple features. Every use case must be registered here as a link with a one-line description. You may optionally add a `BDD.md` alongside with Given-When-Then scenarios (see [TEMPLATE.md](./use-cases/TEMPLATE.md)).

- _List use cases here as they are created._

## How to add a new feature

1. Copy `docs/features/TEMPLATE.md` to `docs/features/<feature-name>/FEATURE.md`.
2. Fill in the template sections.
3. Add a link and one-line purpose to the Features section above.
4. If the new feature changes the overall plan, update this INDEX.md summary.

## How to add a new use case

1. Copy `docs/use-cases/TEMPLATE.md` to `docs/use-cases/<use-case-name>/USE_CASE.md`.
2. Fill in the template sections.
3. Add a link and one-line description to the Use Cases section above.
4. Link to the features it composes under **Related features**.

## How to add a new dependency

1. Copy `docs/dependencies/TEMPLATE.md` to `docs/dependencies/<dependency-name>/DEPENDENCY.md`.
2. Fill in the template sections.
