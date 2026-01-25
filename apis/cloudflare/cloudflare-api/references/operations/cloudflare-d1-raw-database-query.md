# POST /accounts/{account_id}/d1/database/{database_id}/raw

**Resource:** [D1](../resources/D1.md)
**Raw D1 Database query**
**Operation ID:** `cloudflare-d1-raw-database-query`

Returns the query result rows as arrays rather than objects. This is a performance-optimized version of the /query endpoint.

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
| 200 | Raw query response |
| 4XX | Query response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
