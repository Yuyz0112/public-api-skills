# POST /api/v4/groups/{id}/epics/{epic_iid}/related_epics

**Resource:** [Epics](../resources/Epics.md)
**Relate epics**
**Operation ID:** `postApiV4GroupsIdEpicsEpicIidRelatedEpics`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID or URL-encoded path of the group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |
| 409 | Conflict |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesRelatedEpicLink](../schemas/APIEntitiesRelatedEpicLink/APIEntitiesRelatedEpicLink.md)

