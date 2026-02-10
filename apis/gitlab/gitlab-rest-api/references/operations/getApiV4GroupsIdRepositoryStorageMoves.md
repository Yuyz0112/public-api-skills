# GET /api/v4/groups/{id}/repository_storage_moves

**Resource:** [groups](../resources/groups.md)
**Get a list of all group repository storage moves**
**Operation ID:** `getApiV4GroupsIdRepositoryStorageMoves`

This feature was introduced in GitLab 13.9.

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

[APIEntitiesGroupsRepositoryStorageMove](../schemas/APIEntitiesGroupsRepositoryStorageMove/APIEntitiesGroupsRepositoryStorageMove.md)

