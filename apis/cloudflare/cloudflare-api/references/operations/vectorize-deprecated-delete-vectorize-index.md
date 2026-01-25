# DELETE /accounts/{account_id}/vectorize/indexes/{index_name}

**Resource:** [Vectorize Beta (Deprecated)](../resources/Vectorize-Beta-Deprecated.md)
**Delete Vectorize Index (Deprecated)**
**Operation ID:** `vectorize-(-deprecated)-delete-vectorize-index`
⚠️ **Deprecated**

Deletes the specified Vectorize Index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Vectorize Index Response |
| 4XX | Delete Vectorize Index Failure |

## Security

- **api_token**
- **api_email**
- **api_key**
