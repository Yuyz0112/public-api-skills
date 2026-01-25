# GET /repos/{owner}/{repo}/secret-scanning/alerts

**Resource:** [secret-scanning](../resources/secret-scanning.md)
**List secret scanning alerts for a repository**
**Operation ID:** `secret-scanning/list-alerts-for-repo`

Lists secret scanning alerts for an eligible repository, from newest to oldest.

The authenticated user must be an administrator for the repository or for the organization that owns the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` or `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | Repository is public or secret scanning is disabled for the repository |
| 503 | (reference) |

**Success Response Schema:**

Array of [secret-scanning-alert](../schemas/secret-scanning-alert/secret-scanning-alert.md)

