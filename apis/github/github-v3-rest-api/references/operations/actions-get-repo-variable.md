# GET /repos/{owner}/{repo}/actions/variables/{name}

**Resource:** [actions](../resources/actions.md)
**Get a repository variable**
**Operation ID:** `actions/get-repo-variable`

Gets a specific variable in a repository.

The authenticated user must have collaborator access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-variable](../schemas/actions-variable/actions-variable.md)

