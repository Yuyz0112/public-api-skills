# POST /api/v4/projects/{id}/repository_storage_moves

**Resource:** [projects](../resources/projects.md)
**Schedule a project repository storage move**
**Operation ID:** `postApiV4ProjectsIdRepositoryStorageMoves`

This feature was introduced in GitLab 13.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesProjectsRepositoryStorageMove](../schemas/APIEntitiesProjectsRepositoryStorageMove/APIEntitiesProjectsRepositoryStorageMove.md)

