# POST /api/v4/groups/{id}/boards

**Resource:** [Boards](../resources/Boards.md)
**Create a group board**
**Operation ID:** `postApiV4GroupsIdBoards`

This feature was introduced in 10.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesBoard](../schemas/APIEntitiesBoard/APIEntitiesBoard.md)

