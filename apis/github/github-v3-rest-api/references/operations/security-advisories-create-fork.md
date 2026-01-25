# POST /repos/{owner}/{repo}/security-advisories/{ghsa_id}/forks

**Resource:** [security-advisories](../resources/security-advisories.md)
**Create a temporary private fork**
**Operation ID:** `security-advisories/create-fork`

Create a temporary private fork to collaborate on fixing a security vulnerability in your repository.

> [!NOTE]
> Forking a repository happens asynchronously. You may have to wait up to 5 minutes before you can access the fork.

## Responses

| Status | Description |
|--------|-------------|
| 202 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

