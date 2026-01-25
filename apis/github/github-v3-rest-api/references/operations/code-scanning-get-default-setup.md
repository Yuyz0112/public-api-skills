# GET /repos/{owner}/{repo}/code-scanning/default-setup

**Resource:** [code-scanning](../resources/code-scanning.md)
**Get a code scanning default setup configuration**
**Operation ID:** `code-scanning/get-default-setup`

Gets a code scanning default setup configuration.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-default-setup](../schemas/code-scanning-default-setup/code-scanning-default-setup.md)

