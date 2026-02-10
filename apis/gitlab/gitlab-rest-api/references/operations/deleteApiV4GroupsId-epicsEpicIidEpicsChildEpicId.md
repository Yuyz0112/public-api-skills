# DELETE /api/v4/groups/{id}/(-/)epics/{epic_iid}/epics/{child_epic_id}

**Resource:** [Epics](../resources/Epics.md)
**Remove epics relation**
**Operation ID:** `deleteApiV4GroupsId()epicsEpicIidEpicsChildEpicId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `epic_iid` | path | integer | Yes | The internal ID of an epic |
| `child_epic_id` | path | integer | Yes | The global ID of the child epic. Internal ID can't be used because they can conflict with epics from other groups. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 404 | Not found |

