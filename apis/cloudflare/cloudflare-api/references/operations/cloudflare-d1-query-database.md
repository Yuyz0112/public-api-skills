# POST /accounts/{account_id}/d1/database/{database_id}/query

**Resource:** [D1](../resources/D1.md)
**Query D1 Database**
**Operation ID:** `cloudflare-d1-query-database`

Returns the query result as an object.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | d1_account-identifier | Yes |  |
| `database_id` | path | d1_database-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [d1_batch-query](../schemas/d1/d1-batch-query.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Query response |
| 4XX | Query response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
