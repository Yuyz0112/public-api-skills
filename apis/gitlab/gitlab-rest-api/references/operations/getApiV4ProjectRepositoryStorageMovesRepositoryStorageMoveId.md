# GET /api/v4/project_repository_storage_moves/{repository_storage_move_id}

**Resource:** [project_repository_storage_moves](../resources/project-repository-storage-moves.md)
**Get a project repository storage move**
**Operation ID:** `getApiV4ProjectRepositoryStorageMovesRepositoryStorageMoveId`

This feature was introduced in GitLab 13.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_storage_move_id` | path | integer | Yes | The ID of a project repository storage move |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectsRepositoryStorageMove](../schemas/APIEntitiesProjectsRepositoryStorageMove/APIEntitiesProjectsRepositoryStorageMove.md)

