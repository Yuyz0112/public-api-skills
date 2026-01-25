# GET /repos/{owner}/{repo}/codespaces/secrets/{secret_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Get a repository secret**
**Operation ID:** `codespaces/get-repo-secret`

Gets a single repository development environment secret without revealing its encrypted value.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[repo-codespaces-secret](../schemas/repo-codespaces-secret/repo-codespaces-secret.md)

