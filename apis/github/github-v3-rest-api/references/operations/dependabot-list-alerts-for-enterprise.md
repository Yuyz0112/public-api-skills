# GET /enterprises/{enterprise}/dependabot/alerts

**Resource:** [dependabot](../resources/dependabot.md)
**List Dependabot alerts for an enterprise**
**Operation ID:** `dependabot/list-alerts-for-enterprise`

Lists Dependabot alerts for repositories that are owned by the specified enterprise.

The authenticated user must be a member of the enterprise to use this endpoint.

Alerts are only returned for organizations in the enterprise for which you are an organization owner or a security manager. For more information about security managers, see "[Managing security managers in your organization](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/managing-security-managers-in-your-organization)."

OAuth app tokens and personal access tokens (classic) need the `repo` or `security_events` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [dependabot-alert-with-repository](../schemas/dependabot-alert-with-repository/dependabot-alert-with-repository.md)

