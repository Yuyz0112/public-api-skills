# POST /conversations.create

**Resource:** [conversations](../resources/conversations.md)
**Operation ID:** `conversations_create`

Initiates a public or private channel-based conversation

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | No | Authentication token. Requires scope: `conversations:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | If successful, the command returns a rather stark [conversation object](/types/conversation) |
| default | Typical error response when name already in use |

## Security

- **slackAuth**: channels:write, groups:write, im:write, mpim:write
