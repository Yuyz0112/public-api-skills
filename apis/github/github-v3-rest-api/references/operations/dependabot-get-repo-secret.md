# GET /repos/{owner}/{repo}/dependabot/secrets/{secret_name}

**Resource:** [dependabot](../resources/dependabot.md)
**Get a repository secret**
**Operation ID:** `dependabot/get-repo-secret`

Gets a single repository secret without revealing its encrypted value.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[dependabot-secret](../schemas/dependabot-secret/dependabot-secret.md)

