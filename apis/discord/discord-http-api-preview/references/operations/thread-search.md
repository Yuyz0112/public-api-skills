# GET /channels/{channel_id}/threads/search

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `thread_search`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No |  |
| `slop` | query | integer | No |  |
| `min_id` | query | SnowflakeType | No |  |
| `max_id` | query | SnowflakeType | No |  |
| `tag` | query | any | No |  |
| `tag_setting` | query | ThreadSearchTagSetting | No |  |
| `archived` | query | boolean | No |  |
| `sort_by` | query | ThreadSortingMode | No |  |
| `sort_order` | query | SortingOrder | No |  |
| `limit` | query | integer | No |  |
| `offset` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for thread_search |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ThreadSearchResponse](../schemas/Thread/ThreadSearchResponse.md)

## Security

- **BotToken**
