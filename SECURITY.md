# Security Policy — Conductra Health

## Reporting a Vulnerability

Report security vulnerabilities to: **security@conductrahealth.com**

Do not open public GitHub Issues for security vulnerabilities. We will acknowledge receipt within 72 hours and provide a resolution timeline.

---

## Scope

This security policy applies to all Conductra Health repositories:

| Repository | Contains PHI | Notes |
|------------|-------------|-------|
| hospian-app | No (dev only) | PHI handling via Supabase Vault + BAA |
| hospian-website | No | Public-facing marketing site |
| conductra-health-website | No | Corporate site |
| voice-architecture | No | Architecture reference only |
| etchsizzle-audit-tool | No | Notion integration tool |

No Conductra Health repository contains real Protected Health Information. PHI handling in production follows BAA-backed infrastructure only.

---

## Supported Versions

| Repository | Supported Version |
|------------|------------------|
| All active repos | Latest main branch only |

---

## Security Practices

- All secrets managed via platform-specific secret stores (Cloudflare, Supabase Vault)
- No secrets committed to any repository
- Dependency updates managed via Dependabot on all repositories
- PHI-adjacent code reviewed against HIPAA technical safeguard requirements
- Security hard rules documented in each repository's CLAUDE.md

---

## Responsible Disclosure

We appreciate responsible disclosure of security vulnerabilities. Researchers who report valid vulnerabilities will be acknowledged (with permission) in our security log.

---

*Conductra Health, Inc. — Delaware C-Corporation*
*security@conductrahealth.com*
