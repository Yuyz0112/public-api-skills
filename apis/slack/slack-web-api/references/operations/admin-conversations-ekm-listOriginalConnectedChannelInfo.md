# GET /admin.conversations.ekm.listOriginalConnectedChannelInfo

**Resource:** [admin.conversations.ekm](../resources/admin-conversations-ekm.md)
**Operation ID:** `admin_conversations_ekm_listOriginalConnectedChannelInfo`

List all disconnected channels—i.e., channels that were once connected to other workspaces and then disconnected—and the corresponding original channel IDs for key revocation with EKM.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `admin.conversations:read` |
| `channel_ids` | query | string | No | A comma-separated list of channels to filter to. |
| `team_ids` | query | string | No | A comma-separated list of the workspaces to which the channels you would like returned belong. |
| `limit` | query | integer | No | The maximum number of items to return. Must be between 1 - 1000 both inclusive. |
| `cursor` | query | string | No | Set `cursor` to `next_cursor` returned by the previous call to list items in the next page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.conversations:read
