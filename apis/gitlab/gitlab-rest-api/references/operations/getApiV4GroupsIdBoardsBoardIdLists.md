# GET /api/v4/groups/{id}/boards/{board_id}/lists

**Resource:** [Boards](../resources/Boards.md)
**Get the lists of a group board**
**Operation ID:** `getApiV4GroupsIdBoardsBoardIdLists`

Does not include backlog and closed lists. This feature was introduced in 10.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `board_id` | path | integer | Yes | The ID of a board |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesList](../schemas/APIEntitiesList/APIEntitiesList.md)

