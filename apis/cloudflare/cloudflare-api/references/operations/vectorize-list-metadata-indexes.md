# GET /accounts/{account_id}/vectorize/v2/indexes/{index_name}/metadata_index/list

**Resource:** [Vectorize](../resources/Vectorize.md)
**List Metadata Indexes**
**Operation ID:** `vectorize-list-metadata-indexes`

List Metadata Indexes for the specified Vectorize Index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Metadata Index Response |
| 4XX | List Metadata Index Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
