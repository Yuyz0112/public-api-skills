# DELETE /api/v4/groups/{id}/boards/{board_id}/lists/{list_id}

**Resource:** [Boards](../resources/Boards.md)
**Delete a board list**
**Operation ID:** `deleteApiV4GroupsIdBoardsBoardIdListsListId`

This feature was introduced in 10.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `board_id` | path | integer | Yes | The ID of a board |
| `list_id` | path | integer | Yes | The ID of a board list |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

