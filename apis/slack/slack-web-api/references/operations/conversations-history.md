# GET /conversations.history

**Resource:** [conversations](../resources/conversations.md)
**Operation ID:** `conversations_history`

Fetches a conversation's history of messages and events.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `conversations:history` |
| `channel` | query | string | No | Conversation ID to fetch history for. |
| `latest` | query | number | No | End of time range of messages to include in results. |
| `oldest` | query | number | No | Start of time range of messages to include in results. |
| `inclusive` | query | boolean | No | Include messages with latest or oldest timestamp in results only when either timestamp is specified. |
| `limit` | query | integer | No | The maximum number of items to return. Fewer than the requested number of items may be returned, even if the end of the users list hasn't been reached. |
| `cursor` | query | string | No | Paginate through collections of data by setting the `cursor` parameter to a `next_cursor` attribute returned by a previous request's `response_metadata`. Default value fetches the first "page" of the collection. See [pagination](/docs/pagination) for more detail. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response containing a channel's messages |
| default | Typical error response |

## Security

- **slackAuth**: channels:history, groups:history, im:history, mpim:history
