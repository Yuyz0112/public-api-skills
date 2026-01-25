# GET /apps.uninstall

**Resource:** [apps](../resources/apps.md)
**Operation ID:** `apps_uninstall`

Uninstalls your app from a workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `none` |
| `client_id` | query | string | No | Issued when you created your application. |
| `client_secret` | query | string | No | Issued when you created your application. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: none
