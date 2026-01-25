# GET /chat.getPermalink

**Resource:** [chat](../resources/chat.md)
**Operation ID:** `chat_getPermalink`

Retrieve a permalink URL for a specific extant message

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `none` |
| `channel` | query | string | Yes | The ID of the conversation or channel containing the message |
| `message_ts` | query | string | Yes | A message's `ts` value, uniquely identifying it within a channel |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Standard success response |
| default | Error response when channel cannot be found |

## Security

- **slackAuth**: none
