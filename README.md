# Renovate Config

This is a global config for Lido organization.

- Stability days - create a PR only after 5 days after package update
- PR creation only after tests
- Schedule for common work hours
- Concurrent open PR limit of 5
- 2 PRs are created at most in an hour
- Labels to easily distinguish between created PRs eg deps or security updates

## Vulnerability Fixes

For fixable vulnerabilities (eg exists a new version with a fix), a PR is submitted automatically.

Dependabot functionality has to be partly enabled in Repo Settings - Security - Code security and analysis:
- Dependency graph
- Dependabot alerts

## Dependency Grouping

- Dev dependencies
- @lido-sdk/*
- @ethersproject/*
- @types/*
- eslint

Feel free to submit a PR to group more of your dependencies.
