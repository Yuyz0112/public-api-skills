# GET /admin.apps.restricted.list

**Resource:** [admin.apps.restricted](../resources/admin-apps-restricted.md)
**Operation ID:** `admin_apps_restricted_list`

List restricted apps for an org or workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `admin.apps:read` |
| `limit` | query | integer | No | The maximum number of items to return. Must be between 1 - 1000 both inclusive. |
| `cursor` | query | string | No | Set `cursor` to `next_cursor` returned by the previous call to list items in the next page |
| `team_id` | query | string | No |  |
| `enterprise_id` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.apps:read
