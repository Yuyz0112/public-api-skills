# POST /conversations.join

**Resource:** [conversations](../resources/conversations.md)
**Operation ID:** `conversations_join`

Joins an existing conversation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | No | Authentication token. Requires scope: `channels:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response if the conversation is archived and cannot be joined |

## Security

- **slackAuth**: channels:write
