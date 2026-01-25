# POST /chat.deleteScheduledMessage

**Resource:** [chat](../resources/chat.md)
**Operation ID:** `chat_deleteScheduledMessage`

Deletes a pending scheduled message from the queue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `chat:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response if no message is found |

## Security

- **slackAuth**: chat:write:user, chat:write:bot
