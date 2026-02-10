# GET /api/v4/groups/{id}/epics/{epic_iid}/related_epics

**Resource:** [Epics](../resources/Epics.md)
**Get related epics**
**Operation ID:** `getApiV4GroupsIdEpicsEpicIidRelatedEpics`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID or URL-encoded path of the group |
| `epic_iid` | path | integer | Yes | The internal ID of a group epic |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesRelatedEpic](../schemas/APIEntitiesRelatedEpic/APIEntitiesRelatedEpic.md)

