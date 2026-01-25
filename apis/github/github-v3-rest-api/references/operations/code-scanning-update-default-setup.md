# PATCH /repos/{owner}/{repo}/code-scanning/default-setup

**Resource:** [code-scanning](../resources/code-scanning.md)
**Update a code scanning default setup configuration**
**Operation ID:** `code-scanning/update-default-setup`

Updates a code scanning default setup configuration.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [code-scanning-default-setup-update](../schemas/code-scanning-default-setup-update/code-scanning-default-setup-update.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 202 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

