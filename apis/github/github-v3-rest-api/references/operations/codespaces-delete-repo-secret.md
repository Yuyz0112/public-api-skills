# DELETE /repos/{owner}/{repo}/codespaces/secrets/{secret_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Delete a repository secret**
**Operation ID:** `codespaces/delete-repo-secret`

Deletes a development environment secret in a repository using the secret name.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint. The associated user must be a repository admin.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

