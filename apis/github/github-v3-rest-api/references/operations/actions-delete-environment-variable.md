# DELETE /repos/{owner}/{repo}/environments/{environment_name}/variables/{name}

**Resource:** [actions](../resources/actions.md)
**Delete an environment variable**
**Operation ID:** `actions/delete-environment-variable`

Deletes an environment variable using the variable name.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

