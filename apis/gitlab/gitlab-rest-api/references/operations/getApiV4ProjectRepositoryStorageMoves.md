# GET /api/v4/project_repository_storage_moves

**Resource:** [project_repository_storage_moves](../resources/project-repository-storage-moves.md)
**Get a list of all project repository storage moves**
**Operation ID:** `getApiV4ProjectRepositoryStorageMoves`

This feature was introduced in GitLab 13.0.

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

[APIEntitiesProjectsRepositoryStorageMove](../schemas/APIEntitiesProjectsRepositoryStorageMove/APIEntitiesProjectsRepositoryStorageMove.md)

