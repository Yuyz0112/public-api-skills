# POST /user/codespaces

**Resource:** [codespaces](../resources/codespaces.md)
**Create a codespace for the authenticated user**
**Operation ID:** `codespaces/create-for-authenticated-user`

Creates a new codespace, owned by the authenticated user.

This endpoint requires either a `repository_id` OR a `pull_request` but not both.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response when the codespace was successfully created |
| 202 | Response when the codespace creation partially failed but is being retried in the background |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[codespace](../schemas/codespace/codespace.md)

