# POST /zones/{zone_id}/access/identity_providers

**Resource:** [Zone-Level Access identity providers](../resources/Zone-Level-Access-identity-providers.md)
**Add an Access identity provider**
**Operation ID:** `zone-level-access-identity-providers-add-an-access-identity-provider`

Adds a new identity provider to Access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_schemas-identity-providers](../schemas/access/access-schemas-identity-providers.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Add an Access identity provider response |
| 4XX | Add an Access identity provider response failure |

**Success Response Schema:**

[access_identity-providers_components-schemas-single_response](../schemas/access/access-identity-providers-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
