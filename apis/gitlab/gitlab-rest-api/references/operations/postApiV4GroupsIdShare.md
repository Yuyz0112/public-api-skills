# POST /api/v4/groups/{id}/share

**Resource:** [Groups](../resources/Groups.md)
**Share a group with a group**
**Operation ID:** `postApiV4GroupsIdShare`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesGroupDetail](../schemas/APIEntitiesGroupDetail/APIEntitiesGroupDetail.md)

