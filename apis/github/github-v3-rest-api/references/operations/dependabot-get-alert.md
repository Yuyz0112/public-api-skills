# GET /repos/{owner}/{repo}/dependabot/alerts/{alert_number}

**Resource:** [dependabot](../resources/dependabot.md)
**Get a Dependabot alert**
**Operation ID:** `dependabot/get-alert`

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dependabot-alert](../schemas/dependabot-alert/dependabot-alert.md)

