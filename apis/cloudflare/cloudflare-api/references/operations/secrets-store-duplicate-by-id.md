# POST /accounts/{account_id}/secrets_store/stores/{store_id}/secrets/{secret_id}/duplicate

**Resource:** [Secrets Store](../resources/Secrets-Store.md)
**Duplicate Secret**
**Operation ID:** `secrets-store-duplicate-by-id`

Duplicates the secret, keeping the value

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secrets-store_account_identifier | Yes |  |
| `store_id` | path | secrets-store_store_identifier | Yes |  |
| `secret_id` | path | secrets-store_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [secrets-store_duplicateSecretObject](../schemas/secrets-store/secrets-store-duplicateSecretObject.md)

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
