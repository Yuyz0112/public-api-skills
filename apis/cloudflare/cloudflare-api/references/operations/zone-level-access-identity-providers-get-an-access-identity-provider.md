# GET /zones/{zone_id}/access/identity_providers/{identity_provider_id}

**Resource:** [Zone-Level Access identity providers](../resources/Zone-Level-Access-identity-providers.md)
**Get an Access identity provider**
**Operation ID:** `zone-level-access-identity-providers-get-an-access-identity-provider`

Fetches a configured identity provider.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identity_provider_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access identity provider response |
| 4XX | Get an Access identity provider response failure |

**Success Response Schema:**

[access_identity-providers_components-schemas-single_response](../schemas/access/access-identity-providers-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
