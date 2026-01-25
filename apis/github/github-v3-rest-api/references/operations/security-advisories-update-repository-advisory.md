# PATCH /repos/{owner}/{repo}/security-advisories/{ghsa_id}

**Resource:** [security-advisories](../resources/security-advisories.md)
**Update a repository security advisory**
**Operation ID:** `security-advisories/update-repository-advisory`

Update a repository security advisory using its GitHub Security Advisory (GHSA) identifier.

In order to update any security advisory, the authenticated user must be a security manager or administrator of that repository,
or a collaborator on the repository security advisory.

OAuth app tokens and personal access tokens (classic) need the `repo` or `repository_advisories:write` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [repository-advisory-update](../schemas/repository-advisory-update/repository-advisory-update.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 422 | Validation failed, or the endpoint has been spammed. |

**Success Response Schema:**

[repository-advisory](../schemas/repository-advisory/repository-advisory.md)

