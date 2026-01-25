# PUT /accounts/{account_id}/vectorize/indexes/{index_name}

**Resource:** [Vectorize Beta (Deprecated)](../resources/Vectorize-Beta-Deprecated.md)
**Update Vectorize Index (Deprecated)**
**Operation ID:** `vectorize-(-deprecated)-update-vectorize-index`
⚠️ **Deprecated**

Updates and returns the specified Vectorize Index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vectorize_update-index-request](../schemas/vectorize/vectorize-update-index-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Vectorize Index Response |
| 4XX | Update Vectorize Index Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
