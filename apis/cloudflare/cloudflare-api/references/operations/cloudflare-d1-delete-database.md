# DELETE /accounts/{account_id}/d1/database/{database_id}

**Resource:** [D1](../resources/D1.md)
**Delete D1 Database**
**Operation ID:** `cloudflare-d1-delete-database`

Deletes the specified D1 database.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | d1_account-identifier | Yes |  |
| `database_id` | path | d1_database-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete D1 database response |
| 4XX | Delete D1 database response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
