# Security Policy

## Supported versions

Security fixes are prioritized for the latest `main` branch and the latest immutable revision used by repository callers. Older revisions may not receive fixes.

| Version or channel | Security support |
|---|---|
| Latest published immutable revision | Supported |
| `main` | Supported for active development |
| Older revisions | Best effort only |

## Reporting a vulnerability

Please do **not** report security vulnerabilities in a public issue, discussion, pull request, or workflow comment.

Use GitHub's private vulnerability reporting flow from the repository's **Security** tab. If that option is unavailable, contact the repository maintainers privately through GitHub and include the affected workflow or script, commit or tag, reproduction steps, impact, and any proof-of-concept needed to verify the issue.

The reusable workflow is designed to process repository configuration and public website files. Do not include API keys, authentication tokens, cookies, personal data, or other secrets in a report or test fixture.

## Scope

This policy covers the reusable GitHub Actions workflow, the SEO audit scripts, dependency and configuration parsing, repository checkout behavior, and any generated output that could expose caller-repository data or workflow credentials.

## Response expectations

The maintainers will acknowledge a report when practical, investigate the issue, and coordinate a fix or mitigation. Please allow reasonable time for triage and for caller repositories to update their pinned workflow revision before making details public.

When a fix is released, the project may publish a security note describing affected revisions, impact, and the required caller update. Reporter credit will be given only with permission.
