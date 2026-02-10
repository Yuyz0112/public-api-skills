# GET /api/scim/v4/application/Groups

**Resource:** [SCIM and SAML](../resources/SCIM-and-SAML.md)
**Get SCIM groups**
**Operation ID:** `getApiScimV4ApplicationGroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter` | query | string | No | Filter string (e.g. displayName eq "Engineering") |
| `count` | query | integer | No | Number of results per page |
| `startIndex` | query | integer | No | Page offset |
| `excludedAttributes` | query | string | No | Comma-separated list of attributes to exclude |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesScimGroups](../schemas/APIEntitiesScimGroups/APIEntitiesScimGroups.md)

