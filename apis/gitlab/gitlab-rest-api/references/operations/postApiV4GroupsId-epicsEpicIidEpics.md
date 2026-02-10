# POST /api/v4/groups/{id}/(-/)epics/{epic_iid}/epics

**Resource:** [Epics](../resources/Epics.md)
**Create and relate epic to a parent**
**Operation ID:** `postApiV4GroupsId()epicsEpicIidEpics`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `epic_iid` | path | integer | Yes | The internal ID of an epic |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 409 | Conflict |

**Success Response Schema:**

[APIEntitiesEpic](../schemas/APIEntitiesEpic/APIEntitiesEpic.md)

