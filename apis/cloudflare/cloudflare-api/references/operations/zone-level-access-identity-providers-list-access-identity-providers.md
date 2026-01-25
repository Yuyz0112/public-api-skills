# GET /zones/{zone_id}/access/identity_providers

**Resource:** [Zone-Level Access identity providers](../resources/Zone-Level-Access-identity-providers.md)
**List Access identity providers**
**Operation ID:** `zone-level-access-identity-providers-list-access-identity-providers`

Lists all configured identity providers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Access identity providers response |
| 4XX | List Access identity providers response failure |

**Success Response Schema:**

[access_identity-providers_components-schemas-response_collection](../schemas/access/access-identity-providers-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
