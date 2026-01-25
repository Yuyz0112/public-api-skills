# GET /admin.teams.list

**Resource:** [admin.teams](../resources/admin-teams.md)
**Operation ID:** `admin_teams_list`

List all teams on an Enterprise organization

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.teams:read` |
| `limit` | query | integer | No | The maximum number of items to return. Must be between 1 - 100 both inclusive. |
| `cursor` | query | string | No | Set `cursor` to `next_cursor` returned by the previous call to list items in the next page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.teams:read
