# GET /user/codespaces/{codespace_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Get a codespace for the authenticated user**
**Operation ID:** `codespaces/get-for-authenticated-user`

Gets information about a user's codespace.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[codespace](../schemas/codespace/codespace.md)

