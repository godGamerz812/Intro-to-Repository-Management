# Intro to Repository Management

This repository demonstrates practical GitHub repository-management practices for collaborative projects.

## Goals

- Protect the default branch and repository content.
- Document clear contribution and review procedures.
- Assign responsibility for reviewing code.
- Set respectful community expectations.
- Establish a process for reporting security issues.
- Explain the differences between personal and organization-owned repositories.

## Collaboration workflow

1. Create a feature branch for each change.
2. Keep pull requests focused and describe the reason for each change.
3. Test changes and provide evidence when appropriate.
4. Review changes before merging.
5. Resolve review discussions before merging.
6. Never commit credentials, access tokens, private data, or secrets.

## Repository guidance

- [Contributing guidelines](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Security policy](SECURITY.md)
- [Code owners](.github/CODEOWNERS)
- [Pull request template](.github/pull_request_template.md)
- [Bug report template](.github/ISSUE_TEMPLATE/bug_report.md)
- [Feature request template](.github/ISSUE_TEMPLATE/feature_request.md)

## Personal and organization repositories

In a personal repository, the owner manages settings and reviews. In an organization repository, teams can share responsibility and code ownership. Organization teams are preferable when several maintainers need stable review responsibilities.

## Important: enable branch rules in GitHub settings

The files in this repository document the workflow, but they do not enforce server-side protection by themselves. Open **Settings → Rules → Rulesets** (or **Settings → Branches**) and create a ruleset targeting `main`. When available, require pull requests before merging, require an approval, require conversation resolution, block force pushes, and prevent branch deletion. Save the ruleset and verify it is active.

## Security

Use the [security policy](SECURITY.md) for responsible reporting. Do not post exploitable vulnerability details in public issues.
