# GET /api/v4/projects/{id}/repository_storage_moves

**Resource:** [projects](../resources/projects.md)
**Get a list of all project repository storage moves**
**Operation ID:** `getApiV4ProjectsIdRepositoryStorageMoves`

This feature was introduced in GitLab 13.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectsRepositoryStorageMove](../schemas/APIEntitiesProjectsRepositoryStorageMove/APIEntitiesProjectsRepositoryStorageMove.md)

