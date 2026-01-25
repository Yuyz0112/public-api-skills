# POST /accounts/{account_id}/vectorize/v2/indexes/{index_name}/metadata_index/delete

**Resource:** [Vectorize](../resources/Vectorize.md)
**Delete Metadata Index**
**Operation ID:** `vectorize-delete-metadata-index`

Allow Vectorize to delete the specified metadata index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vectorize_delete-metadata-index-request](../schemas/vectorize/vectorize-delete-metadata-index-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Metadata Index Response |
| 4XX | Delete Metadata Index Failure |

## Security

- **api_token**
- **api_email**
- **api_key**
