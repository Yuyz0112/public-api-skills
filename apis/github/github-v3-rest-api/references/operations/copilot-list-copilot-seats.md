# GET /orgs/{org}/copilot/billing/seats

**Resource:** [copilot](../resources/copilot.md)
**List all Copilot seat assignments for an organization**
**Operation ID:** `copilot/list-copilot-seats`

> [!NOTE]
> This endpoint is in public preview and is subject to change.

Lists all Copilot seats for which an organization with a Copilot Business or Copilot Enterprise subscription is currently being billed.
Only organization owners can view assigned seats.

Each seat object contains information about the assigned user's most recent Copilot activity. Users must have telemetry enabled in their IDE for Copilot in the IDE activity to be reflected in `last_activity_at`.
For more information about activity data, see [Metrics data properties for GitHub Copilot](https://docs.github.com/copilot/reference/metrics-data).

OAuth app tokens and personal access tokens (classic) need either the `manage_billing:copilot` or `read:org` scopes to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `per_page` | query | integer | No | The number of results per page (max 100). For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)." |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

