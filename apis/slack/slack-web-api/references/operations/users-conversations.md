# GET /users.conversations

**Resource:** [users](../resources/users.md)
**Operation ID:** `users_conversations`

List conversations the calling user may access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `conversations:read` |
| `user` | query | string | No | Browse conversations by a specific user ID's membership. Non-public channels are restricted to those where the calling user shares membership. |
| `types` | query | string | No | Mix and match channel types by providing a comma-separated list of any combination of `public_channel`, `private_channel`, `mpim`, `im` |
| `exclude_archived` | query | boolean | No | Set to `true` to exclude archived channels from the list |
| `limit` | query | integer | No | The maximum number of items to return. Fewer than the requested number of items may be returned, even if the end of the list hasn't been reached. Must be an integer no larger than 1000. |
| `cursor` | query | string | No | Paginate through collections of data by setting the `cursor` parameter to a `next_cursor` attribute returned by a previous request's `response_metadata`. Default value fetches the first "page" of the collection. See [pagination](/docs/pagination) for more detail. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response with only public channels. Note how `num_members` and `is_member` are not returned like typical `conversations` objects. |
| default | Typical error response |

## Security

- **slackAuth**: channels:read, groups:read, im:read, mpim:read
