# POST /zones/{zone_id}/access/organizations

**Resource:** [Zone-Level Zero Trust organization](../resources/Zone-Level-Zero-Trust-organization.md)
**Create your Zero Trust organization**
**Operation ID:** `zone-level-zero-trust-organization-create-your-zero-trust-organization`

Sets up a Zero Trust organization for your account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_organizations_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create your Zero Trust organization response |
| 4XX | Create your Zero Trust organization response failure |

**Success Response Schema:**

[access_organizations_components-schemas-single_response](../schemas/access/access-organizations-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
