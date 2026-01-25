# POST /accounts/{account_id}/vectorize/indexes/{index_name}/delete-by-ids

**Resource:** [Vectorize Beta (Deprecated)](../resources/Vectorize-Beta-Deprecated.md)
**Delete Vectors By Identifier (Deprecated)**
**Operation ID:** `vectorize-(-deprecated)-delete-vectors-by-id`
⚠️ **Deprecated**

Delete a set of vectors from an index by their vector identifiers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vectorize_index-delete-vectors-by-id-request](../schemas/vectorize/vectorize-index-delete-vectors-by-id-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Vector Identifiers Response |
| 4XX | Delete Vector Identifiers Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
