# GET /api/v4/groups/{id}/scim/identities

**Resource:** [Provider identities](../resources/Provider-identities.md)
**Get user identities for the provider**
**Operation ID:** `getApiV4GroupsIdScimIdentities`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIdentityDetail](../schemas/APIEntitiesIdentityDetail/APIEntitiesIdentityDetail.md)

