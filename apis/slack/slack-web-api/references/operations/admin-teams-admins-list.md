# GET /admin.teams.admins.list

**Resource:** [admin.teams.admins](../resources/admin-teams-admins.md)
**Operation ID:** `admin_teams_admins_list`

List all of the admins on a given workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `admin.teams:read` |
| `limit` | query | integer | No | The maximum number of items to return. |
| `cursor` | query | string | No | Set `cursor` to `next_cursor` returned by the previous call to list items in the next page. |
| `team_id` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.teams:read
