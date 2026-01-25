# POST /repos/{owner}/{repo}/security-advisories

**Resource:** [security-advisories](../resources/security-advisories.md)
**Create a repository security advisory**
**Operation ID:** `security-advisories/create-repository-advisory`

Creates a new repository security advisory.

In order to create a draft repository security advisory, the authenticated user must be a security manager or administrator of that repository.

OAuth app tokens and personal access tokens (classic) need the `repo` or `repository_advisories:write` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [repository-advisory-create](../schemas/repository-advisory-create/repository-advisory-create.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[repository-advisory](../schemas/repository-advisory/repository-advisory.md)

