# security-advisories

Manage security advisories.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/advisories` | List global security advisories | [View](../operations/security-advisories-list-global-advisories.md) |
| GET | `/advisories/{ghsa_id}` | Get a global security advisory | [View](../operations/security-advisories-get-global-advisory.md) |
| GET | `/orgs/{org}/security-advisories` | List repository security advisories for an organization | [View](../operations/security-advisories-list-org-repository-advisories.md) |
| GET | `/repos/{owner}/{repo}/security-advisories` | List repository security advisories | [View](../operations/security-advisories-list-repository-advisories.md) |
| POST | `/repos/{owner}/{repo}/security-advisories` | Create a repository security advisory | [View](../operations/security-advisories-create-repository-advisory.md) |
| POST | `/repos/{owner}/{repo}/security-advisories/reports` | Privately report a security vulnerability | [View](../operations/security-advisories-create-private-vulnerability-report.md) |
| GET | `/repos/{owner}/{repo}/security-advisories/{ghsa_id}` | Get a repository security advisory | [View](../operations/security-advisories-get-repository-advisory.md) |
| PATCH | `/repos/{owner}/{repo}/security-advisories/{ghsa_id}` | Update a repository security advisory | [View](../operations/security-advisories-update-repository-advisory.md) |
| POST | `/repos/{owner}/{repo}/security-advisories/{ghsa_id}/cve` | Request a CVE for a repository security advisory | [View](../operations/security-advisories-create-repository-advisory-cve-request.md) |
| POST | `/repos/{owner}/{repo}/security-advisories/{ghsa_id}/forks` | Create a temporary private fork | [View](../operations/security-advisories-create-fork.md) |
