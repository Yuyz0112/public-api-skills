# GET /user/codespaces/{codespace_name}/machines

**Resource:** [codespaces](../resources/codespaces.md)
**List machine types for a codespace**
**Operation ID:** `codespaces/codespace-machines-for-authenticated-user`

List the machine types a codespace can transition to use.

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

