# POST /accounts/{account_id}/vectorize/indexes

**Resource:** [Vectorize Beta (Deprecated)](../resources/Vectorize-Beta-Deprecated.md)
**Create Vectorize Index (Deprecated)**
**Operation ID:** `vectorize-(-deprecated)-create-vectorize-index`
⚠️ **Deprecated**

Creates and returns a new Vectorize Index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vectorize_create-index-request](../schemas/vectorize/vectorize-create-index-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Vectorize Index Response |
| 4XX | Create Vectorize Index Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
