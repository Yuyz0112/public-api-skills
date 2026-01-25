# GET /accounts/{account_id}/d1/database/{database_id}/time_travel/bookmark

**Resource:** [D1](../resources/D1.md)
**Get D1 database bookmark**
**Operation ID:** `cloudflare-d1-time-travel-get-bookmark`

Retrieves the current bookmark, or the nearest bookmark at or before a provided timestamp.
Bookmarks can be used with the restore endpoint to revert the database to a previous point in time.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | d1_account-identifier | Yes |  |
| `database_id` | path | d1_database-identifier | Yes |  |
| `timestamp` | query | d1_time-travel-timestamp | No | An optional ISO 8601 timestamp. If provided, returns the nearest available bookmark at or before this timestamp. If omitted, returns the current bookmark. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Bookmark retrieved successfully |
| 4XX | Failed to retrieve bookmark |

## Security

- **api_token**
- **api_email**
- **api_key**
