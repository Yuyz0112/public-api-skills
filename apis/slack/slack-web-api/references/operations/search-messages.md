# GET /search.messages

**Resource:** [search](../resources/search.md)
**Operation ID:** `search_messages`

Searches for messages matching a query.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `search:read` |
| `count` | query | integer | No | Pass the number of results you want per "page". Maximum of `100`. |
| `highlight` | query | boolean | No | Pass a value of `true` to enable query highlight markers (see below). |
| `page` | query | integer | No |  |
| `query` | query | string | Yes | Search query. |
| `sort` | query | string | No | Return matches sorted by either `score` or `timestamp`. |
| `sort_dir` | query | string | No | Change sort direction to ascending (`asc`) or descending (`desc`). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: search:read
