# POST /admin.conversations.setConversationPrefs

**Resource:** [admin.conversations](../resources/admin-conversations.md)
**Operation ID:** `admin_conversations_setConversationPrefs`

Set the posting permissions for a public or private channel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.conversations:write` |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.conversations:write
