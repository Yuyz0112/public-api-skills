# POST /api/v4/groups/{id}/saml_group_links

**Resource:** [SCIM and SAML](../resources/SCIM-and-SAML.md)
**Add SAML group link**
**Operation ID:** `postApiV4GroupsIdSamlGroupLinks`

Add a SAML group link for a group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesSamlGroupLink](../schemas/APIEntitiesSamlGroupLink/APIEntitiesSamlGroupLink.md)

