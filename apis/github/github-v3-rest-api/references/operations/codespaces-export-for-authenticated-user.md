# POST /user/codespaces/{codespace_name}/exports

**Resource:** [codespaces](../resources/codespaces.md)
**Export a codespace for the authenticated user**
**Operation ID:** `codespaces/export-for-authenticated-user`

Triggers an export of the specified codespace and returns a URL and ID where the status of the export can be monitored.

If changes cannot be pushed to the codespace's repository, they will be pushed to a new or previously-existing fork instead.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 202 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

