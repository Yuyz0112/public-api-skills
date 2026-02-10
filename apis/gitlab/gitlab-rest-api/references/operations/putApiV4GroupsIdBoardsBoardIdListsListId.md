# PUT /api/v4/groups/{id}/boards/{board_id}/lists/{list_id}

**Resource:** [Boards](../resources/Boards.md)
**Moves a board list to a new position**
**Operation ID:** `putApiV4GroupsIdBoardsBoardIdListsListId`

This feature was introduced in 10.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
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

