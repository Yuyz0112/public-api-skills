# DELETE /user/codespaces/{codespace_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Delete a codespace for the authenticated user**
**Operation ID:** `codespaces/delete-for-authenticated-user`

Deletes a user's codespace.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 202 | (reference) |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

