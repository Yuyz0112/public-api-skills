# GET /api/v4/groups/{id}/boards

**Resource:** [Boards](../resources/Boards.md)
**Get all group boards**
**Operation ID:** `getApiV4GroupsIdBoards`

This feature was introduced in 10.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBoard](../schemas/APIEntitiesBoard/APIEntitiesBoard.md)

