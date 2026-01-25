# GET /zones/{zone_id}/access/organizations

**Resource:** [Zone-Level Zero Trust organization](../resources/Zone-Level-Zero-Trust-organization.md)
**Get your Zero Trust organization**
**Operation ID:** `zone-level-zero-trust-organization-get-your-zero-trust-organization`

Returns the configuration for your Zero Trust organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_organizations_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get your Zero Trust organization response |
| 4XX | Get your Zero Trust organization response failure |

**Success Response Schema:**

[access_organizations_components-schemas-single_response](../schemas/access/access-organizations-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
