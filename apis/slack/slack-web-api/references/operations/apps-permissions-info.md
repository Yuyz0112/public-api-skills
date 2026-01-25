# GET /apps.permissions.info

**Resource:** [apps.permissions](../resources/apps-permissions.md)
**Operation ID:** `apps_permissions_info`

Returns list of permissions this app has on a team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `none` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Standard success response when used with a user token |
| default | Standard failure response when used with an invalid token |

## Security

- **slackAuth**: none
