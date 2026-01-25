# GET /orgs/{org}/secret-scanning/alerts

**Resource:** [secret-scanning](../resources/secret-scanning.md)
**List secret scanning alerts for an organization**
**Operation ID:** `secret-scanning/list-alerts-for-org`

Lists secret scanning alerts for eligible repositories in an organization, from newest to oldest.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` or `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

Array of [organization-secret-scanning-alert](../schemas/organization-secret-scanning-alert/organization-secret-scanning-alert.md)

