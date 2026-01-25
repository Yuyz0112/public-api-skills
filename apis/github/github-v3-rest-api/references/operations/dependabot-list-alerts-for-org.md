# GET /orgs/{org}/dependabot/alerts

**Resource:** [dependabot](../resources/dependabot.md)
**List Dependabot alerts for an organization**
**Operation ID:** `dependabot/list-alerts-for-org`

Lists Dependabot alerts for an organization.

The authenticated user must be an owner or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [dependabot-alert-with-repository](../schemas/dependabot-alert-with-repository/dependabot-alert-with-repository.md)

