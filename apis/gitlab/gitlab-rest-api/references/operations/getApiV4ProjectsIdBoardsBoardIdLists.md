# GET /api/v4/projects/{id}/boards/{board_id}/lists

**Resource:** [Boards](../resources/Boards.md)
**Get the lists of a project board**
**Operation ID:** `getApiV4ProjectsIdBoardsBoardIdLists`

Does not include `done` list. This feature was introduced in 8.13

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `board_id` | path | integer | Yes | The ID of a board |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesList](../schemas/APIEntitiesList/APIEntitiesList.md)

