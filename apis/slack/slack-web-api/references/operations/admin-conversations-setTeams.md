# POST /admin.conversations.setTeams

**Resource:** [admin.conversations](../resources/admin-conversations.md)
**Operation ID:** `admin_conversations_setTeams`

Set the workspaces in an Enterprise grid org that connect to a public or private channel.

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
