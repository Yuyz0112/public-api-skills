# PUT /api/v4/projects/{id}/boards/{board_id}

**Resource:** [Boards](../resources/Boards.md)
**Update a project board**
**Operation ID:** `putApiV4ProjectsIdBoardsBoardId`

This feature was introduced in 11.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBoard](../schemas/APIEntitiesBoard/APIEntitiesBoard.md)

