# Contributing & Workflow

## Branching
- `main`: stable, portfolio-ready
- `dev`: active work
Create short-lived feature branches from `dev`, then merge via PR.

## Commit Messages (Conventional Commits)
- `feat: add churn baseline model`
- `fix: handle nulls in preprocessing`
- `docs: update project README`

## Code Style
- Format with `black`
- Lint with `ruff` (optional)

## Data
- Never push raw/confidential data.
- Put sample data under `data/sample/` only if needed.