# GET /accounts/{account_id}/d1/database/{database_id}

**Resource:** [D1](../resources/D1.md)
**Get D1 Database**
**Operation ID:** `cloudflare-d1-get-database`

Returns the specified D1 database.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | d1_account-identifier | Yes |  |
| `database_id` | path | any | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Database details response |
| 4XX | Database details response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
