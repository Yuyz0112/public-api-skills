# GET /conversations.info

**Resource:** [conversations](../resources/conversations.md)
**Operation ID:** `conversations_info`

Retrieve information about a conversation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `conversations:read` |
| `channel` | query | string | No | Conversation ID to learn more about |
| `include_locale` | query | boolean | No | Set this to `true` to receive the locale for this conversation. Defaults to `false` |
| `include_num_members` | query | boolean | No | Set to `true` to include the member count for the specified conversation. Defaults to `false` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response for a public channel. (Also, a response from a private channel and a multi-party IM is very similar to this example.) |
| default | Typical error response when a channel cannot be found |

## Security

- **slackAuth**: channels:read, groups:read, im:read, mpim:read
