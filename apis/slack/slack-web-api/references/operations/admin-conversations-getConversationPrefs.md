# GET /admin.conversations.getConversationPrefs

**Resource:** [admin.conversations](../resources/admin-conversations.md)
**Operation ID:** `admin_conversations_getConversationPrefs`

Get conversation preferences for a public or private channel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.conversations:read` |
| `channel_id` | query | string | Yes | The channel to get preferences for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.conversations:read
