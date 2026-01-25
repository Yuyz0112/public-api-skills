# GET /admin.conversations.search

**Resource:** [admin.conversations](../resources/admin-conversations.md)
**Operation ID:** `admin_conversations_search`

Search for public or private channels in an Enterprise organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.conversations:read` |
| `team_ids` | query | string | No | Comma separated string of team IDs, signifying the workspaces to search through. |
| `query` | query | string | No | Name of the the channel to query by. |
| `limit` | query | integer | No | Maximum number of items to be returned. Must be between 1 - 20 both inclusive. Default is 10. |
| `cursor` | query | string | No | Set `cursor` to `next_cursor` returned by the previous call to list items in the next page. |
| `search_channel_types` | query | string | No | The type of channel to include or exclude in the search. For example `private` will search private channels, while `private_exclude` will exclude them. For a full list of types, check the [Types section](#types). |
| `sort` | query | string | No | Possible values are `relevant` (search ranking based on what we think is closest), `name` (alphabetical), `member_count` (number of users in the channel), and `created` (date channel was created). You can optionally pair this with the `sort_dir` arg to change how it is sorted  |
| `sort_dir` | query | string | No | Sort direction. Possible values are `asc` for ascending order like (1, 2, 3) or (a, b, c), and `desc` for descending order like (3, 2, 1) or (c, b, a) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.conversations:read
