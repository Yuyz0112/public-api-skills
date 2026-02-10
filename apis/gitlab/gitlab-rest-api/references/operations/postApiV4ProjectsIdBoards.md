# POST /api/v4/projects/{id}/boards

**Resource:** [Boards](../resources/Boards.md)
**Create a project board**
**Operation ID:** `postApiV4ProjectsIdBoards`

This feature was introduced in 10.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesBoard](../schemas/APIEntitiesBoard/APIEntitiesBoard.md)

