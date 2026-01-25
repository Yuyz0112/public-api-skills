# POST /chat.delete

**Resource:** [chat](../resources/chat.md)
**Operation ID:** `chat_delete`

Deletes a message.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | No | Authentication token. Requires scope: `chat:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: chat:write:user, chat:write:bot
