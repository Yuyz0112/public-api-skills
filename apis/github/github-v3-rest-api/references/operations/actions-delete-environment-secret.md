# DELETE /repos/{owner}/{repo}/environments/{environment_name}/secrets/{secret_name}

**Resource:** [actions](../resources/actions.md)
**Delete an environment secret**
**Operation ID:** `actions/delete-environment-secret`

Deletes a secret in an environment using the secret name.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Default response |

