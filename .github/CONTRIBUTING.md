# Contributing to Krow

Thank you for your interest in contributing to Krow.

This document outlines our development workflow, expectations, and review process. Following these guidelines helps us maintain code quality and respond to contributions efficiently.

## Code of Conduct

By participating, you agree to uphold our [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## Getting Started

### Prerequisites

- Familiarity with the project's primary languages and frameworks.
- A GitHub account with [two-factor authentication](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa) enabled.
- Git installed and configured locally.

### Finding Work

- Browse [open issues](https://github.com/krowft/Krow/issues) for areas marked `good first issue` or `help wanted`.
- Discuss larger changes in a GitHub Issue before beginning implementation.
- Review our public roadmap and focus areas to ensure alignment.

## Development Workflow

1. **Fork the repository.**
2. **Create a feature branch** from `main`.
3. **Make your changes** following our coding standards.
4. **Run tests and linting** before committing.
5. **Submit a pull request** to `main`.

## Branch Naming

Use the following convention:

```
<type>/<description>
```

Examples:

- `feat/add-cli-install-command`
- `fix/crash-on-empty-input`
- `docs/update-readme-badges`
- `chore/upgrade-dependencies`

Accepted types:

| Type | Description |
| --- | --- |
| `feat` | New feature or functionality |
| `fix` | Bug fix |
| `docs` | Documentation changes |
| `refactor` | Code change that neither fixes a bug nor adds a feature |
| `test` | Adding or updating tests |
| `chore` | Build process, dependencies, or tooling |
| `ci` | CI/CD pipeline changes |

## Commit Conventions

We use [Conventional Commits](https://www.conventionalcommits.org/) to maintain a readable history.

Format:

```
<type>(<scope>): <description>
```

Examples:

```
feat(cli): add --watch flag for development
fix(auth): handle expired token refresh
docs(readme): update installation instructions
refactor(utils): simplify date parsing logic
```

Rules:

- Use the imperative mood (`add` not `added` or `adds`).
- Keep the description under 72 characters.
- Use the body to explain the motivation and context when necessary.
- Reference issues in the body with `Fixes #123` or `Closes #456`.

## Pull Requests

### Before Submitting

- Ensure your branch is up to date with `main`.
- Run the full test suite and linting.
- Update documentation if your change affects behaviour, APIs, or user-facing surfaces.
- Add tests for new behaviour or bug fixes.
- Keep PRs focused. One logical change per pull request.

### PR Description

A good PR description includes:

- **What** — A concise summary of the change.
- **Why** — The motivation or problem being solved.
- **How** — A brief overview of the implementation approach.
- **Testing** — Steps to reproduce or validate the change.
- **Screenshots** — If the change affects UI or output.

Use the [PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md) to structure your submission.

### Review Process

- At least one maintainer review is required before merge.
- Reviews are expected within a few business days.
- Address all comments and requested changes.
- Once approved, a maintainer will merge and squash commits.

## Code Quality

- Linting must pass before merge.
- Type safety is preferred where the project language supports it.
- Avoid unnecessary dependencies. Every dependency is a commitment.
- Write code that is readable by humans first, optimised by compilers or runtimes second.
- Delete dead code. Comments should explain why, not what.

## Documentation

- Update the README or relevant docs when behaviour changes.
- Add inline comments only when the code alone is not self-explanatory.
- Keep examples in documentation tested and up to date.

## Community Behaviour

We are committed to providing a welcoming experience for everyone. Please:

- Be patient and respectful in discussions.
- Assume positive intent.
- Accept constructive feedback gracefully.
- Focus on what is best for the community.

Harassment, discrimination, or abusive behaviour will not be tolerated. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for the full policy.

## Questions

If you have questions about contributing, reach out through:

- [GitHub Issues](https://github.com/krowft/Krow/issues)
- [Discord](https://discord.gg/aa3HPzyVv)
- Our [website](https://krow-mocha.vercel.app/)

Thank you for contributing to Krow.
