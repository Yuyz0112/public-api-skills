# DELETE /api/v4/groups/{id}/ldap_group_links/{provider}/{cn}

**Resource:** [LDAP group links](../resources/LDAP-group-links.md)
**Delete LDAP group link**
**Operation ID:** `deleteApiV4GroupsIdLdapGroupLinksProviderCn`

Deletes an LDAP group link for a specific LDAP provider.Deprecated. Scheduled for removal in a future release.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `cn` | path | string | Yes | The CN of a LDAP group |
| `provider` | path | string | Yes | LDAP provider for the LDAP group link |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

