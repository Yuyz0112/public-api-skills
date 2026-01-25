# GET /accounts/{account_id}/vectorize/v2/indexes

**Resource:** [Vectorize](../resources/Vectorize.md)
**List Vectorize Indexes**
**Operation ID:** `vectorize-list-vectorize-indexes`

Returns a list of Vectorize Indexes

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Vectorize Index Response |
| 4XX | List Vectorize Index Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
