# DELETE /api/v4/projects/{id}/boards/{board_id}/lists/{list_id}

**Resource:** [Boards](../resources/Boards.md)
**Delete a board list**
**Operation ID:** `deleteApiV4ProjectsIdBoardsBoardIdListsListId`

This feature was introduced in 8.13

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `board_id` | path | integer | Yes | The ID of a board |
| `list_id` | path | integer | Yes | The ID of a board list |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

