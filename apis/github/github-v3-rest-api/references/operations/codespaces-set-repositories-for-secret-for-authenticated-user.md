# PUT /user/codespaces/secrets/{secret_name}/repositories

**Resource:** [codespaces](../resources/codespaces.md)
**Set selected repositories for a user secret**
**Operation ID:** `codespaces/set-repositories-for-secret-for-authenticated-user`

Select the repositories that will use a user's development environment secret.

The authenticated user must have Codespaces access to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `codespace` or `codespace:secrets` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content when repositories were added to the selected list |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

