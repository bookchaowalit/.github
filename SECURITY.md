# Security Policy

## Supported Versions

These defaults apply to every public repository of this account that has no SECURITY.md of its own. Security updates are applied to the default branch as soon as they are identified.

## Reporting a Vulnerability

Since this is a personal project, please report security issues by:

1. Opening a private vulnerability report on the affected repository (**Security** tab → **Report a vulnerability**), or
2. Emailing the maintainer (see the GitHub profile)

**Do not open public issues for security vulnerabilities.**

## Security Practices

- Secrets are managed via Infisical (never committed to repo)
- Automated secret scanning runs in CI
- Dependencies are monitored for vulnerabilities
- All API keys are stored in environment variables, never in code
