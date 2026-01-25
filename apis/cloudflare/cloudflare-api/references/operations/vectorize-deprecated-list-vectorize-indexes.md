# GET /accounts/{account_id}/vectorize/indexes

**Resource:** [Vectorize Beta (Deprecated)](../resources/Vectorize-Beta-Deprecated.md)
**List Vectorize Indexes (Deprecated)**
**Operation ID:** `vectorize-(-deprecated)-list-vectorize-indexes`
⚠️ **Deprecated**

Returns a list of Vectorize Indexes

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Vectorize Index Response |
| 4XX | List Vectorize Index Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
