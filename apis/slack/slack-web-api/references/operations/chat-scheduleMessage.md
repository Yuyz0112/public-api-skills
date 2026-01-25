# POST /chat.scheduleMessage

**Resource:** [chat](../resources/chat.md)
**Operation ID:** `chat_scheduleMessage`

Schedules a message to be sent to a channel.

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
| default | Typical error response if the `post_at` is invalid (ex. in the past or too far into the future) |

## Security

- **slackAuth**: chat:write:user, chat:write:bot
