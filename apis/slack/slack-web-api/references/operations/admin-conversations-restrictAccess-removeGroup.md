# POST /admin.conversations.restrictAccess.removeGroup

**Resource:** [admin.conversations.restrictAccess](../resources/admin-conversations-restrictAccess.md)
**Operation ID:** `admin_conversations_restrictAccess_removeGroup`

Remove a linked IDP group linked from a private channel

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
