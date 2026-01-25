# GET /admin.conversations.getTeams

**Resource:** [admin.conversations](../resources/admin-conversations.md)
**Operation ID:** `admin_conversations_getTeams`

Get all the workspaces a given public or private channel is connected to within this Enterprise org.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.conversations:read` |
| `channel_id` | query | string | Yes | The channel to determine connected workspaces within the organization for. |
| `cursor` | query | string | No | Set `cursor` to `next_cursor` returned by the previous call to list items in the next page |
| `limit` | query | integer | No | The maximum number of items to return. Must be between 1 - 1000 both inclusive. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.conversations:read
