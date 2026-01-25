# DELETE /accounts/{account_id}/secrets_store/stores/{store_id}

**Resource:** [Secrets Store](../resources/Secrets-Store.md)
**Delete a store**
**Operation ID:** `secrets-store-delete-by-id`

Deletes a single store

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secrets-store_account_identifier | Yes |  |
| `store_id` | path | secrets-store_store_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | store details |
| 4XX | failure |

**Success Response Schema:**

[secrets-store_store_response](../schemas/secrets-store/secrets-store-store-response.md)

## Security

- **api_email**
- **api_key**
