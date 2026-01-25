# POST /admin.conversations.restrictAccess.addGroup

**Resource:** [admin.conversations.restrictAccess](../resources/admin-conversations-restrictAccess.md)
**Operation ID:** `admin_conversations_restrictAccess_addGroup`

Add an allowlist of IDP groups for accessing a channel

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
