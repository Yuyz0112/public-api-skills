# POST /accounts/{account_id}/vectorize/v2/indexes/{index_name}/query

**Resource:** [Vectorize](../resources/Vectorize.md)
**Query Vectors**
**Operation ID:** `vectorize-query-vector`

Finds vectors closest to a given vector in an index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vectorize_index-query-v2-request](../schemas/vectorize/vectorize-index-query-v2-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Query Vectors Response |
| 4XX | Query Vectors Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
