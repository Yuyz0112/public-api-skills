# GET /admin.users.list

**Resource:** [admin.users](../resources/admin-users.md)
**Operation ID:** `admin_users_list`

List users on a workspace

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.users:read` |
| `team_id` | query | string | Yes | The ID (`T1234`) of the workspace. |
| `cursor` | query | string | No | Set `cursor` to `next_cursor` returned by the previous call to list items in the next page. |
| `limit` | query | integer | No | Limit for how many users to be retrieved per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.users:read
