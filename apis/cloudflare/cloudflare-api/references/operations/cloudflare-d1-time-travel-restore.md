# POST /accounts/{account_id}/d1/database/{database_id}/time_travel/restore

**Resource:** [D1](../resources/D1.md)
**Restore D1 Database to a bookmark or point in time**
**Operation ID:** `cloudflare-d1-time-travel-restore`

Restores a D1 database to a previous point in time either via a bookmark or a timestamp.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | d1_account-identifier | Yes |  |
| `database_id` | path | d1_database-identifier | Yes |  |
| `bookmark` | query | d1_time-travel-bookmark | No | A bookmark to restore the database to. Required if `timestamp` is not provided. |
| `timestamp` | query | d1_time-travel-timestamp | No | An ISO 8601 timestamp to restore the database to. Required if `bookmark` is not provided. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Database restored successfully |
| 4XX | Restore operation failed |

## Security

- **api_token**
- **api_email**
- **api_key**
