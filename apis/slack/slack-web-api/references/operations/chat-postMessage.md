# POST /chat.postMessage

**Resource:** [chat](../resources/chat.md)
**Operation ID:** `chat_postMessage`

Sends a message to a channel.

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
| default | Typical error response if too many attachments are included |

## Security

- **slackAuth**: chat:write:user, chat:write:bot
