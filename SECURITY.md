# Security Policy

## Supported Versions

Solo Empire is a personal project. Security updates are applied to `main` as soon as they are identified.

## Reporting a Vulnerability

Since this is a personal project, please report security issues by:

1. Opening a [security advisory](https://github.com/bookchaowalit/solo-empire/security/advisories/new) on GitHub, or
2. Emailing the maintainer directly

**Do not open public issues for security vulnerabilities.**

## Security Practices

- Secrets are managed via Infisical (never committed to repo)
- Automated secret scanning runs in CI (`npm run lint:secrets`)
- Dependencies are monitored for vulnerabilities
- All API keys are stored in environment variables, never in code
