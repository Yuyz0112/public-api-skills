# GET /repos/{owner}/{repo}/environments/{environment_name}/variables/{name}

**Resource:** [actions](../resources/actions.md)
**Get an environment variable**
**Operation ID:** `actions/get-environment-variable`

Gets a specific variable in an environment.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-variable](../schemas/actions-variable/actions-variable.md)

