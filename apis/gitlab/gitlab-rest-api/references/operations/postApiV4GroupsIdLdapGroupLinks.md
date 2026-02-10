# POST /api/v4/groups/{id}/ldap_group_links

**Resource:** [LDAP group links](../resources/LDAP-group-links.md)
**Add LDAP group link with CN or filter**
**Operation ID:** `postApiV4GroupsIdLdapGroupLinks`

Adds an LDAP group link using a CN or filter.Adding a group link by filter is only supported in the Premium tier and above.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

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

[APIEntitiesLdapGroupLink](../schemas/APIEntitiesLdapGroupLink/APIEntitiesLdapGroupLink.md)

