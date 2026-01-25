# POST /accounts/{account_id}/secrets_store/stores/{store_id}/secrets

**Resource:** [Secrets Store](../resources/Secrets-Store.md)
**Create a secret**
**Operation ID:** `secrets-store-secret-create`

Creates a secret in the account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secrets-store_account_identifier | Yes |  |
| `store_id` | path | secrets-store_store_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [secrets-store_createSecretObject](../schemas/secrets-store/secrets-store-createSecretObject.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | secret detail |
| 4XX | List store secrets response failure |

**Success Response Schema:**

[secrets-store_secrets_response_collection](../schemas/secrets-store/secrets-store-secrets-response-collection.md)

## Security

- **api_email**
- **api_key**
