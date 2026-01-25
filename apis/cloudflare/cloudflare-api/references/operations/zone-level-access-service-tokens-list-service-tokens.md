# GET /zones/{zone_id}/access/service_tokens

**Resource:** [Zone-Level Access service tokens](../resources/Zone-Level-Access-service-tokens.md)
**List service tokens**
**Operation ID:** `zone-level-access-service-tokens-list-service-tokens`

Lists all service tokens.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List service tokens response |
| 4XX | List service tokens response failure |

**Success Response Schema:**

[access_service-tokens_components-schemas-response_collection](../schemas/access/access-service-tokens-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
