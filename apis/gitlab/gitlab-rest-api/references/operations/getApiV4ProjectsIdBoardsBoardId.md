# GET /api/v4/projects/{id}/boards/{board_id}

**Resource:** [Boards](../resources/Boards.md)
**Find a project board**
**Operation ID:** `getApiV4ProjectsIdBoardsBoardId`

This feature was introduced in 10.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBoard](../schemas/APIEntitiesBoard/APIEntitiesBoard.md)

