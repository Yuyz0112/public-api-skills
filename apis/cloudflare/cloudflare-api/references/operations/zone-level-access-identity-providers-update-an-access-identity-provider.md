# PUT /zones/{zone_id}/access/identity_providers/{identity_provider_id}

**Resource:** [Zone-Level Access identity providers](../resources/Zone-Level-Access-identity-providers.md)
**Update an Access identity provider**
**Operation ID:** `zone-level-access-identity-providers-update-an-access-identity-provider`

Updates a configured identity provider.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identity_provider_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_schemas-identity-providers](../schemas/access/access-schemas-identity-providers.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an Access identity provider response |
| 4XX | Update an Access identity provider response failure |

**Success Response Schema:**

[access_identity-providers_components-schemas-single_response](../schemas/access/access-identity-providers-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
