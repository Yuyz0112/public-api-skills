# GET /reactions.list

**Resource:** [reactions](../resources/reactions.md)
**Operation ID:** `reactions_list`

Lists reactions made by a user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `reactions:read` |
| `user` | query | string | No | Show reactions made by this user. Defaults to the authed user. |
| `full` | query | boolean | No | If true always return the complete reaction list. |
| `count` | query | integer | No |  |
| `page` | query | integer | No |  |
| `cursor` | query | string | No | Parameter for pagination. Set `cursor` equal to the `next_cursor` attribute returned by the previous request's `response_metadata`. This parameter is optional, but pagination is mandatory: the default value simply fetches the first "page" of the collection. See [pagination](/docs/pagination) for more details. |
| `limit` | query | integer | No | The maximum number of items to return. Fewer than the requested number of items may be returned, even if the end of the list hasn't been reached. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: reactions:read
