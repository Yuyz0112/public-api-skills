# POST /accounts/{account_id}/d1/database

**Resource:** [D1](../resources/D1.md)
**Create D1 Database**
**Operation ID:** `cloudflare-d1-create-database`

Returns the created D1 database.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | d1_account-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the created D1 database's metadata |
| 4XX | Database details response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
