# POST /user/codespaces/{codespace_name}/stop

**Resource:** [codespaces](../resources/codespaces.md)
**Stop a codespace for the authenticated user**
**Operation ID:** `codespaces/stop-for-authenticated-user`

Stops a user's codespace.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[codespace](../schemas/codespace/codespace.md)

