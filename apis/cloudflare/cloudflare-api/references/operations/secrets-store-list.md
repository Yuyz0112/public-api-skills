# GET /accounts/{account_id}/secrets_store/stores

**Resource:** [Secrets Store](../resources/Secrets-Store.md)
**List account stores**
**Operation ID:** `secrets-store-list`

Lists all the stores in an account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secrets-store_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List account stores response |
| 4XX | List account stores response failure |

**Success Response Schema:**

[secrets-store_stores_response_collection](../schemas/secrets-store/secrets-store-stores-response-collection.md)

## Security

- **api_email**
- **api_key**
