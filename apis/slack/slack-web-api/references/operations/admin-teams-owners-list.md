# GET /admin.teams.owners.list

**Resource:** [admin.teams.owners](../resources/admin-teams-owners.md)
**Operation ID:** `admin_teams_owners_list`

List all of the owners on a given workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `admin.teams:read` |
| `team_id` | query | string | Yes |  |
| `limit` | query | integer | No | The maximum number of items to return. Must be between 1 - 1000 both inclusive. |
| `cursor` | query | string | No | Set `cursor` to `next_cursor` returned by the previous call to list items in the next page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.teams:read
