# POST /api/v4/groups/{id}/archive

**Resource:** [Groups](../resources/Groups.md)
**Archive a group**
**Operation ID:** `postApiV4GroupsIdArchive`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |

**Success Response Schema:**

[APIEntitiesGroup](../schemas/APIEntitiesGroup/APIEntitiesGroup.md)

