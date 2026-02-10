# GET /api/v4/groups/{id}/repository_storage_moves/{repository_storage_move_id}

**Resource:** [groups](../resources/groups.md)
**Get a group repository storage move**
**Operation ID:** `getApiV4GroupsIdRepositoryStorageMovesRepositoryStorageMoveId`

This feature was introduced in GitLab 13.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `repository_storage_move_id` | path | integer | Yes | The ID of a group repository storage move |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupsRepositoryStorageMove](../schemas/APIEntitiesGroupsRepositoryStorageMove/APIEntitiesGroupsRepositoryStorageMove.md)

