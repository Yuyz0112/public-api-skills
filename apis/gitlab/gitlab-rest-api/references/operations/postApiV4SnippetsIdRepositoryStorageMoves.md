# POST /api/v4/snippets/{id}/repository_storage_moves

**Resource:** [snippets](../resources/snippets.md)
**Schedule a snippet repository storage move**
**Operation ID:** `postApiV4SnippetsIdRepositoryStorageMoves`

This feature was introduced in GitLab 13.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a snippet |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesSnippetsRepositoryStorageMove](../schemas/APIEntitiesSnippetsRepositoryStorageMove/APIEntitiesSnippetsRepositoryStorageMove.md)

