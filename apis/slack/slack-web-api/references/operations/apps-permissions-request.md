# GET /apps.permissions.request

**Resource:** [apps.permissions](../resources/apps-permissions.md)
**Operation ID:** `apps_permissions_request`

Allows an app to request additional scopes

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `none` |
| `scopes` | query | string | Yes | A comma separated list of scopes to request for |
| `trigger_id` | query | string | Yes | Token used to trigger the permissions API |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Standard success response when used with a user token |
| default | Standard failure response when trigger_id is invalid |

## Security

- **slackAuth**: none
