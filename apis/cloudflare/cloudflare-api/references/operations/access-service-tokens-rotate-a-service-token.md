# POST /accounts/{account_id}/access/service_tokens/{service_token_id}/rotate

**Resource:** [Access service tokens](../resources/Access-service-tokens.md)
**Rotate a service token**
**Operation ID:** `access-service-tokens-rotate-a-service-token`

Generates a new Client Secret for a service token and revokes the old one.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `service_token_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Rotate a service token response |
| 4XX | Rotate a service token response failure |

**Success Response Schema:**

[access_create_response](../schemas/access/access-create-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
