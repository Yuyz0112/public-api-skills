# POST /conversations.leave

**Resource:** [conversations](../resources/conversations.md)
**Operation ID:** `conversations_leave`

Leaves a conversation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | No | Authentication token. Requires scope: `conversations:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response when attempting to leave a workspace's "general" channel |

## Security

- **slackAuth**: channels:write, groups:write, im:write, mpim:write
