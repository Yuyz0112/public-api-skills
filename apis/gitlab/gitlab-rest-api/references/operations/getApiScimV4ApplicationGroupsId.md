# GET /api/scim/v4/application/Groups/{id}

**Resource:** [SCIM and SAML](../resources/SCIM-and-SAML.md)
**Get a SCIM group**
**Operation ID:** `getApiScimV4ApplicationGroupsId`

Retrieves a SCIM group by its ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The SCIM group ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesScimGroup](../schemas/APIEntitiesScimGroup/APIEntitiesScimGroup.md)

