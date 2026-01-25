# POST /repos/{owner}/{repo}/codespaces

**Resource:** [codespaces](../resources/codespaces.md)
**Create a codespace in a repository**
**Operation ID:** `codespaces/create-with-repo-for-authenticated-user`

Creates a codespace owned by the authenticated user in the specified repository.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response when the codespace was successfully created |
| 202 | Response when the codespace creation partially failed but is being retried in the background |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[codespace](../schemas/codespace/codespace.md)

