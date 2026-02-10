# GET /api/v4/groups/{id}/saml_group_links/{saml_group_name}

**Resource:** [SCIM and SAML](../resources/SCIM-and-SAML.md)
**Get SAML group link**
**Operation ID:** `getApiV4GroupsIdSamlGroupLinksSamlGroupName`

Get a SAML group link for the group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the group |
| `saml_group_name` | path | string | Yes | Name of an SAML group |
| `provider` | query | string | No | Provider string to disambiguate when multiple links exist with same name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |
| 422 | Multiple links found, provider parameter required |

**Success Response Schema:**

[APIEntitiesSamlGroupLink](../schemas/APIEntitiesSamlGroupLink/APIEntitiesSamlGroupLink.md)

