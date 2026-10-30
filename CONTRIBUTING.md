# Contributing to AxiSpark.js

We welcome contributions to AxiSpark.js! Whether you're fixing bugs, adding new features, or improving documentation, your help is greatly appreciated. These guidelines apply to every repository in the [AxiSpark.js organization](https://github.com/axisparkjs). Please follow them to ensure a smooth contribution process.

By participating in this project, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Opening an Issue

Every change starts with an issue. Open it from the **Issues → New issue** page of the repository the change belongs to, and choose the template that matches the type of change:

| Template | Use it for | Title prefix | Label |
| --- | --- | --- | --- |
| **Fix** | Bugs or something that is not working as expected | `[Fix]` | `bug` |
| **Feature** | New features | `[Feature]` | `feature` |
| **Update** | Improvements to existing code, tooling or configuration | `[Update]` | `update` |
| **Docs** | Documentation changes | `[Docs]` | `documentation` |

The template sets the title prefix and the label, and asks for the information we need to understand the change. Please check that a similar issue does not exist before opening a new one.

> **Security vulnerabilities must not be reported in public issues.** Follow our [Security Policy](SECURITY.md) instead.

If you have a question or need help using AxiSpark.js, see [Support](SUPPORT.md).

## Submitting a Pull Request

### Development Setup

Each repository describes its own requirements, setup, versioning and testing steps in its `DEVELOPMENT.md` file. Read it before starting to work on a change. In general:

- Fork the repository on GitHub.
- Clone your forked repository to your local machine.
- Follow the setup steps in the repository's `DEVELOPMENT.md`.

### Branching

For each issue, create a new branch from the `main` branch. Start the branch name with the prefix that matches the issue type, followed by a brief description:

| Issue type | Branch prefix | Example |
| --- | --- | --- |
| `[Feature]` | `feature/` | `feature/http-file-upload` |
| `[Fix]` | `fix/` | `fix/login-validation` |
| `[Update]` | `update/` | `update/translate-cli-comments` |
| `[Docs]` | `docs/` | `docs/cli-page` |

`release/` branches are reserved for maintainers to prepare releases.

The documentation lives in its own repository, [axisparkjs/website](https://github.com/axisparkjs/website). A change that needs documentation is usually two pull requests: the code in its repository and the guides in `website`. Link them to each other. The API reference does not need a pull request in `website`, because it is generated from the TSDoc comments of the code.

Make sure to regularly pull the latest changes from the `main` branch to keep your branch up to date.

### Commit Messages

When committing your changes, please use clear and descriptive commit messages. Follow this specification for consistency:

The commit message should start with the type of change (e.g., `fix`, `feat`, `update`, `docs`, `refactor`, etc.) followed by ` (#issue-number): ` and a brief description of the change. Here are some examples:

- `fix (#123): Correct the login validation logic`
- `feat (#456): Add new user profile feature`

### Pull Request Guidelines

When you are ready to submit your changes, create a pull request (PR) from your branch to the `main` branch of the original repository. The description is prefilled with the pull request template: link the issue, list the changes and complete the checklist.

Once your pull request is submitted, it will pass the CI pipeline and be reviewed by the maintainers. Please be responsive to any feedback or requests for changes. We appreciate your contributions and look forward to collaborating with you!
