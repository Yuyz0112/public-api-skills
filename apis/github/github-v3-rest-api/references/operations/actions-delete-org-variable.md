# DELETE /orgs/{org}/actions/variables/{name}

**Resource:** [actions](../resources/actions.md)
**Delete an organization variable**
**Operation ID:** `actions/delete-org-variable`

Deletes an organization variable using the variable name.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth tokens and personal access tokens (classic) need the`admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

