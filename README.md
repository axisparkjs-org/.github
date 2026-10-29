# AxiSpark.js/.github

This repository contains the organization's public profile and the default community health files shared by every repository in the [AxiSpark.js organization](https://github.com/axisparkjs).

## Contents

| Path | Description |
| --- | --- |
| [`profile/README.md`](profile/README.md) | Public profile shown on the organization page. |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Contribution guidelines: issues, branching, commit messages and pull requests. |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Code of Conduct, based on the Contributor Covenant 2.1. |
| [`SECURITY.md`](SECURITY.md) | How to report security vulnerabilities privately. |
| [`SUPPORT.md`](SUPPORT.md) | Where to get help. |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) | Issue forms: Fix, Feature, Update and Docs. |
| [`.github/pull_request_template.md`](.github/pull_request_template.md) | Default pull request description. |

## How the defaults work

GitHub uses these files in every repository of the organization that does not define its own file of the same type. Keep in mind:

- A repository's own file always overrides the default one.
- If a repository has any template in `.github/ISSUE_TEMPLATE`, **none** of the default issue templates are used.
- Labels set by the issue templates (`bug`, `feature`, `update`, `documentation`) must exist in this repository and in every repository where the templates are used.
- Repository-specific development steps belong in each repository's `DEVELOPMENT.md`, which `CONTRIBUTING.md` links to.
- `LICENSE`, `CODEOWNERS` and `dependabot.yml` are not inherited and must live in each repository.
