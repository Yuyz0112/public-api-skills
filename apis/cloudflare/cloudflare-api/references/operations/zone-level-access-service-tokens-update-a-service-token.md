# PUT /zones/{zone_id}/access/service_tokens/{service_token_id}

**Resource:** [Zone-Level Access service tokens](../resources/Zone-Level-Access-service-tokens.md)
**Update a service token**
**Operation ID:** `zone-level-access-service-tokens-update-a-service-token`

Updates a configured service token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `service_token_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a service token response |
| 4XX | Update a service token response failure |

**Success Response Schema:**

[access_service-tokens_components-schemas-single_response](../schemas/access/access-service-tokens-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
