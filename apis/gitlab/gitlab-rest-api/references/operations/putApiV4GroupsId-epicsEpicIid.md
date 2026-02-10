# PUT /api/v4/groups/{id}/(-/)epics/{epic_iid}

**Resource:** [Epics](../resources/Epics.md)
**Update an epic**
**Operation ID:** `putApiV4GroupsId()epicsEpicIid`

Updates an epic

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `epic_iid` | path | integer | Yes | The internal ID of an epic |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEpic](../schemas/APIEntitiesEpic/APIEntitiesEpic.md)

