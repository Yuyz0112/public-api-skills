# GET /api/v4/group_repository_storage_moves/{repository_storage_move_id}

**Resource:** [group_repository_storage_moves](../resources/group-repository-storage-moves.md)
**Get a group repository storage move**
**Operation ID:** `getApiV4GroupRepositoryStorageMovesRepositoryStorageMoveId`

This feature was introduced in GitLab 13.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_storage_move_id` | path | integer | Yes | The ID of a group repository storage move |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupsRepositoryStorageMove](../schemas/APIEntitiesGroupsRepositoryStorageMove/APIEntitiesGroupsRepositoryStorageMove.md)

