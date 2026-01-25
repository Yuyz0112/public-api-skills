# POST /conversations.setPurpose

**Resource:** [conversations](../resources/conversations.md)
**Operation ID:** `conversations_setPurpose`

Sets the purpose for a conversation.

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
| default | Typical error response |

## Security

- **slackAuth**: channels:write, groups:write, im:write, mpim:write
