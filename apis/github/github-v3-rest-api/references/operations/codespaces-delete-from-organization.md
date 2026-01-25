# DELETE /orgs/{org}/members/{username}/codespaces/{codespace_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Delete a codespace from the organization**
**Operation ID:** `codespaces/delete-from-organization`

Deletes a user's codespace.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 202 | (reference) |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

