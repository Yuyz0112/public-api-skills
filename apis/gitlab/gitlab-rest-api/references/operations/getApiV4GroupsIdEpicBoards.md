# GET /api/v4/groups/{id}/epic_boards

**Resource:** [Epics](../resources/Epics.md)
**Get all group epic boards**
**Operation ID:** `getApiV4GroupsIdEpicBoards`

This feature was introduced in 15.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEpicBoard](../schemas/APIEntitiesEpicBoard/APIEntitiesEpicBoard.md)

