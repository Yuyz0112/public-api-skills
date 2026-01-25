# POST /accounts/{account_id}/vectorize/v2/indexes/{index_name}/get_by_ids

**Resource:** [Vectorize](../resources/Vectorize.md)
**Get Vectors By Identifier**
**Operation ID:** `vectorize-get-vectors-by-id`

Get a set of vectors from an index by their vector identifiers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vectorize_index-get-vectors-by-id-request](../schemas/vectorize/vectorize-index-get-vectors-by-id-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Vectors By Identifier Response |
| 4XX | Get Vectors By Identifier Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
