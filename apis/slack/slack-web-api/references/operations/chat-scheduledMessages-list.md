# GET /chat.scheduledMessages.list

**Resource:** [chat.scheduledMessages](../resources/chat-scheduledMessages.md)
**Operation ID:** `chat_scheduledMessages_list`

Returns a list of scheduled messages.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | No | Authentication token. Requires scope: `none` |
| `channel` | query | string | No | The channel of the scheduled messages |
| `latest` | query | number | No | A UNIX timestamp of the latest value in the time range |
| `oldest` | query | number | No | A UNIX timestamp of the oldest value in the time range |
| `limit` | query | integer | No | Maximum number of original entries to return. |
| `cursor` | query | string | No | For pagination purposes, this is the `cursor` value returned from a previous call to `chat.scheduledmessages.list` indicating where you want to start this call from. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response if the channel passed is invalid |

## Security

- **slackAuth**: none
