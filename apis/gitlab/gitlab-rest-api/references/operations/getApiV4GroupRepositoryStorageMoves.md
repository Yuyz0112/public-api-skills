# GET /api/v4/group_repository_storage_moves

**Resource:** [group_repository_storage_moves](../resources/group-repository-storage-moves.md)
**Get a list of all group repository storage moves**
**Operation ID:** `getApiV4GroupRepositoryStorageMoves`

This feature was introduced in GitLab 13.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupsRepositoryStorageMove](../schemas/APIEntitiesGroupsRepositoryStorageMove/APIEntitiesGroupsRepositoryStorageMove.md)

