# POST /accounts/{account_id}/vectorize/indexes/{index_name}/upsert

**Resource:** [Vectorize Beta (Deprecated)](../resources/Vectorize-Beta-Deprecated.md)
**Upsert Vectors (Deprecated)**
**Operation ID:** `vectorize-(-deprecated)-upsert-vector`
⚠️ **Deprecated**

Upserts vectors into the specified index, creating them if they do not exist and returns the count of values and ids successfully inserted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

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
