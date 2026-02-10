# GET /api/v4/groups/{id}/boards/{board_id}

**Resource:** [Boards](../resources/Boards.md)
**Find a group board**
**Operation ID:** `getApiV4GroupsIdBoardsBoardId`

This feature was introduced in 10.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBoard](../schemas/APIEntitiesBoard/APIEntitiesBoard.md)

