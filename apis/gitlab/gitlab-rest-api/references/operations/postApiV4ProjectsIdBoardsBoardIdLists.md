# POST /api/v4/projects/{id}/boards/{board_id}/lists

**Resource:** [Boards](../resources/Boards.md)
**Create a new board list**
**Operation ID:** `postApiV4ProjectsIdBoardsBoardIdLists`

This feature was introduced in 8.13

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `board_id` | path | integer | Yes | The ID of a board |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesList](../schemas/APIEntitiesList/APIEntitiesList.md)

