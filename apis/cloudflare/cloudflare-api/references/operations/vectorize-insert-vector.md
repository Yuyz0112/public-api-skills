# POST /accounts/{account_id}/vectorize/v2/indexes/{index_name}/insert

**Resource:** [Vectorize](../resources/Vectorize.md)
**Insert Vectors**
**Operation ID:** `vectorize-insert-vector`

Inserts vectors into the specified index and returns a mutation id corresponding to the vectors enqueued for insertion.

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
| 200 | Insert Vectors Response |
| 4XX | Insert Vectors Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
