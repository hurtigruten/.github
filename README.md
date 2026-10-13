# .github

Organization-wide defaults for the [hurtigruten](https://github.com/hurtigruten) GitHub organization.

GitHub uses the files in this repository for every repository in the organization that does not have its own copy. A repository that adds its own file (for example `.github/pull_request_template.md`) uses that instead, for that file only.

| File | Used for |
|------|----------|
| [`profile/README.md`](profile/README.md) | The public organization page at https://github.com/hurtigruten |
| [`SECURITY.md`](SECURITY.md) | The security policy shown in every repository's Security tab |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Contribution guidelines, linked when someone opens an issue or pull request |
| [`.github/pull_request_template.md`](.github/pull_request_template.md) | The default pull request description |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) | The default issue forms |

This repository is public, so everything in it is visible to anyone. Do not add internal links, names or details here.

Changes affect every repository in the organization, so they go through a pull request. The repository settings and branch ruleset are managed in [iac-hurtigruten-github](https://github.com/hurtigruten/iac-hurtigruten-github).
