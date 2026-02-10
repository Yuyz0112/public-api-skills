# PUT /api/v4/groups/{id}/boards/{board_id}

**Resource:** [Boards](../resources/Boards.md)
**Update a group board**
**Operation ID:** `putApiV4GroupsIdBoardsBoardId`

This feature was introduced in 11.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBoard](../schemas/APIEntitiesBoard/APIEntitiesBoard.md)

