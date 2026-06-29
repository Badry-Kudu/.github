<!-- Use this template for urgent fixes, release blockers, production patches, and backports. -->

## Hotfix / release summary

<!-- What is being fixed or released? -->

## Severity and impact

- [ ] Production outage
- [ ] Release blocker
- [ ] Data correctness
- [ ] Security/privacy
- [ ] Customer/user-visible defect
- [ ] Internal operational issue

Impact:

## Root cause

<!-- Briefly explain the cause if known. -->

## Fix

<!-- Explain the minimal change and why it is safe. -->

## Validation

```text
# exact verification evidence
```

## Rollout plan

<!-- Include target version, deployment order, backport branches, migrations, or feature flags. -->

## Rollback plan

<!-- Include revert commit, config rollback, version rollback, or mitigation. -->

## Communication

- [ ] No communication needed
- [ ] Release note needed
- [ ] Status/customer/internal communication needed
- [ ] Incident follow-up needed

## Checklist

- [ ] Change is minimal and scoped.
- [ ] Fix has been verified against the failing scenario.
- [ ] Rollout owner and rollback path are clear.
- [ ] Release notes/changelog updated if required.
- [ ] CI passes or exception is documented.
