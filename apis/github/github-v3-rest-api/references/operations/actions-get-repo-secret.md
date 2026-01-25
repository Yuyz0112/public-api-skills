# GET /repos/{owner}/{repo}/actions/secrets/{secret_name}

**Resource:** [actions](../resources/actions.md)
**Get a repository secret**
**Operation ID:** `actions/get-repo-secret`

Gets a single repository secret without revealing its encrypted value.

The authenticated user must have collaborator access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-secret](../schemas/actions-secret/actions-secret.md)

