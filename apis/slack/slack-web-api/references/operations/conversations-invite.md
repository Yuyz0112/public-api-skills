# POST /conversations.invite

**Resource:** [conversations](../resources/conversations.md)
**Operation ID:** `conversations_invite`

Invites users to a channel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | No | Authentication token. Requires scope: `conversations:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response when an invitation is extended |
| default | Typical error response when an invite is attempted on a conversation type that does not support it |

## Security

- **slackAuth**: channels:write, groups:write, im:write, mpim:write
