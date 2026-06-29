<!-- Use this template for CI, build, deployment, workflow, environment, infra, or tooling changes. -->

## Infrastructure / CI change

<!-- What system, workflow, or environment changed? -->

## Motivation

<!-- Reliability, speed, cost, security, developer experience, required upgrade, etc. -->

## Affected systems

- [ ] GitHub Actions / CI
- [ ] Build system
- [ ] Test infrastructure
- [ ] Deployment pipeline
- [ ] Runtime infrastructure
- [ ] Developer tooling
- [ ] Secrets / credentials
- [ ] Monitoring / logging

## Implementation details

<!-- Mention workflow names, environments, permissions, secrets, cache keys, runners, images, services, or scripts. -->

## Validation

```text
# workflow runs, dry-runs, test commands, deployment checks
```

## Operational risk

Risk level: Low / Medium / High

Failure mode:

Rollback plan:

## Security review

- [ ] No permission/secrets impact
- [ ] Permissions minimized
- [ ] Secrets handling reviewed
- [ ] Third-party action or image reviewed/pinned
- [ ] Not applicable

## Checklist

- [ ] Change is scoped to infrastructure/tooling.
- [ ] Logs or workflow run evidence is included.
- [ ] Permissions are least-privilege where applicable.
- [ ] Rollback is documented.
- [ ] CI passes.
