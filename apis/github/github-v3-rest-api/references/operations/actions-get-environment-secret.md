# GET /repos/{owner}/{repo}/environments/{environment_name}/secrets/{secret_name}

**Resource:** [actions](../resources/actions.md)
**Get an environment secret**
**Operation ID:** `actions/get-environment-secret`

Gets a single environment secret without revealing its encrypted value.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-secret](../schemas/actions-secret/actions-secret.md)

