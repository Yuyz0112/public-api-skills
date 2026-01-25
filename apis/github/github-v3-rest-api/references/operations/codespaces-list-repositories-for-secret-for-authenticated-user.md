# GET /user/codespaces/secrets/{secret_name}/repositories

**Resource:** [codespaces](../resources/codespaces.md)
**List selected repositories for a user secret**
**Operation ID:** `codespaces/list-repositories-for-secret-for-authenticated-user`

List the repositories that have been granted the ability to use a user's development environment secret.

The authenticated user must have Codespaces access to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `codespace` or `codespace:secrets` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

