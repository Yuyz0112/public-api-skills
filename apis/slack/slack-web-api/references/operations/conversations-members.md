# GET /conversations.members

**Resource:** [conversations](../resources/conversations.md)
**Operation ID:** `conversations_members`

Retrieve members of a conversation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `conversations:read` |
| `channel` | query | string | No | ID of the conversation to retrieve members for |
| `limit` | query | integer | No | The maximum number of items to return. Fewer than the requested number of items may be returned, even if the end of the users list hasn't been reached. |
| `cursor` | query | string | No | Paginate through collections of data by setting the `cursor` parameter to a `next_cursor` attribute returned by a previous request's `response_metadata`. Default value fetches the first "page" of the collection. See [pagination](/docs/pagination) for more detail. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical paginated success response |
| default | Typical error response when an invalid cursor is provided |

## Security

- **slackAuth**: channels:read, groups:read, im:read, mpim:read
