# GET /stars.list

**Resource:** [stars](../resources/stars.md)
**Operation ID:** `stars_list`

Lists stars for a user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `stars:read` |
| `count` | query | string | No |  |
| `page` | query | string | No |  |
| `cursor` | query | string | No | Parameter for pagination. Set `cursor` equal to the `next_cursor` attribute returned by the previous request's `response_metadata`. This parameter is optional, but pagination is mandatory: the default value simply fetches the first "page" of the collection. See [pagination](/docs/pagination) for more details. |
| `limit` | query | integer | No | The maximum number of items to return. Fewer than the requested number of items may be returned, even if the end of the list hasn't been reached. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: stars:read
