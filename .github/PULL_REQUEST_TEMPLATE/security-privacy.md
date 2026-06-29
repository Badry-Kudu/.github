<!-- Use this template for auth, authorization, secrets, PII, logging, encryption, dependency risk, or security hardening. -->

## Security / privacy change

<!-- Describe the risk, control, fix, or hardening. Avoid exposing sensitive details for active vulnerabilities. -->

## Classification

- [ ] Authentication
- [ ] Authorization
- [ ] Secrets / credentials
- [ ] PII / personal data
- [ ] Logging / telemetry
- [ ] Encryption / key management
- [ ] Dependency / supply chain
- [ ] Input validation / injection
- [ ] Rate limiting / abuse prevention
- [ ] Security configuration

## Threat / risk addressed

<!-- What attack, leak, misuse, or compliance issue does this reduce? -->

## Implementation details

<!-- Describe controls, boundaries, assumptions, and defense-in-depth. -->

## Data handling

- [ ] No new data collected
- [ ] New data collected; documented
- [ ] Logs reviewed for sensitive data
- [ ] Retention/deletion impact reviewed
- [ ] Access control reviewed

## Verification

```text
# tests, scans, manual checks, reproduction, exploit prevention evidence
```

## Rollout and rollback

<!-- Include whether this needs coordinated deployment, secret rotation, migration, or staged rollout. -->

## Reviewer guidance

Security-sensitive areas to inspect:

## Checklist

- [ ] No secrets or sensitive details are included in the PR.
- [ ] Permissions are least-privilege.
- [ ] Sensitive data is not logged.
- [ ] Tests cover abuse or failure cases where practical.
- [ ] Documentation or runbooks were updated if needed.
- [ ] Security/privacy owner reviewed if required.
