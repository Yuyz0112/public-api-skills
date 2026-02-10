# GET /api/v4/snippets/{id}/repository_storage_moves/{repository_storage_move_id}

**Resource:** [snippets](../resources/snippets.md)
**Get a snippet repository storage move**
**Operation ID:** `getApiV4SnippetsIdRepositoryStorageMovesRepositoryStorageMoveId`

This feature was introduced in GitLab 13.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a snippet |
| `repository_storage_move_id` | path | integer | Yes | The ID of a snippet repository storage move |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSnippetsRepositoryStorageMove](../schemas/APIEntitiesSnippetsRepositoryStorageMove/APIEntitiesSnippetsRepositoryStorageMove.md)

