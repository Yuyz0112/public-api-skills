# DELETE /accounts/{account_id}/secrets_store/stores/{store_id}/secrets/{secret_id}

**Resource:** [Secrets Store](../resources/Secrets-Store.md)
**Delete a secret**
**Operation ID:** `secrets-store-secret-delete-by-id`

Deletes a single secret

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secrets-store_account_identifier | Yes |  |
| `store_id` | path | secrets-store_store_identifier | Yes |  |
| `secret_id` | path | secrets-store_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | secret detail |
| 4XX | failure |

**Success Response Schema:**

[secrets-store_secret_response](../schemas/secrets-store/secrets-store-secret-response.md)

## Security

- **api_email**
- **api_key**
