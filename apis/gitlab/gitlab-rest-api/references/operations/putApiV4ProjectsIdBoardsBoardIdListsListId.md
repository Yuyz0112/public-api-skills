# PUT /api/v4/projects/{id}/boards/{board_id}/lists/{list_id}

**Resource:** [Boards](../resources/Boards.md)
**Moves a board list to a new position**
**Operation ID:** `putApiV4ProjectsIdBoardsBoardIdListsListId`

This feature was introduced in 8.13

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `board_id` | path | integer | Yes | The ID of a board |
| `list_id` | path | integer | Yes | The ID of a list |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesList](../schemas/APIEntitiesList/APIEntitiesList.md)

