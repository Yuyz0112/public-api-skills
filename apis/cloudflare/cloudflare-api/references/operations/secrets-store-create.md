# POST /accounts/{account_id}/secrets_store/stores

**Resource:** [Secrets Store](../resources/Secrets-Store.md)
**Create a store**
**Operation ID:** `secrets-store-create`

Creates a store in the account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secrets-store_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [secrets-store_createStoreObject](../schemas/secrets-store/secrets-store-createStoreObject.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | store details |
| 4XX | List store secrets response failure |

**Success Response Schema:**

[secrets-store_stores_response_collection](../schemas/secrets-store/secrets-store-stores-response-collection.md)

## Security

- **api_email**
- **api_key**
