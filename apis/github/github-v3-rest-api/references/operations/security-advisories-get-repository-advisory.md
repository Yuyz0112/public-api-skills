# GET /repos/{owner}/{repo}/security-advisories/{ghsa_id}

**Resource:** [security-advisories](../resources/security-advisories.md)
**Get a repository security advisory**
**Operation ID:** `security-advisories/get-repository-advisory`

Get a repository security advisory using its GitHub Security Advisory (GHSA) identifier.

Anyone can access any published security advisory on a public repository.

The authenticated user can access an unpublished security advisory from a repository if they are a security manager or administrator of that repository, or if they are a
collaborator on the security advisory.

OAuth app tokens and personal access tokens (classic) need the `repo` or `repository_advisories:read` scope to to get a published security advisory in a private repository, or any unpublished security advisory that the authenticated user has access to.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[repository-advisory](../schemas/repository-advisory/repository-advisory.md)

