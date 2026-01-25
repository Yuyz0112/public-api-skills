# GET /orgs/{org}/actions/variables/{name}/repositories

**Resource:** [actions](../resources/actions.md)
**List selected repositories for an organization variable**
**Operation ID:** `actions/list-selected-repos-for-org-variable`

Lists all repositories that can access an organization variable
that is available to selected repositories.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 409 | Response when the visibility of the variable is not set to `selected` |

