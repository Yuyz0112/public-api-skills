# GET /api/v4/groups/{id}/epic_boards/{board_id}

**Resource:** [Epics](../resources/Epics.md)
**Find a group epic board**
**Operation ID:** `getApiV4GroupsIdEpicBoardsBoardId`

This feature was introduced in 15.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `board_id` | path | integer | Yes | The ID of an epic board |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEpicBoard](../schemas/APIEntitiesEpicBoard/APIEntitiesEpicBoard.md)

