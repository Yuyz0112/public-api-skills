# GET /accounts/{account_id}/secrets_store/quota

**Resource:** [Secrets Store](../resources/Secrets-Store.md)
**View secret usage**
**Operation ID:** `secrets-store-quota`

Lists the number of secrets used in the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secrets-store_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Usage and quota |
| 4XX | List store secrets response failure |

**Success Response Schema:**

[secrets-store_quota_response](../schemas/secrets-store/secrets-store-quota-response.md)

## Security

- **api_email**
- **api_key**
