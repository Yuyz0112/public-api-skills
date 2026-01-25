# GET /repos/{owner}/{repo}/dependabot/alerts

**Resource:** [dependabot](../resources/dependabot.md)
**List Dependabot alerts for a repository**
**Operation ID:** `dependabot/list-alerts-for-repo`

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `per_page` | query | integer | No | The number of results per page (max 100). For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)." |

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

Array of [dependabot-alert](../schemas/dependabot-alert/dependabot-alert.md)

