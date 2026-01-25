# POST /user/codespaces/{codespace_name}/start

**Resource:** [codespaces](../resources/codespaces.md)
**Start a codespace for the authenticated user**
**Operation ID:** `codespaces/start-for-authenticated-user`

Starts a user's codespace.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 402 | Payment required |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[codespace](../schemas/codespace/codespace.md)

