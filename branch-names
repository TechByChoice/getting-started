# OpenTBC Branching Strategy

Welcome to the OpenTBC organization. This document outlines our branching strategy that supports our workflows, collaboration, code quality. To keep us organized we're using [Linear](https://linear.app) for product management! Linear helps ceates our branch namings, because devs don't like to name things 😂.

## Overview

Our branching strategy is centered around the Linear-GitHub integration, using branch numbers created by Linear as our branch names. This approach ensures a tight coupling between our code changes and the tasks or features they relate to, simplifying tracking and review processes.

## Branching Workflow

### Main Branch

- `main`: The primary branch where the source code always reflects a production-ready state.

### Feature Branches

- Branch Naming: Each branch created for a new feature or bug fix is named using the Linear issue ID (TBC-111), ensuring direct traceability between the task in Linear and the corresponding code changes in GitHub.
- Creation: When a new task is assigned and moved to the "In Progress" state in Linear, a new branch is created from the `main` branch using the format `LIN-<issue_number>`, where `<issue_number>` is the ID assigned by Linear.

### Pull Requests (PR)

- Upon completion of work on a feature branch, a pull request is created targeting the `main` branch.
- The PR title should clearly describe the feature or fix, including the Linear issue ID for reference.
- PRs are reviewed by the team, ensuring code quality, adherence to project standards, and if there's any teaching moments this is where it happens!

### Merging Strategy

- After a PR is approved, it is squash and merge into the `main` branch.
- Once merged the Linear issue associated with the merged PR is automatically marked as compelte and you're good to go!

## Best Practices

- **Branch Up-to-Date**: Regularly rebase feature branches with the latest changes from the `main` branch to minimize merge conflicts.
- **Small, Focused Changes**: Keep branches focused on a single feature or fix to streamline reviews and reduce integration complexity.
- **Commit Messages**: Write clear, concise commit messages, including the Linear issue ID for easy reference.

## Getting Started

To start contributing, please ensure you're familiar with Linear and our project's workflow. If you're new to Linear, [this guide](https://linear.app/docs) provides a comprehensive introduction.

## Questions?

If you have any questions about our branching strategy or need assistance with Linear, please reach out to our project team via Tech by Choice Slack in the #team-open-source channel.

Thank you for contributing to OpenTBC projects. Together, we're making tech a better place!

