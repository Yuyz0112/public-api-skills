# POST /zones/{zone_id}/access/organizations/revoke_user

**Resource:** [Zone-Level Zero Trust organization](../resources/Zone-Level-Zero-Trust-organization.md)
**Revoke all Access tokens for a user**
**Operation ID:** `zone-level-zero-trust-organization-revoke-all-access-tokens-for-a-user`

Revokes a user's access across all applications.

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
| 200 | Revoke all Access tokens for a user response |
| 4xx | Revoke all Access tokens for a user response failure |

**Success Response Schema:**

[access_empty_response](../schemas/access/access-empty-response.md)

## Security

- **api_email**
- **api_key**
