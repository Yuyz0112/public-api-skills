# GET /apps.permissions.users.list

**Resource:** [apps.permissions.users](../resources/apps-permissions-users.md)
**Operation ID:** `apps_permissions_users_list`

Returns list of user grants and corresponding scopes this app has on a team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `none` |
| `cursor` | query | string | No | Paginate through collections of data by setting the `cursor` parameter to a `next_cursor` attribute returned by a previous request's `response_metadata`. Default value fetches the first "page" of the collection. See [pagination](/docs/pagination) for more detail. |
| `limit` | query | integer | No | The maximum number of items to return. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical successful paginated response |
| default | Typical error response |

## Security

- **slackAuth**: none
