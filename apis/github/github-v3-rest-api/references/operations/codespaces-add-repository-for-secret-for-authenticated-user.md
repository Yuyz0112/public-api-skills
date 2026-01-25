# PUT /user/codespaces/secrets/{secret_name}/repositories/{repository_id}

**Resource:** [codespaces](../resources/codespaces.md)
**Add a selected repository to a user secret**
**Operation ID:** `codespaces/add-repository-for-secret-for-authenticated-user`

Adds a repository to the selected repositories for a user's development environment secret.

The authenticated user must have Codespaces access to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `codespace` or `codespace:secrets` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content when repository was added to the selected list |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

