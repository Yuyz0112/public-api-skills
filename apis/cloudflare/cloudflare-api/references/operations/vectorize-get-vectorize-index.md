# GET /accounts/{account_id}/vectorize/v2/indexes/{index_name}

**Resource:** [Vectorize](../resources/Vectorize.md)
**Get Vectorize Index**
**Operation ID:** `vectorize-get-vectorize-index`

Returns the specified Vectorize Index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Vectorize Index Response |
| 4XX | Get Vectorize Index Failure |

## Security

- **api_token**
- **api_email**
- **api_key**
