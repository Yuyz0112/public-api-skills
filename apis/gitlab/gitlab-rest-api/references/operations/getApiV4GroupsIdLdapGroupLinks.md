# GET /api/v4/groups/{id}/ldap_group_links

**Resource:** [LDAP group links](../resources/LDAP-group-links.md)
**List LDAP group links**
**Operation ID:** `getApiV4GroupsIdLdapGroupLinks`

Get LDAP group links for a group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesLdapGroupLink](../schemas/APIEntitiesLdapGroupLink/APIEntitiesLdapGroupLink.md)

