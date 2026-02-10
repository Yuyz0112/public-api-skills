# GET /api/v4/groups/{id}/(-/)epics/{epic_iid}/epics

**Resource:** [Epics](../resources/Epics.md)
**Get related epics**
**Operation ID:** `getApiV4GroupsId()epicsEpicIidEpics`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `epic_iid` | path | integer | Yes | The internal ID of an epic |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEpic](../schemas/APIEntitiesEpic/APIEntitiesEpic.md)

