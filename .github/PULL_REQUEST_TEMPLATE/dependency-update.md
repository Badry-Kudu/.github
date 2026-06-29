<!-- Use this template for package, runtime, lockfile, vendored dependency, or toolchain updates. -->

## Dependency change

<!-- Name the dependency, current version, target version, and ecosystem. -->

| Dependency | From | To | Reason |
|---|---:|---:|---|
|  |  |  |  |

## Change type

- [ ] Patch
- [ ] Minor
- [ ] Major
- [ ] Security update
- [ ] Runtime/toolchain update
- [ ] Lockfile-only update

## Release notes / changelog reviewed

<!-- Link upstream release notes, migration guide, advisory, or changelog. -->

## Compatibility impact

- [ ] No breaking changes found
- [ ] Breaking changes handled
- [ ] Requires code migration
- [ ] Requires config migration
- [ ] Unknown; explain:

## Security impact

- [ ] Fixes known vulnerability
- [ ] No known vulnerability impact
- [ ] Adds new transitive dependencies; reviewed
- [ ] Not reviewed; reason:

## Testing

```text
# install/build/test/audit commands and results
```

## Rollback

<!-- State how to revert safely if the update breaks production or CI. -->

## Checklist

- [ ] Lockfiles are updated intentionally.
- [ ] Upstream release notes or advisory were reviewed.
- [ ] Transitive dependency changes were checked.
- [ ] Build and tests pass.
- [ ] Runtime/deployment compatibility was considered.
