# PUT /accounts/{account_id}/d1/database/{database_id}

**Resource:** [D1](../resources/D1.md)
**Update D1 Database**
**Operation ID:** `cloudflare-d1-update-database`

Updates the specified D1 database.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | d1_account-identifier | Yes |  |
| `database_id` | path | d1_database-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [d1_database-update-request-body](../schemas/d1/d1-database-update-request-body.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Database details response |
| 4XX | Update D1 database response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
