# Security

> [!IMPORTANT]
> Principles only. No credential names, no specific scopes, no key rotation
> mechanics beyond the general practice.

- **Credential isolation.** Secrets live in a dedicated store, never in
  workflow configuration values, logs, or code.
- **Environment variables** for local development; committed example files
  contain placeholder values only.
- **Least privilege.** Service accounts and integration tokens are scoped to
  the role a component's function requires. Platform default grants are
  reviewed against actual usage and replaced with purpose-built credentials
  where the default exceeds it.
- **API key rotation.** Scheduled on a recurring cadence.
- **Webhook URL handling.** Treated as secrets, never committed,
  documented, or shared.
- **Logging policy.** No pipeline path logs a secret. Task/run history is
  reviewed for this before anything is exposed even internally.

> [!TIP]
> **Reporting a vulnerability:** use GitHub's Security tab on this repository to report privately, once the repository is live.
