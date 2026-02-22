# Security Policy

## Scope

This policy covers all repositories under the **venantvr-web** organization. These projects include web applications, frontend frameworks, portfolio sites, APIs, and Docker-based web stacks.

## Reporting a Vulnerability

If you discover a security vulnerability in any of these repositories, please report it responsibly:

1. **Do not open a public issue.** Security vulnerabilities must be reported privately.
2. Go to the affected repository's **Security** tab and click **"Report a vulnerability"** to create a private security advisory.
3. Include as much detail as possible: affected files, steps to reproduce, and potential impact.

## What We Consider Security Issues

- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- SQL or NoSQL injection
- Authentication or session management flaws
- Insecure direct object references
- Server-side request forgery (SSRF)
- Exposed secrets, API keys, or credentials
- Insecure Docker configurations (exposed ports, default passwords)

## Response

- Acknowledgment within **72 hours**
- Status update within **7 days**
- If confirmed, a fix will be prioritized and you will be credited (unless you prefer anonymity)

## Out of Scope

- Archived repositories (kept for reference, not actively maintained)
- Static portfolio sites with no backend or user input processing
- Known limitations documented in the project's README
