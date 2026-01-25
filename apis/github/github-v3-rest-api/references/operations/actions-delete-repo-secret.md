# DELETE /repos/{owner}/{repo}/actions/secrets/{secret_name}

**Resource:** [actions](../resources/actions.md)
**Delete a repository secret**
**Operation ID:** `actions/delete-repo-secret`

Deletes a secret in a repository using the secret name.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

