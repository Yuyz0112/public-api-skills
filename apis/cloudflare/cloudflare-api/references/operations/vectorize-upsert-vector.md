# POST /accounts/{account_id}/vectorize/v2/indexes/{index_name}/upsert

**Resource:** [Vectorize](../resources/Vectorize.md)
**Upsert Vectors**
**Operation ID:** `vectorize-upsert-vector`

Upserts vectors into the specified index, creating them if they do not exist and returns a mutation id corresponding to the vectors enqueued for upsertion.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |
| `unparsable-behavior` | query | enum: error, discard | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-ndjson`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upsert Vectors Response |
| 4XX | Upsert Vectors Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
