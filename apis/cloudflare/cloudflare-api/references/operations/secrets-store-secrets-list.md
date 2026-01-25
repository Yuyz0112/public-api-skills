# GET /accounts/{account_id}/secrets_store/stores/{store_id}/secrets

**Resource:** [Secrets Store](../resources/Secrets-Store.md)
**List store secrets**
**Operation ID:** `secrets-store-secrets-list`

Lists all store secrets

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secrets-store_account_identifier | Yes |  |
| `store_id` | path | secrets-store_store_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List store secrets response |
| 4XX | List store secrets response failure |

**Success Response Schema:**

[secrets-store_secrets_response_collection](../schemas/secrets-store/secrets-store-secrets-response-collection.md)

## Security

- **api_email**
- **api_key**
