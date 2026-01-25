# GET /admin.emoji.list

**Resource:** [admin.emoji](../resources/admin-emoji.md)
**Operation ID:** `admin_emoji_list`

List emoji for an Enterprise Grid organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `admin.teams:read` |
| `cursor` | query | string | No | Set `cursor` to `next_cursor` returned by the previous call to list items in the next page |
| `limit` | query | integer | No | The maximum number of items to return. Must be between 1 - 1000 both inclusive. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.teams:read
