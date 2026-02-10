# GET /api/v4/groups/{id}/saml_group_links

**Resource:** [SCIM and SAML](../resources/SCIM-and-SAML.md)
**Lists SAML group links**
**Operation ID:** `getApiV4GroupsIdSamlGroupLinks`

Get SAML group links for a group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSamlGroupLink](../schemas/APIEntitiesSamlGroupLink/APIEntitiesSamlGroupLink.md)

