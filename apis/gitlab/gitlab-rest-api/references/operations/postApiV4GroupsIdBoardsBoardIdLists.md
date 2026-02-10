# POST /api/v4/groups/{id}/boards/{board_id}/lists

**Resource:** [Boards](../resources/Boards.md)
**Create a new board list**
**Operation ID:** `postApiV4GroupsIdBoardsBoardIdLists`

This feature was introduced in 10.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `board_id` | path | integer | Yes | The ID of a board |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesList](../schemas/APIEntitiesList/APIEntitiesList.md)

