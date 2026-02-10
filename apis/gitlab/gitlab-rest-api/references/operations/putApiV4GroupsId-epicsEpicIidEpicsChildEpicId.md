# PUT /api/v4/groups/{id}/(-/)epics/{epic_iid}/epics/{child_epic_id}

**Resource:** [Epics](../resources/Epics.md)
**Reorder child epics**
**Operation ID:** `putApiV4GroupsId()epicsEpicIidEpicsChildEpicId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `epic_iid` | path | integer | Yes | The internal ID of an epic |
| `child_epic_id` | path | integer | Yes | The global ID of the child epic. Internal ID can't be used because they can conflict with epics from other groups. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEpic](../schemas/APIEntitiesEpic/APIEntitiesEpic.md)

