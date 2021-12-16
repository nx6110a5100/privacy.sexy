# Pipelines

Pipelines are found under [`.github/workflows`](./../.github/workflows).

## Pipeline types

They are categorized based on their type:

- `tests`:
- `deploy`:
- `checks`:

## Naming conventions

Pipeline files are named using: `<type>.<name-kebab-case>.yaml`.
Sub-folders do not work for GitHub workflows so that's why `<type>.` prefix is used.

Pipeline themselves are named using kebab case.
It allows for easier URL references for their status badges.

E.g. file name `tests.unit.yaml`, pipeline name: `name: unit-tests`

