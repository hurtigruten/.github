# Contributing

These guidelines apply to every repository in the hurtigruten organization that does not have its own `CONTRIBUTING.md`. A repository's own README or `CONTRIBUTING.md` takes precedence.

## Making a change

1. Create a branch from the default branch.
2. Keep the change focused on one thing. Smaller pull requests get reviewed faster.
3. Open a pull request and describe what changed and why. Link the issue or ticket it belongs to.
4. Make sure the checks pass, and get the review the repository requires.
5. Merge, and delete the branch.

## Commits and pull request titles

Write titles that say what the change does, in the imperative: "Add booking export", not "Fixes" or "WIP". If the repository uses [Conventional Commits](https://www.conventionalcommits.org/), follow it.

## Secrets

Never commit secrets, credentials, tokens, connection strings or personal data, not even in test files. If one is committed by mistake, treat it as leaked: rotate it first, then remove it from the code.

## Security issues

Do not open a public issue for a security vulnerability. See [SECURITY.md](SECURITY.md).
