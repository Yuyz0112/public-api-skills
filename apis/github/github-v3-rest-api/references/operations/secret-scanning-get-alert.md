# GET /repos/{owner}/{repo}/secret-scanning/alerts/{alert_number}

**Resource:** [secret-scanning](../resources/secret-scanning.md)
**Get a secret scanning alert**
**Operation ID:** `secret-scanning/get-alert`

Gets a single secret scanning alert detected in an eligible repository.

The authenticated user must be an administrator for the repository or for the organization that owns the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` or `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 404 | Repository is public, or secret scanning is disabled for the repository, or the resource is not found |
| 503 | (reference) |

**Success Response Schema:**

[secret-scanning-alert](../schemas/secret-scanning-alert/secret-scanning-alert.md)

