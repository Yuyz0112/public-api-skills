# GET /zones/{zone_id}/access/service_tokens/{service_token_id}

**Resource:** [Zone-Level Access service tokens](../resources/Zone-Level-Access-service-tokens.md)
**Get a service token**
**Operation ID:** `zone-level-access-service-tokens-get-a-service-token`

Fetches a single service token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `service_token_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a service token response |
| 4XX | Get a service token response failure |

**Success Response Schema:**

[access_service-tokens_components-schemas-single_response](../schemas/access/access-service-tokens-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
