# DELETE /repos/{owner}/{repo}/actions/variables/{name}

**Resource:** [actions](../resources/actions.md)
**Delete a repository variable**
**Operation ID:** `actions/delete-repo-variable`

Deletes a repository variable using the variable name.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

