# GET /accounts/{account_id}/vectorize/v2/indexes/{index_name}/info

**Resource:** [Vectorize](../resources/Vectorize.md)
**Get Vectorize Index Info**
**Operation ID:** `vectorize-index-info`

Get information about a vectorize index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Vectorize Index Info Response |
| 4XX | Get Vectorize Index Info Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
