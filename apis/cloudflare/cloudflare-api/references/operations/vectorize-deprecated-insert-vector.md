# POST /accounts/{account_id}/vectorize/indexes/{index_name}/insert

**Resource:** [Vectorize Beta (Deprecated)](../resources/Vectorize-Beta-Deprecated.md)
**Insert Vectors (Deprecated)**
**Operation ID:** `vectorize-(-deprecated)-insert-vector`
⚠️ **Deprecated**

Inserts vectors into the specified index and returns the count of the vectors successfully inserted.

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
