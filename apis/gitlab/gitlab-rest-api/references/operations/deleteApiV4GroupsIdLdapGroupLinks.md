# DELETE /api/v4/groups/{id}/ldap_group_links

**Resource:** [LDAP group links](../resources/LDAP-group-links.md)
**Delete LDAP group link with CN or filter**
**Operation ID:** `deleteApiV4GroupsIdLdapGroupLinks`

Deletes an LDAP group link using a CN or filter.Deleting by filter is only supported in the Premium tier and above.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `cn` | query | string | No | The CN of a LDAP group |
| `filter` | query | string | No | The LDAP filter for the group |
| `provider` | query | string | Yes | LDAP provider for the LDAP group link |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

