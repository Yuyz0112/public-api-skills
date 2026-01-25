# GET /repos/{owner}/{repo}/secret-scanning/alerts/{alert_number}/locations

**Resource:** [secret-scanning](../resources/secret-scanning.md)
**List locations for a secret scanning alert**
**Operation ID:** `secret-scanning/list-locations-for-alert`

Lists all locations for a given secret scanning alert for an eligible repository.

The authenticated user must be an administrator for the repository or for the organization that owns the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` or `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | Repository is public, or secret scanning is disabled for the repository, or the resource is not found |
| 503 | (reference) |

**Success Response Schema:**

Array of [secret-scanning-location](../schemas/secret-scanning-location/secret-scanning-location.md)

