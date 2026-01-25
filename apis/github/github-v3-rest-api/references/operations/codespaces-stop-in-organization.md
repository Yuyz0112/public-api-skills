# POST /orgs/{org}/members/{username}/codespaces/{codespace_name}/stop

**Resource:** [codespaces](../resources/codespaces.md)
**Stop a codespace for an organization user**
**Operation ID:** `codespaces/stop-in-organization`

Stops a user's codespace.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

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

