# Contributing

These are the defaults for every True Bearing repository. A repository with its own `CONTRIBUTING.md` overrides this file.

## Workflow

1. Create a branch from `main`: `feature/<task-id>-<short-description>`. Use lowercase unless the task ID comes from an external system.
2. Make the change and run the repository's own checks before pushing (see its README).
3. Commit using Conventional Commits, for example `feat: add reusable plan workflow` or `fix: correct the input name`.
4. Open a pull request. Fill in the template.

## Commits

Conventional Commits drive versioning and changelogs. Allowed types: `feat`, `fix`, `chore`, `docs`, `refactor`, `test`, `ci`, `perf`, `build`. Mark a breaking change with `feat!:` or a `BREAKING CHANGE:` footer.

## Pull requests

- Required checks pass.
- At least one review. Changes to automation or container definitions need a code owner review.
- Keep the change focused. Unrelated cleanups go in their own pull request.
- Never commit secrets, credentials or tokens. If one is committed by mistake, treat it as exposed and rotate it.
