# GET /api/v4/projects/{id}/repository_storage_moves/{repository_storage_move_id}

**Resource:** [projects](../resources/projects.md)
**Get a project repository storage move**
**Operation ID:** `getApiV4ProjectsIdRepositoryStorageMovesRepositoryStorageMoveId`

This feature was introduced in GitLab 13.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `repository_storage_move_id` | path | integer | Yes | The ID of a project repository storage move |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectsRepositoryStorageMove](../schemas/APIEntitiesProjectsRepositoryStorageMove/APIEntitiesProjectsRepositoryStorageMove.md)

