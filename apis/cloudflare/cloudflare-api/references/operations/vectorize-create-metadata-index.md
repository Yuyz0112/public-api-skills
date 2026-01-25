# POST /accounts/{account_id}/vectorize/v2/indexes/{index_name}/metadata_index/create

**Resource:** [Vectorize](../resources/Vectorize.md)
**Create Metadata Index**
**Operation ID:** `vectorize-create-metadata-index`

Enable metadata filtering based on metadata property. Limited to 10 properties.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vectorize_create-metadata-index-request](../schemas/vectorize/vectorize-create-metadata-index-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Metadata Index Response |
| 4XX | Create Metadata Index Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
