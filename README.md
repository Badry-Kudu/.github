# Default GitHub PR templates

This repository provides default pull request templates for repositories owned by `Badry-Kudu`.

GitHub applies default community health files from a public `.github` repository to repositories owned by the same account when those repositories do not define their own equivalent files.

## Default template

The default PR template is:

```text
.github/pull_request_template.md
```

Use this for normal pull requests.

## Specialized templates

Additional templates are stored in:

```text
.github/PULL_REQUEST_TEMPLATE/
```

GitHub does not show a built-in dropdown for multiple PR templates. Use the `template` query parameter when opening a PR.

Example:

```text
https://github.com/OWNER/REPO/compare/main...my-branch?quick_pull=1&template=bug-fix.md
```

## Available templates

| Template | File | Use when |
|---|---|---|
| Default | `.github/pull_request_template.md` | General PRs where no specialized template is needed |
| Bug fix | `.github/PULL_REQUEST_TEMPLATE/bug-fix.md` | Fixing incorrect behavior, regressions, or defects |
| Feature | `.github/PULL_REQUEST_TEMPLATE/feature.md` | Adding new user-facing or developer-facing functionality |
| Refactor | `.github/PULL_REQUEST_TEMPLATE/refactor.md` | Changing structure without intended behavior change |
| Documentation | `.github/PULL_REQUEST_TEMPLATE/documentation.md` | Docs, examples, README, tutorials, or comments |
| Dependency update | `.github/PULL_REQUEST_TEMPLATE/dependency-update.md` | Upgrading packages, runtimes, lockfiles, or vendored dependencies |
| CI / infrastructure | `.github/PULL_REQUEST_TEMPLATE/ci-infrastructure.md` | Build, test, deployment, workflow, or environment changes |
| Security / privacy | `.github/PULL_REQUEST_TEMPLATE/security-privacy.md` | Auth, permissions, secrets, PII, logging, dependency risk |
| Hotfix / release | `.github/PULL_REQUEST_TEMPLATE/hotfix-release.md` | Urgent fixes, release blockers, production patches |
| AI-assisted change | `.github/PULL_REQUEST_TEMPLATE/ai-assisted-change.md` | Substantial code generated or modified with AI assistance |

## Reusable PR links

Add links like these to project READMEs or contributor guides:

```md
- [Bug fix PR](https://github.com/OWNER/REPO/compare/main...BRANCH?quick_pull=1&template=bug-fix.md)
- [Feature PR](https://github.com/OWNER/REPO/compare/main...BRANCH?quick_pull=1&template=feature.md)
- [Security/privacy PR](https://github.com/OWNER/REPO/compare/main...BRANCH?quick_pull=1&template=security-privacy.md)
```

Replace `OWNER`, `REPO`, and `BRANCH`.
