# GET /admin.conversations.restrictAccess.listGroups

**Resource:** [admin.conversations.restrictAccess](../resources/admin-conversations-restrictAccess.md)
**Operation ID:** `admin_conversations_restrictAccess_listGroups`

List all IDP Groups linked to a channel

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `admin.conversations:read` |
| `channel_id` | query | string | Yes |  |
| `team_id` | query | string | No | The workspace where the channel exists. This argument is required for channels only tied to one workspace, and optional for channels that are shared across an organization. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.conversations:read
