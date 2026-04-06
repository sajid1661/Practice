# Contributing to Practice

Thank you for your interest in contributing! The following guidelines will help you get started.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Report a Bug](#how-to-report-a-bug)
- [How to Request a Feature](#how-to-request-a-feature)
- [How to Submit a Pull Request](#how-to-submit-a-pull-request)
- [Commit Message Guidelines](#commit-message-guidelines)

## Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this standard. Please report unacceptable behaviour to the maintainers.

## How to Report a Bug

1. Search the [existing issues](https://github.com/sajid1661/Practice/issues) to avoid duplicates.
2. Open a new issue using the **Bug Report** template.
3. Include:
   - A clear and descriptive title.
   - Steps to reproduce the problem.
   - Expected and actual behaviour.
   - Any relevant screenshots or logs.

## How to Request a Feature

1. Search existing issues and discussions to see if the idea has already been proposed.
2. Open a new issue using the **Feature Request** template.
3. Describe the problem your feature would solve and how you envision it working.

## How to Submit a Pull Request

1. **Fork** the repository and create your branch from `main`:

   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes following the existing code style.
3. Write or update tests if applicable.
4. Ensure your branch is up to date with `main` before opening a PR:

   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

5. Open a pull request against the `main` branch and fill in the PR template.
6. Address any review feedback promptly.

## Commit Message Guidelines

Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
<type>(<optional scope>): <short description>

[optional body]

[optional footer(s)]
```

Common types:

| Type       | When to use                                        |
|------------|----------------------------------------------------|
| `feat`     | A new feature                                      |
| `fix`      | A bug fix                                          |
| `docs`     | Documentation changes only                        |
| `style`    | Formatting, missing semicolons, etc. (no logic change) |
| `refactor` | Code change that is neither a fix nor a feature   |
| `test`     | Adding or updating tests                          |
| `chore`    | Build process, dependency updates, tooling        |

Example:

```
feat(readme): add installation instructions
```
