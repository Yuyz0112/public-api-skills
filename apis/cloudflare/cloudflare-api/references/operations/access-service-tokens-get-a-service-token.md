# GET /accounts/{account_id}/access/service_tokens/{service_token_id}

**Resource:** [Access service tokens](../resources/Access-service-tokens.md)
**Get a service token**
**Operation ID:** `access-service-tokens-get-a-service-token`

Fetches a single service token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `service_token_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a service token response |
| 4XX | Get a service token response failure |

**Success Response Schema:**

[access_schemas-single_response](../schemas/access/access-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
