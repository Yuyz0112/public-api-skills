# POST /accounts/{account_id}/vectorize/indexes/{index_name}/query

**Resource:** [Vectorize Beta (Deprecated)](../resources/Vectorize-Beta-Deprecated.md)
**Query Vectors (Deprecated)**
**Operation ID:** `vectorize-(-deprecated)-query-vector`
⚠️ **Deprecated**

Finds vectors closest to a given vector in an index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vectorize_index-query-request](../schemas/vectorize/vectorize-index-query-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Query Vectors Response |
| 4XX | Query Vectors Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
