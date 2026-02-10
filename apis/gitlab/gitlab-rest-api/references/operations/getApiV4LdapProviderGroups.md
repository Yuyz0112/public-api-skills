# GET /api/v4/ldap/{provider}/groups

**Resource:** [LDAP groups](../resources/LDAP-groups.md)
**List LDAP groups by the requested provider**
**Operation ID:** `getApiV4LdapProviderGroups`

Limit size to 20 of them.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | Search for a specific LDAP group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesLdapGroup](../schemas/APIEntitiesLdapGroup/APIEntitiesLdapGroup.md)

